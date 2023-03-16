#alx-low_level_programming

this project explors different ways of compiling and running a c code.

# 0, savse a c file into a global variable called $CFILE
          export $CFILE=main.c
     run the c file through a preprocessor
          gcc -E $CFILE -o c

# 1, compiles the c file named the same as it c file but with extension .o
          main.c ==>  main.o
          
# 2, generates the assembley of a code and save it in an output file with extension .s
          main.c ==> main.s
          
# 3, creates an executable file named cidfun
          gcc $CFILE -o cisfun
          
# 4,  a C program that prints a text without using printf and return 0

# 5,  a C program that prints a text using printf and return 0

# 6,  a C program that prints the size of different types on a 64 and 32 bit computers

# 7, a script that generates the assembly code(intel syntax) of a C code and saves it in a file with extension .s

# 8, a script that prints a text into the standard error and returns 1

