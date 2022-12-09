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
  *main - Entry poin
  *code by peppymstermind
  *Return: always 0
*/
int main(void)

{
        printf("Size of a char: %d byte(s)\n", sizeof(char));
        printf("Size of an int: %d byte(s)\n", sizeof(int));
        printf("Size of a long int: %d byte(s)\n", sizeof(long int));
        printf("Size of a long long int: %d byte(s)\n", sizeof(long long int));
        printf("Size of a float: %d byte(s)\n", sizeof(float));
        return (0);
} (C program that prints the size of various types on the computer it is compiled and run on )

7. gcc -S -masm=intel $CFILE (script that generates the assembly code (Intel syntax) of a C code and save it in an output file.)
