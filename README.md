AUTHORING: Daniel Dreyer UMBC/CMSC 313 Spring 8:30AM

PURPOSE OF SOFTWARE: this is a program that will take the address varible of an ascii character convert it to the hex value and desplay it to the user and then return a line

FILES the only file before compilling is the HW11.asm file, this file holds all the program that will convert the ascii adresses to hex ascii values

BUILD INSTRUCTIONS: to build the program, please locate the HW11.asm file in your computer and make sure you are using 32-bit x86 (i found the best location for this is using bitvise and accessing UMBC's SSH on your own computer. then assemble using the command "nasm -f elf32 -g -F dwarf -o HW11.o HW11.asm" after that please use the command "ld -m elf_i386 -o HW11 HW11.o" to link and load, finally type "./HW11" to run the program

TESTING METHODOLOGY: after running the build instructions you will notice a HW11.o file and a HW11 program, then you know you have run it successfully, if you'd like to change the address data so other values can be produced, you can change them in the inputBuf area under the .data section, (the data already placed is the data given in the homework 11 instructions) it should desplay something like the example shown and submitted in my homework 11 assignmnet

ADDITIONAL INFORMATION: if you would like to know any more information on a particular section or line of code, i have placed comments throughout the program, lastly, the extra credit portion of subroutine is showned with the call statments to convert to ascii section
