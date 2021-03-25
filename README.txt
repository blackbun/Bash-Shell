# Terminal Bash Shell

Name:	Nicholas Blackburn
Class:	CS 344
Date:	8/4/19
File:	Program3 - smallsh.c - README

						Description

This program is a small shell environment written in C.  Its main commands are cd, status, and exit.  It can also execute any other
normal linux bash commands.  Input and output files for redirection may be used.  Commands may be executed as foreground or background processes.  Signals can be received by the shell.

						Compile Instructions

- First compile with this command

gcc -std=c99 -o smallsh smallsh.c

- Then run this command to start the shell:

./smallsh

