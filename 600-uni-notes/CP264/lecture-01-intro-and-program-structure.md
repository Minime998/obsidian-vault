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
```ad-note
title: Terminal Options
icon: info
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

### C program structure model
```ad-note
title: Basic structure
icon: info

[preprocessor directives]
[global variables]
[function declarations]
main( arguments ) {
[statements]
}
[function definitions]
```

### Basic Syntax
* Basic symbols

![[Screenshot 2022-01-09 155836.png]]

- C has 32 reserved words

![[Screenshot 2022-01-09 160031.png]]

- Expressions:
	- Use infix notation consists of constants, variables, operators, parenthesis
	```ad-example

	(1 + 2) X 3, 1=2, (1=1) && (2!=1)

	```
- Statements:
	- A C statement is a command/instruction to the C compiler
	- A statement can be a declaration, assignment, condition, function call, flow control statements of selection, and repetition

- Program block:
	- A program **block**, scoped by { }, is a sequence of statements

- Function
	- Function declaration/header syntax:
	```C
	typename function_name(argument type list);
	```
	- Function def/implementation syntax:
	```C
	typename function_name(argument type and name list){
	// function block
	}
	```
	- Function call syntax:
	```C
	function_name(parameter list)
	```

### Data types

- A data type (or type) defines:
	1. how a certain type of data value is represented in programs
	2. how many bytes are used to represent the data value and how a dat value is represented in bit pattern and stored in memory
	3. what operations are applied to the data values and how data values are operated in the operations

**Brief description:** data type defines how certain type of data represented and operated in programming and computers

- C provides primary (primitive or basic) data types, defined by keywords: *char*, *int*, *float*, *double*, *short*, *long*, *signed*, *unsigned*

- C provides methods to build secondary (derived, extended) data types, using primary, data types, pointer, array, struct, union, Enum

### Primary data types

![[Screenshot 2022-01-10 083405.png]]

- each data type has a *size*, i.e *the number of bytes* required to store the values of the type in memory and has a *value range*
```ad-example
the int type has 2 in old 16 bits systems, but has 4 bytes in 32 and 64 bits systems
**we will assume that int has 4 bytes in this course**

```
### The char type

*char* type is used to present characters as an integer defined by ASCII code

```ad-example
A is coded as 65, a as 97, 0 as 48
```

![[Screenshot 2022-01-10 084216.png]]

- each addressable memory cell hold 8 buts (1 byte). When a data type has a bugger size than 1, it needs a contiguous memory cells (called memory block) to store the value of the type
- The char type has 1 byte, it uses one addressable memory cell.

```ad-example
Character A is coded as 65
The binary rep of 65 is *100 0001*
A is stored in memory as *0100 0001*
```

### How int type is stored in memory

The int type uses 4 bytes

*Big-endian*: Store the most significant byte in the lowest address cell
*Little-endian*: store the least significant byte in the lowest address cell

![[Screenshot 2022-01-10 084953.png]]

### float and double types

- *float* type uses *4 bytes* for single precision floating point numbers, defined by IEEE 754 standard
- *double* type uses *8 bytes* for double precision floating point numbers, defined by IEEE 754 standard

### Variables

* *concepts of variables*
1. A variable is a name (identifier) used in source code to rep a dat value of a certain type
2. S variable is assigned a memory block with relative address at the compile time, as well as instructions to set and get values to the memory block
3. The memory block of a variable is instantiated with the absolute address at at runtime

Brief description: **a variable is an identifier of a data value in a program, it gets memory block allocation at the compile time, and absolute memory space (instanced) at runtime**

### Variables in C

- A var must be declared with a type and name
- The var declaration lets compiler to assign memory block with relative address, and generate instructions to allocate memory space for the variable at runtime
- A var has to be indicated or assigned a value by assignment statement before it can be used at runtime.
- C car names must start with a letter, followed by letters, underscores and numbers, and case sensitive
- C name convention:
	- undercore_style, camelCaseStyle
- *Variable scope*
	- each var has a scope where it is declared and be accessed by statements within the scope A var has to be declared before it can be used
	- global vars are variables declared not in any block. so can be used anywhere
	- local variables are vars declared in a block

### sizeof

- sizeof is a unary operator used to calculate the sizes of data 
- returns the size of the var