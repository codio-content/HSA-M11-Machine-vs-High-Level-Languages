
A typical line in assembly language program might be as follows:

`LOOP:	 MOV.B r0, #80	     ;initialize counter`


This line will be assembled into a single instruction in machine code (binary) as: 

` 11 0000 1000 0000`

The assembly language and the machine code correspond to each other.

Each statement, or line of code,  in assembly language has four parts; label, mnemonic, operand, comment; however, not all are present in every line.

When you have written a program in assembly language, it actually consists of lots of ASCII characters; this would be stored in a file and called "source code". This then forms the input to a program called an "assembler" which can translate the "source code" into machine code. or object code. When the assembler has done its work, this line of source code will have been translated into a binary pattern, associated with a particular address in the program memory.

In the next section we will examine our Hello World! program a little closer. 


    
    

