# BitwiseOperators-EXP4-

AIM-To learn bitwise functions(1 & 0)

APPARATUS:VS code/Programiz

ALGORITHM

  Program 1(Bitwise)

 1) Declare and initialize two integer variables, a and b.

 2) Perform bitwise operations on a and b:

 3)Compute bitwise AND, OR, XOR, NOT (for both a and b).

 4)Compute left shift and right shift for both a and b.

 5)Output the results of all bitwise operations.

PROGRAM 2(RESET)

   Use standard namespace for simplified name access.

   Start main program.

   Declare and initialize an integer variable n with value 12.

   Declare variables for bit position inputs and operation outputs.

  Prompt and store user input for bit position to set.

  Set the specified bit in n using bitwise OR and left shift, then output the result.

  Prompt and store user input for bit position to reset.

   Reset the specified bit in n using bitwise AND and NOT with left shift, then output the result.

THEORY:

1. Bitwise AND (&)
Operation: Compares each bit of a and b. If both bits are 1, the result is 1; otherwise, it is 0.

2. Bitwise OR (|)
Operation: Compares each bit of a and b. If either bit is 1, the result is 1.

3. Bitwise NOT (~)
Operation: Flips all the bits of the operand. Converts all 0s to 1s and vice versa.

5. Bitwise XOR (^)
Operation: Compares each bit of a and b. If the bits are different, the result is 1; otherwise, it is 0.

6. Left Shift (<<)
Operation: Shifts all bits of a to the left by n positions, inserting 0s from the right. This is equivalent to multiplying the number by 2ⁿ.

8. Right Shift (>>) 
Operation: Shifts all bits of a to the right by n positions, discarding bits on the right. This is equivalent to integer division by 2ⁿ

Conclusion:
This program effectively demonstrates how various bitwise operations work in C++. Bitwise operators are powerful tools for low-level data manipulation, offering optimized performance in situations where direct binary manipulation is required.
