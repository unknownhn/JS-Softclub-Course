# JavaScript String Methods
- The length property returns the length of a string

- slice() extracts a part of a string and returns the extracted part in a new string.
The method takes 2 parameters: start position, and end position (end not included).

- substring() is similar to slice().
The difference is that start and end values less than 0 are treated as 0 in substring().

- substr() is similar to slice().
The difference is that the second parameter specifies the length of the extracted part.

- The replace() method replaces a specified value with another value in a string
  >The replace() method does not change the string it is called on.
The replace() method returns a new string.
The replace() method replaces only the first match
If you want to replace all matches, use a regular expression with the /g flag set. See examples below.
  -The replaceAll() method allows you to specify a regular expression instead of a string to be replaced.
If the parameter is a regular expression, the global flag (g) must be set, otherwise a TypeError is thrown.
  >
- concat() joins two or more strings
- The trim() method removes whitespace from both sides of a string.
  
 and others...
