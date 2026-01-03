# Chapter 2 Notes
## Hello World

C is a *Low-Level* language.

Something about C that can cause confusion in those learning it is **Pointers**. Those with previous programming experience might already be familiar with the *concept* behind Pointers, however C forces users to be explicit with their use. 

```c

#include <stdio.h> 

/* Anything begining with an '#' is something the C Preprocessor will operate on before the compiler even gets started.*/

/* After the 'C Preprocessor' finishes preprocessing everything, the result is ready for the **Compiler* to render "Machine Code" (1s and 0s, not human-readable) or "Assembly Code" (Assembly-Level code) */

/* After the octothorpe, "include" is a "Preprocessor Directive" - of which there are several */

/* Next, "<stdio.h>" a "Header File" (the '.h' is how you know that), more specifically it is the "Standard I/O" (stdio) header file, giving our file access to necessary I/O functionality, the `printf` function to be precise. */

int main(void)

/* The "main" function stands out as chiefly as being the first function that will be called when your program starts executing. Nothing gets called before `main() */ 

```