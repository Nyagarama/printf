# PRINTF PROJECT

The essence of this project is to create a custom version of [printf](https://man7.org/linux/man-pages/man3/printf.3.html) function located in the ***stdio.h*** library. _printf_ function is used to print data to the standard output _(typically in the console)_ in a specified format. 

## _printf FUNCTION

_ _printf_ is a variadiac function that imitates the _printf_ function. It receives **n arguments** that replace **n tags.** It has the following prototype:

`int _printf(const char *format, ...);`
