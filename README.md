# seq.asm
UNIX SEQ x86_64 


COMPILING
----------------------

code written in Intel-Syntax Assembly
NEED nasm to compile



COMPILE DOING FOLLOWING
--------------------------

$ nasm -f elf64 -o seq.o seq.asm

$ ld -o seq seq.o



USAGE
----------------------------
accepts either parameter for sequence generation:

./seq <start> <end>
  
  or
  
./seq <end>
  
if only one argument is provided, start is assumed to be 1.





EXAMPLES
----------------------------------

Two Arguments:

$ ./seq 10 15
10
11
12
13
14
15




