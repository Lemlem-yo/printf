#Description
The printf function sends formatted output to stdout. A custom _printf() for learning purposes was developed by cohort #9 student Lemlem. _printf() function format string is a character string, beginning and ending in its initial shift state, if any. These arguments are placed using the percentage '%' operator
#RESOURCES
	the secret of printf https://www.academia.edu/10297206/Secrets_of_printf_
#Authorized functions and macros
	write (man 2 write)
	malloc (man 3 malloc)
	free (man 3 free)
	va_start (man 3 va_start)
	va_end (man 3 va_end)
	va_copy (man 3 va_copy)
	va_arg (man 3 va_arg)
#compilation
	The code must be compiled this way:

*$ gcc -Wall -Werror -Wextra -pedantic .c

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)

The main files will include your main header file (holberton.h): #include holberton.h


#Tasks required for this project
	0. I am not going anywhere. You can print that wherever you want to. I'm here and I am a Spur for life1. I am not going anywhere. You can print that wherever you want to. I'm here and I am a Spur for life.
Write a function that produces output according to a format. Handle the following conversion specifiers:

c
s
%
	1. Education is when you read the fine print. Experience is what you get if you dont
Handle the following conversion specifiers:

d
i
	2. Just because its in print doesn't mean its the gospel
Create a man page for the function
