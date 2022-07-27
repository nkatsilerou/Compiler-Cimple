# Compiler-Cimple
This project is about making a compiler for the visual programming language C-imple. The input is a .ci program and the output is an .asm (assembly) file for RISC-V. In the fist part of the project we constructed a lexical analyzer who converts a seqeunce of characters (in this case the input program) into a sequence of lexical tokens. The second part is the syntax analysis which is the process of analyzing a string of symbols , conforming to the rules of a formal grammar which in our case is C-imples' grammar. The third part is the intermediate code generation, in which we create quads to help the code generator (.c and .int). The fourth part is the symbol table management, in which we create the scopes to be able to understand the visibility of our variables (.symb) and the fifth part is the code generator, in which we create the assembly code for the RISC-V (.asm).
The test
