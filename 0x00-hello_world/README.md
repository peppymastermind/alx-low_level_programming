PREPROCESSOR
gcc $CFILE -E -o c (a script that runs a C file through the preprocessor and save the result into another file. File name is $CFILE)
gcc -c $CFILE (a script that compiles a C file but does not link. File name is $CFILE)
gcc -S $CFILE  (a script that generates the assembly code of a C code and save it in an output file)
