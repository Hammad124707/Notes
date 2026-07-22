#Notes

A computer can also be described
abstractly, by specifying and demonstrating its machine language capabilities

A machine language is an agreed-upon formalism, designed to code low-level
programs as series of machine instructions. 
A machine language can be viewed as an agreed-upon formalism, designed to manipulate a memory using a processor and a set of registers
A machine language program is a series of coded instructions. For example, a typical
instruction in a 16-bit computer may be 1010001100011001. In order to figure out
what this instruction means, we have to know the rules of the game, namely, the instruction set of the underlying hardware platform.

the language designer can decide that the operation code
1010 will be represented by the mnemonic add and that the registers of the machine
will be symbolically referred to using the symbols R0, R1, R2, and so forth. Using
these conventions, one can specify machine language instructions either directly, as
1010001100011001, or symbolically, as, say, ADD R3,R1,R9.

we can use a text processing program
to parse the symbolic commands into their underlying fields (mnemonics and operands), translate each field into its equivalent binary representation, and assemble the
resulting codes into binary machine instructions. The symbolic notation is called assembly language, or simply assembly, and the program that translates from assembly
to binary is called assembler.

#instructions
