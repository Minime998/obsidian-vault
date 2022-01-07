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

Compiling steps

takes four steps:
1. pre-processing (resolve lines with pre-processor directives)
2. compilation (Convert C to assembly program)
3. assemble (convert the assemble to binary format, called object programs)
4. linking (link object files with other library files to make exe)