# Bitwise Operators in C++

Aim: To study and implement C++ Bitwise Operators  
Tools Used: VS Code or Programiz Online Compiler

---

## Theory

Bitwise operators work directly on the binary digits (bits) of integer values, allowing programmers to manipulate data at its most fundamental level. These operators enable precise control over individual bits, making them useful in hardware control, cryptography, and performance optimization.

- Bitwise AND (&): Compares each bit of a and b. Result is 1 only if both bits are 1.  
- Bitwise OR (|): Compares each bit of a and b. Result is 1 if at least one bit is 1.  
- Bitwise NOT (~): Flips all bits of the operand.  
- Bitwise XOR (^): Compares each bit of a and b. Result is 1 if the bits are different.  
- Left Shift (<<): Shifts bits of a to the left by n positions (multiplies by 2ⁿ).  
- Right Shift (>>): Shifts bits of a to the right by n positions (divides by 2ⁿ).

---

In C++ (and other programming languages), bit set and bit reset refer to operations that manipulate individual bits within an integer's binary representation using bitwise operators. These operations are commonly used in low-level programming, such as working with hardware registers, flags, or optimizing data storage.

Definitions:
Bit Set: Setting a bit means changing a specific bit in a number to 1, regardless of its previous value. This is typically done using the bitwise OR (|) operator with a mask.

Bit Reset (or Clear): Resetting a bit means changing a specific bit in a number to 0, regardless of its previous value. This is typically done using the bitwise AND (&) operator with the complement of a mask.

## Algorithm

### Program 1 – Bitwise Operations

1. Declare and initialize two integer variables, a and b.  
2. Perform bitwise AND, OR, XOR, NOT on both a and b.  
3. Compute left shift and right shift for both a and b.  
4. Output all results.

### Program 2 – Bit Set/Reset

1. Use the standard namespace.  
2. Declare an integer variable n with value 12.  
3. Ask user for a bit position to set.  
4. Set the bit using OR and left shift. Output the result.  
5. Ask user for a bit position to reset.  
6. Reset the bit using AND with NOT and left shift. Output the result.

---

## Conclusion

This program effectively demonstrates the use of bitwise operators in C++. Bitwise operations are essential in systems-level programming, offering optimized performance for binary-level data manipulation.

