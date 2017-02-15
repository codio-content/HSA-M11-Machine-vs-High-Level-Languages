## Compilers
A **compiler** is a special program that processes statements written in a particular programming language and turns them into machine language or "code" that a computer's processor uses. Typically, a programmer writes statements in a language such as Python or Java one line at a time using an editor.

*Here's a flow chart showing how high-level languages communicate with the computer:* 


![flow_chart](https://mentor-trident.codio.io/flow_chart.png)

The file that is created contains what are called the **source statements**. The programmer then runs the appropriate language compiler, specifying the name of the file that contains the source statements.  When executing (running), the compiler first parses (or analyzes) all of the language statements syntactically one after the other and then, in one or more successive stages or "passes", builds the output code, making sure that statements that refer to other statements are referred to correctly in the final code. 

If there are any errors in the source code, the compiler specifies the errors at the end of compilation. The errors must be removed before the compiler can successfully compile the source code. The object program can be executed a number of times without translating it again.

Traditionally, the output of the compilation has been called **object code**. The object code is machine code that the processor can execute one instruction at a time.
