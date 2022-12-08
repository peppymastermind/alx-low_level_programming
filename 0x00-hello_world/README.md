PREPROCESSOR
0. gcc $CFILE -E -o c (a script that runs a C file through the preprocessor and save the result into another file. File name is $CFILE)

1. gcc -c $CFILE (a script that compiles a C file but does not link. File name is $CFILE)


2. gcc -S $CFILE  (a script that generates the assembly code of a C code and save it in an output file)

3. gcc $CFILE -o cisfun ( a script that compiles a C file and creates an executable named cisfun)

4. #include <stdio.h> 
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


5. #include <stdio.h> 
/**
 * main - print a line of code using printf
 *
 * Return: 0
*/

int main(void)
{
	printf("with proper grammar, but the outcome is a piece of art,\n");
	return (0);
} (a C program that prints exactly with proper grammar, but the outcome is a piece of art, followed by a new line)



6. #include <stdio.h>
/**
 * main - print out sizes of data types in C
 * Code by peppymastermind
 * Return: 0
 */

int main(void)
{
        char a;
        int b;
        long int c;
        long long int d;
        float f;

        printf("Size of a char: %lu byte(S)\n", (unsigned long)sizeof(a));
        printf("Size of an int: %lu byte(S)\n", (unsigned long)sizeof(b));
        printf("Size of a long int: %lu byte(S)\n", (unsigned long)sizeof(c));
        printf("Size of a long long int: %lu byte(S)\n", (unsigned long)sizeof(d));
        printf("Size of a float: %lu byte (S)\n", (unsigned long)sizeof(f));
        return (0);
} (C program that prints the size of various types on the computer it is compiled and run on)
