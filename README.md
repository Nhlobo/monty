# Monty Project

## Overview
Monty is a scripting language interpreter that processes Monty byte code files. The language relies on a unique stack with specific instructions to manipulate it.

## Project Structure
- **monty.h**: Header file containing struct definitions and function prototypes.
- **push.c**: Implementation of the push opcode.
- **pall.c**: Implementation of the pall opcode.
- **pint.c**: Implementation of the pint opcode.
- **pop.c**: Implementation of the pop opcode.
- **swap.c**: Implementation of the swap opcode.
- **add.c**: Implementation of the add opcode.
- **nop.c**: Implementation of the nop opcode.

## Compilation & Usage
Compile the code using the provided compilation command:
```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty


Run the interpreter with the following command:
```bash
$ ./monty <file_path>


## Error Handling
- Memory allocation errors are handled gracefully with appropriate messages.
- Opcode-specific errors are reported with line numbers.


## AUTHOR
This file list all contributors of the repository

Novice Mathebula <nhlobo365@gmail.com>
