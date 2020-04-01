# 4/2/20 Agenda
Spiel on interpreted vs compiled.

## Hello world
```
I share window, you code on yours
printf, no include, no \n
gcc hello.c
run a.out (may need ./)
fix include warning and \n
gcc hello.c -o hello (output file!)
```
## expand printf and more functions.
Here we'll switch to J's mac.
```
Common formats:
%d - print number as integer
%c - print character
%s - print string

MANY other formatting options available (leading zeros, precision, base, etc).  Google search to see them all.
```
Write a function that prints the numbers from 1 to 10.

Talk about declaration vs use.

# Later
Pre-processing, compiling, linking.  Simplified model.

gcc options:
-o output_executable
-c makes it into an object.
`gcc -c hello.c` makes hello.o

-o then lets you put objects into an exe:
`gcc -o hello hello.o

## scanf

## argc, argv

## bigger projects
### static vs extern

