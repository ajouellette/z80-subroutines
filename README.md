# Assembly subroutines for the z80

This is a collection of z80 assembly subroutines, mainly for use in assembly programming on
the TI-83/84+ graphing calculators.

Theses subroutines are divided into two major groups: those that depend on TI-OS
(these might use `bcalls` or need labels defined by `ti83plus.inc`) and general 
routines that do not depend on any specific OS.

# Use

To minimize the space usage of the finished program,
Each file contains only a couple, sometimes 1 subroutine.

Put `#include "file"` at the end of your program (or wherever 
you store your subroutines). Use `call routine` to call a specific 
subroutine.

# Credits

Many of these subroutines were found on the Cemetech forums. 
When the author is known, credit is given.

# Contributing

If you know of any other useful subroutines, feel free to create
a pull request.
