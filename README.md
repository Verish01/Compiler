# Compiler for Simple Language of Expressions

Overview: This project builds upon a previous task where you created an arithmetic expression evaluator for a language called E++. In this assignment, you will enhance the efficiency of your previous implementation and develop a compiler that converts E++ expressions into code executable on a stack machine. This involves generating and not evaluating the code.

Syntax Extensions:

Delete Statement (del): Deletes variables that have been previously assigned values.
Return Statement (ret): Returns the value of an expression and stops the program.
Data Structures:

Replace the Binary Search Trees used for symbol tables with AVL Trees to ensure logarithmic time complexity for insertions, deletions, and lookups.
Code Generator:

You will generate code for a stack machine where operations are performed on a stack and results are stored in a memory array.
Commands include arithmetic operations, push and pop from stack, and special commands for handling memory.
Compiler and Memory Management:

Implement functions to parse expressions, assign memory addresses to variables, and handle deletions.
Memory allocation for variables will use a stack-like vector or an optional MinHeap for optimized address allocation.
Output and Testing:

Generate a Targ (target language) code file which will be executed on a simulated stack machine to validate output.
Enhancements for Bonus Marks:

Implement a MinHeap to optimize memory address allocation, ensuring that variables are mapped to the least available memory address.
Deliverables:

Convert symbol tables to use AVL Trees.
Implement a code generator that outputs Targ code according to the provided syntax.
Develop the compiler infrastructure to handle parsing, memory address assignment, and file output.
This task will test your ability to optimize data structures and develop a compiler that interfaces with a simulated machine architecture.
