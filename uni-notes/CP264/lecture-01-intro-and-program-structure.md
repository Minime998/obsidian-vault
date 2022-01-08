#CP264

# Intro

## Compile and execution
- first program hello world

```C
#include<stdio.h> //include a header file
void main() // the main function
{
 printf("hello world!\n"); //prints out (function call)
}
```

To compile gcc hello.c
- will create an executable then for windows: a.exe

### Compiling steps

takes four steps:
1. pre-processing (resolve lines with pre-processor directives)
2. compilation (Convert C to assembly program)
3. assemble (convert the assemble to binary format, called object programs)
4. linking (link object files with other library files to make exe)

### Compiler Options
```Terminal
gcc-std=c99 (use C99 standard)
gcc-c hello.c (makes object file)
gcc-g hello.c (put diagnostic into object file)
gcc hello.c -o hello.exe (name exe)
gcc-S hello.c (makes assemble file)
```

### Execution

1. the exe is loaded onto memory
2. starts from the first instruction controlled by flow control until end
3. read from memory to CPU and then executed

---

# C programming language basics

## Summary
1. C program structure
2. basic syntax
3. data types
4. variables

### C program structure

- A C source program is organized into a sequence of functions
	- Must have the *main()* function for a exe program
		- The function of a C program begins from its main() function
	- A function has a logic sequence of statements
	- A statement can call another function, a function has to be declared or defined before it can be called
- After compiling, an exe is organized in sequences of blocks and functions 

### Structure Example

```C
/*
C program structure example
*/

include<stdio.h> // preprocessor directive include
int a; // global variable declaration
int add(int, int); // function declaration
int minus(int, int); // function declaration
int main() // main function

{
a=1; // assign/set value 1 to global variable a
int b=2; // declare local variable b and initialize/set it to value 2
printf("a+b=%d\n", add(a, b)); // function calls
printf("a-b=%d\n", minus(a, b)); // function calls

return 0; }
// definition/implementation of function add(int, int)
int add(int x, int y) // function header
{

return x+y; // function body 
}
// definition/implementation of function minus(int, int)
int minus(int x, int y) // function header 
{
return x-y; // function body 
} 
```
