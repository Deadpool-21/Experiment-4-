AIM : To study and implement C++ Bitwise Operators

SOFTWARE USED : VS CODE

1) Theory
   
Bitwise operations are used to manipulate individual bits of data. These operations are faster and more memory-efficient,
making them essential in low-level programming, hardware interfacing, and performance-critical applications.

This experiment demonstrates two key concepts:

A. Bitwise Operator Demonstration
The following operators are applied to two integers:

AND (&): Sets each bit to 1 if both bits are 1.

OR (|): Sets each bit to 1 if at least one of the bits is 1.

XOR (^): Sets each bit to 1 only if the corresponding bits are different.

NOT (~): Inverts all bits of a number.

Left Shift (<<): Shifts bits to the left, inserting 0s on the right.

Right Shift (>>): Shifts bits to the right, discarding bits on the right.

These operations help understand how data is stored and manipulated at the binary level.

B. Bit Manipulation – Setting and Resetting Bits
This part focuses on controlling individual bits of a number:

Setting a Bit (to 1): Done using number | (1 << position)

Resetting a Bit (to 0): Done using number & ~(1 << position)

Here:

(1 << position) creates a mask with only the required bit set.

| ensures the bit is set.

~ inverts the mask and & clears the bit.

These are fundamental operations in embedded systems, flag management, and efficient storage techniques.

2) Algorithm
   
Part A: Bitwise Operators
Start the program.

Accept two integer inputs from the user.

Apply each of the following bitwise operators:

AND (&)

OR (|)

XOR (^)

NOT (~) on both numbers

Left Shift (<<)

Right Shift (>>)

Display the results of each operation in decimal form.

Analyze how each operator changes the binary representation of the values.

Part B: Set and Reset Bit
Input an integer number.

Input the bit position to be modified (starting from 0).

To set the bit:

Calculate: number | (1 << position)

Display the result.

To reset the bit:

Calculate: number & ~(1 << position)

Display the result.

End the program.

3) Procedure

Create a new C++ file.

Include the necessary header (#include <iostream>) and use the std namespace.

Define the main() function.

Declare variables for two integers and one bit position.

Take user inputs for the two integers.

Demonstrate the use of:

Bitwise AND, OR, XOR, NOT

Left Shift and Right Shift on both integers

Display each result using cout along with clear messages.

Accept a new input for the bit position and demonstrate:

Setting the bit at the given position.

Resetting the bit at the given position.

Compile and run the program.

Observe how each operation modifies the value and interpret the results.

4) Conclusion
   
This experiment significantly deepened the understanding of bitwise operations and bit manipulation techniques. It demonstrated how:
Arithmetic-like operations can be performed directly on bits.
Specific bits can be efficiently controlled using masks.
These skills are critical in systems programming, cryptography, graphics, and other domains requiring low-level data manipulation and optimized performance.
