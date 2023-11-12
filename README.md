# PRINTF PROJECT

The essence of this project is to create a custom version of [printf](https://man7.org/linux/man-pages/man3/printf.3.html) function located in the ***stdio.h*** library. _printf_ function is used to print data to the standard output _(typically in the console)_ in a specified format. 

## _printf FUNCTION

_ _printf_ is a variadiac function that imitates the _printf_ function. It receives **n arguments** that replace **n tags.** It has the following prototype:

`int _printf(const char *format, ...);`

***format** is a pointer to the string printed while the format tag syntax is `%specifier`

### FORMAT SPECIFIER

[Format specifier](https://www.simplilearn.com/tutorials/c-tutorial/format-specifiers-in-c) tell the compiler the type of data given _(input)_ and the type of data to be printed on the screen _(output)_.

|Specifier | Output |
| :---: | :---: |
| `%d or %i` | Decimal or Signed integer |
| `%c` | Signed character |
| `%f` | Signed float |
| `%e` | Float-point number |
| `%s` | String or sequence of character |
| `%S` | String with special chars replaced by their ASCII value |
| `%lf` | double |
| `%Lf` | Long double |
| `%o` | Octal integer |
| `%u` | Short unsigned integer |
| `%ld` | Long decimal integer |
| `%x` | Hexadecimal integer |
| `%X` | Unsigned hexadecimal integer (Uppercase) |
| `%p` | Print memory address in the hexadecimal form |
| `%b` | Signed binary |
| `%r` | Reverse string of characters |
| `%R` | ROT13 translation of string |
 
