C++ Compiler

Sequentially goes through each source code file in program and first

Checks C++ code to make sure it follows the rules of C++ language

Then translates the code in machine language instructions, stored in an an Object File temporarily.

The object file contains other data that's required in other steps. 


Then there's the linker

The linker combines all the object files and produced the desired output file

Process is called linking

First, it reads in each of the object files and makes sure they're valid
Then it ensures all cross-file dependencies are resolved (ex. importing one class from another)

Then links in library files defined in the code

Finally, outputs desired output file, which is usually an executable
