# Advanced Functions

Advanced functions is a collection of functions which can be used in the smart box to enabled advanced evaluation of text. Unlike [built-in functions](https://docs.microsoft.com/en-us/dotnet/api/system.data.datacolumn.expression?view=netframework-4.7.2) like IIF, LEN, SUBSTRING where literals need to be enclosed into the brackets '', it is not required for advanced functions.

All advanced functions names are enclosed with _ symbols.

To enable formula evaluations it is required to add = symbol at the beginning.

## Formulas

### \_Replace\_

Function finds the specified symbols withing the string and replaces with new value

*Arguments*:
* String to replace
* Value to find in the string
* Value to replace

~~~
=_Replace_(AB-001, AB, CD)

Result: CD-001
~~~

### \_IndexOf\_

Finds the first 0-based index of the symbol(s) within the search string. -1 is returned if no index found

*Arguments*:
* Input string to search index in
* String to search

~~~
=_IndexOf_(ABCDEF,C)

Result: 2
~~~

### \_LastIndexOf\_

Finds the last 0-based index of the symbol(s) within the search string. -1 is returned if no index found

*Arguments*:
* Input string to search index in
* String to search

~~~
=_LastIndexOf_(ABCDABEF,A)

Result: 4
~~~

### \_LCase\_

Converts all symbols into the lower case

*Arguments*:
* Input string to convert to lower case

~~~
=_LCase_(aBc)

Result: abc
~~~

### \_UCase\_

Converts all symbols into the upper case

*Arguments*:
* Input string to convert to upper case

~~~
=_UCase_(aBc)

Result: ABC
~~~

### \_TruncateStart\_

Trims the beginning of the string with specified symbol

*Arguments*:
* Input string to truncate
* Symbol to truncate with

~~~
=_TruncateStart_(__Abc__,_)

Result: Abc__
~~~

### \_TruncateEnd\_

Trims the ending of the string with specified symbol

*Arguments*:
* Input string to truncate
* Symbol to truncate with

~~~
=_TruncateEnd_(__Abc__,_)

Result: __Abc
~~~

### \_IIF\_

Performs the logical evaluation of the first parameter and returns either 2nd or 3rd argument depending on the result

*Arguments*:
* Logical expression which evaluates to boolean (True or False)
* Value to return if logical expression returns True
* Value to return if logical expression returns False

~~~
=_IIF_(10=10,TruePart,FalsePart)

Result: TruePart
~~~

### \_IsNumeric\_

Checks if the provided input is a numeric type (including floating numbers)

*Arguments*:
* Input to check

~~~
=_IsNumeric_(10.5)

Result: True
~~~

### \_Switch\_

Allows to perform the logical evaluation on multiple conditions (if-then-elseif-...-elseif-else)

*Arguments*:
* First logical condition
* Value to return if the condition is True
* Else If condition
* Value to return if Else If condition is True
* Another Else If condition

...

* Value to return if no of the conditions are true


~~~
=_Switch_(Condition1,Value if Condition 1 is True,Else Condition2,Value if Condition 2 is True,...,Value if none of the conditions is true)
~~~

~~~
=_Switch_('A'='B',L1,'A'='C',L2,'A'='D',L3,'A'='A',L4,L5)

Result: L4
~~~

### \_Length\_

Returns the number of symbols in the input text

*Arguments*:
* Input string to calculate the number of symbols

~~~
=_Length_(ABCD)

Result: 4
~~~

### \_Substring\_

Returns the part of the string starting at the specified 0-based index with the specified length

*Arguments*:
* String to get substring from
* Starting 0-based index
* Length of the part

~~~
=_Substring_(ABCDEF,1,2)

Result: BC
~~~

### Escaping Special Symbols

Comma , and brackets () symbols are the special symbols used to specify the parameters of the string. If Any of these special symbols needs to be used as the values itself's they need to be escaped with \" symbol

~~~
=_Replace_(\"AB,1\",\",\",.)

Result: AB.1
~~~

### Nested Formulas

Formulas and placeholders can be used as a parameter of other formulas or placeholders

~~~
=_IIF_(_IsNumeric_(AB),Numeric,NotNumeric)

Result: NotNumeric
~~~