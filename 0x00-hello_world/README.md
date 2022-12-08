PREPROCESSOR
gcc $CFILE -E -o c (a script that runs a C file through the preprocessor and save the result into another file. File name is $CFILE)
gcc -c $CFILE (a script that compiles a C file but does not link. File name is $CFILE)
gcc -S $CFILE  (a script that generates the assembly code of a C code and save it in an output file)
gcc $CFILE -o cisfun ( a script that compiles a C file and creates an executable named cisfun)
#include <stdio.h> 
/**
 * main - print a line of code using puts 
 * 
 * Return: 0 
*/

int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");
	return (0);
} (a C program that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.)
