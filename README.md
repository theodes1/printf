# 0x11.C - printf

This is a project that's part of the first trimester of Holberton School curriculum. Our printf project replicates part of the C standard library printf() function.

## Prototype

int _printf(const char *format, ...);

## Usage

Prints a string to the standard output, according to a given format

All files were created and compiled on Ubuntu Ubuntu 22.04.1 LTS using GCC 4.8.4 with the command gcc -Wall -Werror -Wextra -pedantic - Wno-format *.c

All files were linted for syntax and style with Betty

Returns the number of characters in the output string on success, -1 otherwise

Call it this way: _printf("format string", arguments...) where format string can contain conversion specifiers and flags, along with regular characters.


#### Files contained in this repository

|Name                |Description                 
README.md|		Update README.md |
_printf.c|		Create _printf.c|
functions.c|		Create functions.c|
functions1.c|		Create functions1.c|
functions2.c|		Create functions2.c|
get_flags.c|		Create get_flags.c|
get_precision.c	|	Create get_precision.c|
get_size.c	|	Create get_size.c|
get_width.c	|	Create get_width.c|
handle_print.c	|	Create handle_print.c|
main.h		|	Create main.h|
utils.c		|	Create utils.c|
write_handlers.c|	Create write_handlers.c|

-------------------------------------------------------------------------------------------------

#### Task requested in this project
------------

0. ##### I am not going anywhere. You can print that wherever you want to. I'm here and I am a Spur for life1.  I am not going anywhere. You can print that wherever you want to. I'm here and I am a Spur for life. 

Write a function that produces output according to a format.
Handle the following conversion specifiers:
- c
- s
- %

1. ##### Education is when you read the fine print. Experience is what you get if you dont

Handle the following conversion specifiers:
- d
- i

2. ##### Just because its in print doesn't mean its the gospel
Create a man page for the function

3. ##### With a face like mine, I do better in print|
Handle the following conversion specifiers:
- b

4. ##### What one has not experienced, one will never understand in print
Handle the following conversion specifiers:
- u
- x
- o
- x
- X

5. ##### Nothing in fine print is ever good news
Use a local buffer of 1024 chars in order to call write as little as possible.

6. ##### Handle the following custom conversion specifier
- S : prints the string.
- Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters).

7. ##### How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier: p

8. ##### The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:
- ??+??
- space
- ??#?? 

9. ##### Sarcasm is lost in print
Handle the following length modifiers for non-custom conversion specifiers:
- l
- h
Conversion specifiers to handle: d, i, u, o, x, X

10. ##### Print some money and give it to us for the rain forests
Handle the field width for non-custom conversion specifiers.

11. ##### The negative is the equivalent of the composer's score, and the print the performance
Handle the precision for non-custom conversion specifiers.

12. ##### It's depressing when you're still around and your albums are out of print
Handle the 0 flag character for non-custom conversion specifiers.

13. ##### Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
Handle the - flag character for non-custom conversion specifiers.

14. ##### Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:
 - r : prints the reversed string

15. ##### The flood of print has turned reading into a process of gulping rather than savoring 
Handle the following custom conversion specifier:
- R: prints the rot13'ed string

16. ##### *
All the above options work well together.

- Samuel Obayemi -[Github](https://github.com/theodes1) / [Linkedin](linkedin.com/in/samuel-obayemi-631025153/)
- Ridwanullahi Badmus -[Github](https://github.com/https://github.com/Sagna112) / [Linkedin](https://www.linkedin.com/in/badmus-ridwanullahi-540012202/)

