This is a project done by me and my partner
Authorized functions and macros
write (man 2 write)
malloc (man 3 malloc)
free (man 3 free)
va_start (man 3 va_start)
va_end (man 3 va_end)
va_copy (man 3 va_copy)
va_arg (man 3 va_arg)
Compilation
Your code will be compiled this way:
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)
Our main files will include your main header file (main.h): #include main.h
You might want to look at the gcc flag -Wno-format when testing with your _printf and the standard printf.

Files contained in this repository
Main.h: Header file with the data type struct
_printf.c:  Main printf function file
TASK0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
WRITE A FUNCTION THAT PRODUCES OUTPUT ACCORDING TO A FORMAT.
Handle the following conversion specifiers:
c
s
%
1. Education is when you read the fine print. Experience is what you get if you don't
Handle the following conversion specifiers:

d
i
2. With a face like mine, I do better in print
Handle the following custom conversion specifiers:

b: the unsigned int argument is converted to binary
3. What one has not experienced, one will never understand in print
Handle the following conversion specifiers:

u
o
x
X
4. Nothing in fine print is ever good news
Use a local buffer of 1024 chars in order to call write as little as possible.
5. My weakness is wearing too much leopard print
Handle the following custom conversion specifier:

S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)
6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier: p.
7. The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:

+
space
#
8. Sarcasm is lost in print
Handle the following length modifiers for non-custom conversion specifiers:

l
h
Conversion specifiers to handle: d, i, u, o, x, X
9. Print some money and give it to us for the rain forests
Handle the field width for non-custom conversion specifiers.
10. The negative is the equivalent of the composer's score, and the print the performance
Handle the precision for non-custom conversion specifiers.
11. It's depressing when you're still around and your albums are out of print
Handle the 0 flag character for non-custom conversion specifiers.
12. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
Handle the - flag character for non-custom conversion specifiers.
13. Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:

r : prints the reversed string
14. The flood of print has turned reading into a process of gulping rather than savoring
Handle the following custom conversion specifier:

R: prints the rot13'ed string
15. *
All the above options work well together.

Authors
Fateemah Toyosi
Richard Akintola
