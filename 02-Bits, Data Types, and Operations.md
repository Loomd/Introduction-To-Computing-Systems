# Solutions to Chapter 2 Exercises
**Author:** Aaron Hunter  
**Date:** 10/25/2024

## Exercise Solutions

### 2.1
- Given \( n \) bits, how many distinct combinations of the \( n \) bits exist?
  - 2^n combinations.
---

### 2.2
- There are 26 characters in the alphabet we use for writing English.  
  - What is the least number of bits needed to give each character a unique bit pattern? 
  - How many bits would we need to distinguish between upper- and lowercase versions of all 26 characters?
    - 5 bits.
    - 6 bits.
---

### 2.3
- a. Assume that there are about 400 students in your class. If every student is to be assigned a unique bit pattern, what is the minimum number of bits required to do this?  
- b. How many more students can be admitted to the class without requiring additional bits for each student’s unique bit pattern?
  - (a): 9 bits allows for 512 students.
  - (b): 112 students.
---

### 2.4
- Given \( n \) bits, how many unsigned integers can be represented with the \( n \) bits? What is the range of these integers?
  - 2^n unsigned integers.  
  - range: from 0 to 2^n - 1.
---

### 2.5
- Using five bits to represent each number, write the representations of 7 and −7 in:
  - 1’s complement
  - Signed magnitude
  - 2’s complement integers
    - 1's complement: 7 = 00111, -7 = 11000.
    - Signed magnitude: 7 = 00111, -7 = 10111.
    - 2's complement integers: 7 = 00111, -7 = 11001.
---

### 2.6
- Write the six-bit 2’s complement representation of −32.
  - 100000
---

### 2.7
- Create a table showing the decimal values of all four-bit 2’s complement numbers.
  | bin	 | dec|
  |------|----|
  | 0000 |  0 |
  | 0001 |  1 |	   
  | 0010 |  2 |	   
  | 0011 |  3 |	   
  | 0100 |  4 |	   
  | 0101 |  5 |	   
  | 0110 |  6 |	   
  | 0111 |  7 |	   
  | 1000 | -8 |	   
  | 1001 | -7 |	   
  | 1010 | -6 |	   
  | 1011 | -5 |	   
  | 1100 | -4 |	   
  | 1101 | -3 |
  | 1110 | -2 |
  | 1111 | -1 |
---

### 2.8
- a. What is the largest positive number one can represent in an eight-bit 2’s complement code? Write your result in binary and decimal.  
- b. What is the greatest magnitude negative number one can represent in an eight-bit 2’s complement code? Write your result in binary and decimal.  
- c. What is the largest positive number one can represent in \( n \)-bit 2’s complement code?  
- d. What is the greatest magnitude negative number one can represent in \( n \)-bit 2’s complement code?
  - (a): 01111111, 127
  - (b): 10000000, -128
  - (c): 2^(n-1).
  - (d): 2^n.
---

### 2.9
- How many bits are needed to represent Avogadro’s number \( (6.02 \times 10^{23}) \) in 2’s complement binary representation?
  - 1 sign bit, 8 exponent bits, 23 precision bits: 32 bits. 
---

### 2.10
- Convert the following 2’s complement binary numbers to decimal:
  - a. 1010             : -6
  - b. 01011010         : 90
  - c. 11111110         : -2
  - d. 0011100111010011 : 14803
---

### 2.11
- Convert these decimal numbers to eight-bit 2’s complement binary numbers:
  - a. 102  : 01100110
  - b. 64   : 01000000
  - c. 33   : 00100001
  - d. −128 : 10000000 
  - e. 127  : 01111111
---

### 2.12
- If the last digit of a 2’s complement binary number is 0, then the number is even. If the last two digits of a 2’s complement binary number are 00 (e.g., the binary number 01100), what does that tell you about the number?
  - it's an even number divisible by 4.
---

### 2.13
- Without changing their values, convert the following 2’s complement binary numbers into eight-bit 2’s complement numbers:
  - a. 1010       : 11111010
  - b. 011001     : 00011001
  - c. 1111111000 : 11111000
  - d. 01         : 00000001
---

### 2.14
- Add the following bit patterns. Leave your results in binary form.
  - a. 1011 + 0001
  - b. 0000 + 1010
  - c. 1100 + 0011
  - d. 0101 + 0110
  - e. 1111 + 0001
      - (a): 1100
      - (b): 1010
      - (c): 1111
      - (d): 1011
      - (e): 0000
---

### 2.15
- It was demonstrated in Example 2.5 that shifting a binary number one bit to the left is equivalent to multiplying the number by 2. What operation is performed when a binary number is shifted one bit to the right?
  - integer division by 2.
---

### 2.16
- Write the results of the following additions as both eight-bit binary and decimal numbers. For each part, use standard binary addition as described in Section 2.5.1.
  - a. Add the 1’s complement representation of 7 to the 1’s complement representation of −7.  
  - b. Add the signed magnitude representation of 7 to the signed magnitude representation of −7.  
  - c. Add the 2’s complement representation of 7 to the 2’s complement representation of −7.  
    - (a): 11111111, (decimal: 0)
    - (b): 10000000, (decimal: -0)
    - (c): 00000000, (decimal: 0)
---

### 2.17
- Add the following 2’s complement binary numbers. Also express the answer in decimal.
  - a. 01 + 1011
  - b. 11 + 01010101
  - c. 0101 + 110
  - d. 01 + 10
    - (a): 1100,     (decimal: -4)
    - (b): 01011000, (decimal: 88)
    - (c): 0011,     (decimal:  3)
    - (d): 11,      ( decimal: -1)
---

### 2.18
- Add the following unsigned binary numbers. Also, express the answer in decimal.
  - a. 01 + 1011
  - b. 11 + 01010101
  - c. 0101 + 110
  - d. 01 + 10
    - (a): 1100,     (decimal: 12)
    - (b): 01011000, (decimal: 88)
    - (c): 1011,     (decimal: 11)
    - (d): 11,       (decimal:  3)
---

### 2.19
- Express the negative value −27 as a 2’s complement integer, using eight bits. Repeat, using 16 bits. Repeat, using 32 bits. What does this illustrate with respect to the properties of sign-extension as they pertain to 2’s complement representation?
  - 8 bits:  11100101
  - 16 bits: 1111111111100101
  - 32 bits: 11111111111111111111111111100101
---

### 2.20
- The following binary numbers are four-bit 2’s complement binary numbers. Which of the following operations generate overflow? Justify your answer by translating the operands and results into decimal.
	- a. 1100 + 0011  
	- b. 1100 + 0100  
	- c. 0111 + 0001  
	- d. 1000 − 0001   
	- e. 0111 + 1001  
		- (a): No overflow; result fits within four bits.
		- (b): No overflow here either, as 0 is within the four-bit range.
		- (c): Overflow occurs because the sum of two positive numbers (7 + 1) results in a negative number (-8) due to bit limitations.
		- (d): Overflow occurs here, as the difference of a negative and a positive value results in a positive value that cannot be accurately represented due to sign inconsistency.
		- (e): No overflow.
---

### 2.21
- Describe what conditions indicate overflow has occurred when two 2’s complement numbers are added.
  - Overflow occurs when adding two positive numbers results in a negative or adding two negative numbers results in a positive.
---

### 2.22
- Create two 16-bit 2’s complement integers such that their sum causes an overflow.
  - Positive overflow example: 0111111111111111 + 0000000000000001
  - Negative overflow example: 1000000000000000 + 1000000000000000
---

### 2.23
- Describe what conditions indicate overflow has occurred when two unsigned numbers are added.
  - Overflow in unsigned addition happens if the sum of two numbers exceeds the maximum value for the bit length (e.g., for 4 bits, a sum above 15).
---

### 2.24
- Create two 16-bit unsigned integers such that their sum causes an overflow.
  - 65535 (1111111111111111) + 1 (0000000000000001) causes an overflow because the result (65536) cannot be represented with 16 bits.
---

### 2.25
- Why does the sum of a negative 2’s complement number and a positive 2’s complement number never generate an overflow?
  - Because there is an equal number of positive and negative values associated with 2^n bits in 2's complement meaning if you add or subtract one positive to one negative all possible outcomes
  - provided that you stay within permitted values will always fall between the max or min possible representation of a value.
---

### 2.26
- You wish to express −64 as a 2’s complement number.
	- a. How many bits do you need (the minimum number)?  
	- b. With this number of bits, what is the largest positive number you can represent? (Please give answer in both decimal and binary.)  
	- c. With this number of bits, what is the largest unsigned number you can represent? (Please give answer in both decimal and binary.)
		- (a): You need 8 bits at minimum.
		- (b): Assuming this question is asking in 2's complement, the largest positive number with 8 bits would be 0111 1111 in binary, which is 127 in decimal.
		- (c): For the largest unsigned number with 8 bits, it would be 1111 1111 in binary, which is 255 in decimal.
---

### 2.27
- The LC-3, a 16-bit machine, adds the two 2’s complement numbers 0101010101010101 and 0011100111001111, producing 1000111100100100. Is there a problem here? If yes, what is the problem? If no, why not?
  - Yes, there is an overflow problem. Adding two positive numbers should yield a positive result, but here, the result starts with a 1 in the sign bit, indicating a negative number due to overflow.
---

### 2.28
- When is the output of an AND operation equal to 1?
  - When both operands are 1.
---

### 2.29
- Fill in the following truth table for a one-bit AND operation.
  | X | Y | X AND Y |
  |---|---|---------|
  | 0 | 0 |    0    |
  | 0 | 1 |    0    |
  | 1 | 0 |    0    |
  | 1 | 1 |    1    |
---

### 2.30
- Compute the following. Write your results in binary.
	- a. 01010111 AND 11010111  
	- b. 101 AND 110  
	- c. 11100000 AND 10110100  
	- d. 00011111 AND 10110100  
	- e. (0011 AND 0110) AND 1101  
	- f. 0011 AND (0110 AND 1101)  
		- (a): 01010111
		- (b): 100
		- (c): 10100000
		- (d): 00010100
		- (e): 0000
		- (f): 0000
---

### 2.31
- When is the output of an OR operation equal to 1?
  - When one of the operands are 1.
---

### 2.32
- Fill in the following truth table for a one-bit OR operation.
  | X | Y | X OR Y |
  |---|---|--------|
  | 0 | 0 |    0   |
  | 0 | 1 |    1   |
  | 1 | 0 |    1   |
  | 1 | 1 |    1   |
---

### 2.33
- Compute the following:
	- a. 01010111 OR 11010111  
	- b. 101 OR 110  
	- c. 11100000 OR 10110100  
	- d. 00011111 OR 10110100  
	- e. (0101 OR 1100) OR 1101  
	- f. 0101 OR (1100 OR 1101)  
		- (a): 11010111
		- (b): 111
		- (c): 11110100
		- (d): 10111111
		- (e): 1101
		- (f): 1101
---

### 2.34
- Compute the following:
	- a. NOT(1011) OR NOT(1100)  
	- b. NOT(1000 AND (1100 OR 0101))  
	- c. NOT(NOT(1101))  
	- d. (0110 OR 0000) AND 1111  
		- (a): 0111
		- (b): 0111
		- (c): 1101
		- (d): 0110
---

### 2.35
- In Example 2.11, what are the masks used for?
   -  The bit mask in this example is used to isolate the target machines and flip them to available or busy.
---

### 2.36
- Refer to Example 2.11 (1100 0010) for the following questions:
  - a. What mask value and what operation would one use to indicate that machine 2 is busy?  
    - 1100 0000, AND
  - b. What mask value and what operation would one use to indicate that machines 2 and 6 are no longer busy? (Note: This can be done with only one operation.)  
    - 1110 0010, OR
  - c. What mask value and what operation would one use to indicate that all machines are busy?  
    - 0000 0000, AND
  - d. What mask value and what operation would one use to indicate that all machines are idle?  
    - 1111 1111, OR
  - e. Using the operations discussed in this chapter, develop a procedure to isolate the status bit of machine 2 as the sign bit.  
    - Example: if the BUSYNESS pattern is `01011100`, the output should be `10000000`.  
    - In general, if the BUSYNESS pattern is `b7 b6 b5 b4 b3 b2 b1 b0`, the output should be `b2 0 0 0 0 0 0 0`.  
    - **Hint:** What happens when you ADD a bit pattern to itself?  
    - Following the example you would add 0111 1100
---

### 2.37
- If `n` and `m` are both four-bit 2’s complement numbers, and `s` is the four-bit result of adding them together, how can we determine, using only the logical operations described in Section 2.6, if an overflow occurred during the addition?  
  - Develop a procedure to determine overflow.  
  - Inputs: `n`, `m`, and `s`.  
  - Output: a bit pattern of all 0s (`0000`) if no overflow occurred, and `1000` if an overflow did occur.  
  - overflow_negative = (n3 AND m3)AND(NOT s3)
  - overflow_positive = (NOT n3 AND NOT m3) AND s3
  - overflow = overflow_negative OR overflow_positive
---

### 2.38
- If `n` and `m` are both four-bit unsigned numbers, and `s` is the four-bit result of adding them together, how can we determine, using only the logical operations described in Section 2.6, if an overflow occurred during the addition?  
  - Develop a procedure for determining overflow.  
  - Inputs: `n`, `m`, and `s`.  
  - Output: a bit pattern of all 0s (`0000`) if no overflow occurred, and `1000` if an overflow did occur.  
  - overflow = (n3 AND m3) OR ((n2 AND m2) AND (n1 OR m1))
---

### 2.39
- Write IEEE floating point representation of the following decimal numbers:
  - a. 3.75  
    - 0 10000000 11100000000000000000000
  - b. −55.359375 (−55 23/64)  
    - 1 10000100 10111010111000000000000
  - c. 3.1415927  
    - 0 10000000 10010010000111111011010
  - d. 64,000  
    - 0 10001110 11110100000000000000000
---

### 2.40
- Write the decimal equivalents for these IEEE floating point numbers:
  - a. `0 10000000 00000000000000000000000`  
    -  2.0
  - b. `1 10000011 00010000000000000000000`  
    - -17.00
  - c. `0 11111111 00000000000000000000000`  
    -  +∞
  - d. `1 10000000 10010000000000000000000`  
    -  -3.125
---

### 2.41
- a. What is the largest exponent the IEEE standard allows for a 32-bit floating point number?  
  - 254 (binary 11111110).
- b. What is the smallest exponent the IEEE standard allows for a 32-bit floating point number?  
  -   1 (binary 00000001).
---

### 2.42
- A computer programmer wrote a program that adds two numbers. The programmer ran the program and observed that when 5 is added to 8, the result is the character "m." Explain why this program is behaving erroneously.  
  - Programmer is adding ASCII value (character 5 and 8).
---

### 2.43
- Translate the following ASCII codes into strings of characters by interpreting each group of eight bits as an ASCII character:
  - a. `x48656c6c6f21`  
    - Hello!
  - b. `x68454c4c4f21`  
    - hELLO!
  - c. `x436f6d70757465727321`  
    - Computers!
  - d. `x4c432d32`  
    - LC-2
---

### 2.44
- What operation(s) can be used to convert the binary representation for 3 (i.e., `0000 0011`) into the ASCII representation for 3 (i.e., `0011 0011`)? What about the binary 4 into the ASCII 4? What about any digit?  
  - Perform an OR operation with 0011 0000 (hexadecimal 0x30).
---

### 2.45
- Convert the following unsigned binary numbers to hexadecimal:
  - a. `1101 0001 1010 1111`  
    - D 1 A F
  - b. `001 1111`  
    - 1 F
  - c. `1`  
    - 1
  - d. `1110 1101 1011 0010`  
    - E D B 2
---

### 2.46
- Convert the following hexadecimal numbers to binary:
  - a. `x10`  
    - 0000000000010000
  - b. `x801`  
    - 0000100000000001
  - c. `xF731`  
    - 1111011100110001
  - d. `x0F1E2D`  
    - 000011110001111000101101
  - e. `xBCAD`  
    - 1011110010101101
---

### 2.47
- Convert the following hexadecimal representations of 2’s complement binary numbers to decimal numbers:
  - a. `xF0`  
    - 11110000         (-16)
  - b. `x7FF`  
    - 011111111111     (2047)
  - c. `x16`  
    - 00010110         (22)
  - d. `x8000`  
    - 1000000000000000 (-32768)
---

### 2.48
- Convert the following decimal numbers to hexadecimal representations of 2’s complement numbers:
  - a. 256  
    - x0100
  - b. 111  
    - x006F
  - c. 123,456,789  
    - x075BCD15
  - d. −44  
    - x002C
---

### 2.49
- Perform the following additions. The corresponding 16-bit binary numbers are in 2’s complement notation. Provide your answers in hexadecimal:
  - a. `x025B + x26DE`  
    - x2939
  - b. `x7D96 + xF0A0`  
    - x6E36
  - c. `xA397 + xA35D`  
    - x46F4
  - d. `x7D96 + x7412`  
    - xF1A8
  - e. What else can you say about the answers to parts (c) and (d)?  
    - Both results fall within the 16-bit range but have opposite signs.
---

### 2.50
- Perform the following logical operations. Express your answers in hexadecimal notation:
  - a. `x5478 AND xFDEA`  
    - x5448
  - b. `xABCD OR x1234`  
    - xBBFD
  - c. `NOT((NOT(xDEFA)) AND (NOT(xFFFF)))`  
    - xDEFA
  - d. `x00FF XOR x325C`  
    - x32A3
---

### 2.51
- What is the hexadecimal representation of the following numbers?
  - a. 25,675  
    - x644B
  - b. 675.625 (i.e., 675 5/8), in the IEEE 754 floating point standard  
    - x4428A400
  - c. The ASCII string: "Hello"  
    - x48656c6c6f
---

---

### 2.52
- Consider two hexadecimal numbers: `x434F4D50` and `x55544552`. What values do they represent for each of the five data types shown?

  |                          |          x434F4D50              |         x55544552              |
  |--------------------------|---------------------------------|--------------------------------|
  | Unsigned binary          |01000011010011110100110101010000 |01010101010101000100010101010010|
  | 1’s complement           |                                 |                                |
  | 2’s complement           |01000011010011110100110101010000 |01010101010101000100010101010010|
  | IEEE 754 floating point  |          1573235200             |           1431308034           |
  | ASCII string             |            COMP                 |               UTER             |
---

### 2.53
- Fill in the truth table for the equations given. The first line is done as an example.

  - Q1 = NOT(A AND B)  
  - Q2 = NOT(NOT(A) AND NOT(B))

  | A | B | Q1 | Q2 |
  |---|---|----|----|
  | 0 | 0 |  1 |  0 |
  | 0 | 1 |  1 |  1 |
  | 1 | 0 |  1 |  1 |
  | 1 | 1 |  0 |  1 |

- Express \( Q2 \) another way.
  - A OR B

---

### 2.54
- Fill in the truth table for the equations given. The first line is done as an example.

- Q1 = NOT(NOT(X) OR (X AND Y AND Z))
- Q2 = NOT((Y OR Z) AND (X AND Y AND Z))

  | X | Y | Z | Q1 | Q2 |
  |---|---|---|----|----|
  | 0 | 0 | 0 |  0 |  1 |
  | 0 | 0 | 1 |  0 |  1 |
  | 0 | 1 | 0 |  0 |  1 |
  | 0 | 1 | 1 |  0 |  1 |
  | 1 | 0 | 0 |  1 |  1 |
  | 1 | 0 | 1 |  1 |  1 |
  | 1 | 1 | 0 |  1 |  1 |
  | 1 | 1 | 1 |  0 |  0 |
---

### 2.55
- We have represented numbers in base-2 (binary) and in base-16 (hex). We are now ready for unsigned base-4, which we will call "quad numbers." A quad digit can be 0, 1, 2, or 3.

- **a.** What is the maximum unsigned decimal value that one can represent with 3 quad digits?
    - 3^3 + 3^2 + 3 = 63
- **b.** What is the maximum unsigned decimal value that one can represent with \( n \) quad digits?  
  *Hint*: Your answer should be a function of \( n \).
  - 4^n − 1
- **c.** Add the two unsigned quad numbers: `023` and `221`.
  - 320
- **d.** What is the quad representation of the decimal number `42`?
  - 210
- **e.** What is the binary representation of the unsigned quad number `123.3`?
  - 0010 1011 11.11
- **f.** Express the unsigned quad number `123.3` in IEEE floating-point format.
  - x42F60000
- **g.** Given a black box that takes \( m \) quad digits as input and produces one quad digit for output, what is the maximum number of unique functions this black box can implement?
  - 4^4^m
---

### 2.56
- Define a new eight-bit floating-point format with the following specifications:

- **1 sign bit**
  - This bit is 0 for positive numbers and 1 for negative numbers.
- **4 bits of exponent**, using an excess-7 code (i.e., the bias is 7)
  - The exponent is stored by adding 7 to the actual exponent value to allow for both positive and negative exponents. For example, an actual exponent of -3 would be represented by 4 (since -3 + 7 = 4).
- **3 bits of fraction**
  - These bits represent the fractional part of the number, effectively providing precision within the normalized range.
---
