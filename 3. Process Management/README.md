# smallsh - CS 344

A basic shell that supports three built-in commands: exit, cd, and status.
Handles all other commands by spawning child processes to perform execvp().

USAGE: command [arg1 arg2 ...] [< input_file] [> output_file] [&]

To see the requirements for the project, read [req.md](/req.md).

# Compilation

To compile, type:

gcc smallsh.c -o smallsh