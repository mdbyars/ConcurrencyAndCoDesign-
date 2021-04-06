Software:

The hera file consists of a simple program that will read letters from memory and print them to alternating terminals. A string is first placed into ram and its size is stored in a register. The program then loops, reading a letter from the string each time and printing it out along with the contents of Register 2 that indicates which terminal each letter is being printed to. 


Hardware:

In order to print out the letters, two screens were added to to the processor. In order to print to these screens, an opcode (HEX: 1152) was added. The opcode specifies a register from which a character should be printed and a register that specifies which screen the character should be printed to. 