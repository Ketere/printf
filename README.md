AUTHORS;
LEONARD kETERE
FRANCIS CHOMBA


# printf Project

This project is a part of the Holberton School curriculum, authored by Leonard Ketere and Francis Chomba.

## Task 0: Implementing `_printf`

### Mandatory
Write a function that produces output according to a format.

- Prototype: `int _printf(const char *format, ...)`
- Returns: the number of characters printed (excluding the null byte used to end output to strings)
- Write output to stdout, the standard output stream
- Format is a character string. The format string is composed of zero or more directives. See `man 3 printf` for more detail.
- Handle the following conversion specifiers:
    - `c`
    - `s`
    - `%`
- You don’t have to reproduce the buffer handling of the C library printf function
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers


## Task 1: Handling Conversion Specifiers

### Mandatory
Handle the following conversion specifiers:

- `d`
- `i`
- You don’t have to handle the flag characters
- You don’t have to handle field width
- You don’t have to handle precision
- You don’t have to handle the length modifiers


## Task 2: Custom Conversion Specifiers

### Advanced
Handle the following custom conversion specifier:

- `b`: the unsigned int argument is converted to binary

Sample usage:
```c
_printf("%b\n", 98); // Output: 1100010


Task 3: More Conversion Specifiers
Advanced

Handle the following conversion specifiers:

    u
    o
    x
    X
    You don’t have to handle the flag characters
    You don’t have to handle field width
    You don’t have to handle precision
    You don’t have to handle the length modifiers

Task 4: Buffer Optimization
Advanced


task 5: Handling Custom Conversion Specifier
Advanced

handle the following custom conversion specifier:

    S: prints the string. Non-printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (uppercase - always 2 characters)

Sample usage:

c

_printf("%S\n", "Best\nSchool"); // Output: Best\x0ASchool


Task 6: Pointer Address
Advanced

Handle the following conversion specifier: p. You don’t have to handle the flag characters, field width, precision, or length modifiers.


Task 7: Handling Flag Characters
Advanced

Handle the following flag characters for non-custom conversion specifiers:

    +
    space
    #


Task 8: Handling Length Modifiers
Advanced

Handle the following length modifiers for non-custom conversion specifiers:

    l
    h

Conversion specifiers to handle: d, i, u, o, x, X


Task 9: Handling Field Width

Task 10: Handling Precision
Advanced

Handle the precision for non-custom conversion specifiers.


Task 11: Handling the 0 Flag Character
Advanced

Handle the 0 flag character for non-custom conversion specifiers.


Task 12: Handling the - Flag Character
Advanced

Handle the - flag character for non-custom conversion specifiers.

Task 13: Custom Conversion Specifier (Reversed String)
Advanced

Handle the following custom conversion specifier:

    r: prints the reversed string


Task 14: Custom Conversion Specifier (ROT13)
Advanced

Handle the following custom conversion specifier:

    R: prints the ROT13'ed string


Task 15: Comprehensive Implementation