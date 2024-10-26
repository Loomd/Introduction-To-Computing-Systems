# Solutions to Chapter 2 Exercises
**Author:** Aaron Hunter  
**Date:** 10/25/2024

## Exercise Solutions

### 2.1
Given \( n \) bits, how many distinct combinations of the \( n \) bits exist?

---

### 2.2
There are 26 characters in the alphabet we use for writing English.  
- What is the least number of bits needed to give each character a unique bit pattern? 
- How many bits would we need to distinguish between upper- and lowercase versions of all 26 characters?

---

### 2.3
a. Assume that there are about 400 students in your class. If every student is to be assigned a unique bit pattern, what is the minimum number of bits required to do this?  
b. How many more students can be admitted to the class without requiring additional bits for each student’s unique bit pattern?

---

### 2.4
Given \( n \) bits, how many unsigned integers can be represented with the \( n \) bits? What is the range of these integers?

---

### 2.5
Using five bits to represent each number, write the representations of 7 and −7 in:
- 1’s complement
- Signed magnitude
- 2’s complement integers

---

### 2.6
Write the six-bit 2’s complement representation of −32.

---

### 2.7
Create a table showing the decimal values of all four-bit 2’s complement numbers.

---

### 2.8
a. What is the largest positive number one can represent in an eight-bit 2’s complement code? Write your result in binary and decimal.  
b. What is the greatest magnitude negative number one can represent in an eight-bit 2’s complement code? Write your result in binary and decimal.  
c. What is the largest positive number one can represent in \( n \)-bit 2’s complement code?  
d. What is the greatest magnitude negative number one can represent in \( n \)-bit 2’s complement code?

---

### 2.9
How many bits are needed to represent Avogadro’s number \( (6.02 \times 10^{23}) \) in 2’s complement binary representation?

---

### 2.10
Convert the following 2’s complement binary numbers to decimal:
a. 1010  
b. 01011010  
c. 11111110  
d. 0011100111010011

---

### 2.11
Convert these decimal numbers to eight-bit 2’s complement binary numbers:
a. 102  
b. 64  
c. 33  
d. −128  
e. 127  

---

### 2.12
If the last digit of a 2’s complement binary number is 0, then the number is even. If the last two digits of a 2’s complement binary number are 00 (e.g., the binary number 01100), what does that tell you about the number?

---

### 2.13
Without changing their values, convert the following 2’s complement binary numbers into eight-bit 2’s complement numbers:
a. 1010  
b. 011001  
c. 1111111000  
d. 01  

---

### 2.14
Add the following bit patterns. Leave your results in binary form.
a. 1011 + 0001  
b. 0000 + 1010  
c. 1100 + 0011  
d. 0101 + 0110  
e. 1111 + 0001  

---

### 2.15
It was demonstrated in Example 2.5 that shifting a binary number one bit to the left is equivalent to multiplying the number by 2. What operation is performed when a binary number is shifted one bit to the right?

---

### 2.16
Write the results of the following additions as both eight-bit binary and decimal numbers. For each part, use standard binary addition as described in Section 2.5.1.
a. Add the 1’s complement representation of 7 to the 1’s complement representation of −7.  
b. Add the signed magnitude representation of 7 to the signed magnitude representation of −7.  
c. Add the 2’s complement representation of 7 to the 2’s complement representation of −7.  

---

### 2.17
Add the following 2’s complement binary numbers. Also express the answer in decimal.
a. 01 + 1011  
b. 11 + 01010101  
c. 0101 + 110  
d. 01 + 10  

---

### 2.18
Add the following unsigned binary numbers. Also, express the answer in decimal.
a. 01 + 1011  
b. 11 + 01010101  
c. 0101 + 110  
d. 01 + 10  

---

### 2.19
Express the negative value −27 as a 2’s complement integer, using eight bits. Repeat, using 16 bits. Repeat, using 32 bits. What does this illustrate with respect to the properties of sign-extension as they pertain to 2’s complement representation?

---

### 2.20
The following binary numbers are four-bit 2’s complement binary numbers. Which of the following operations generate overflow? Justify your answer by translating the operands and results into decimal.
a. 1100 + 0011  
b. 1100 + 0100  
c. 0111 + 0001  
d. 1000 − 0001  
e. 0111 + 1001  

---

### 2.21
Describe what conditions indicate overflow has occurred when two 2’s complement numbers are added.

---

### 2.22
Create two 16-bit 2’s complement integers such that their sum causes an overflow.

---

### 2.23
Describe what conditions indicate overflow has occurred when two unsigned numbers are added.

---

### 2.24
Create two 16-bit unsigned integers such that their sum causes an overflow.

---

### 2.25
Why does the sum of a negative 2’s complement number and a positive 2’s complement number never generate an overflow?

---

### 2.26
You wish to express −64 as a 2’s complement number.
a. How many bits do you need (the minimum number)?  
b. With this number of bits, what is the largest positive number you can represent? (Please give answer in both decimal and binary.)  
c. With this number of bits, what is the largest unsigned number you can represent? (Please give answer in both decimal and binary.)

---

### 2.27
The LC-3, a 16-bit machine, adds the two 2’s complement numbers 0101010101010101 and 0011100111001111, producing 1000111100100100. Is there a problem here? If yes, what is the problem? If no, why not?

---

### 2.28
When is the output of an AND operation equal to 1?

---

### 2.29
Fill in the following truth table for a one-bit AND operation.
| X | Y | X AND Y |
|---|---|---------|
| 0 | 0 |         |
| 0 | 1 |         |
| 1 | 0 |         |
| 1 | 1 |         |

---

### 2.30
Compute the following. Write your results in binary.
a. 01010111 AND 11010111  
b. 101 AND 110  
c. 11100000 AND 10110100  
d. 00011111 AND 10110100  
e. (0011 AND 0110) AND 1101  
f. 0011 AND (0110 AND 1101)  

---

### 2.31
When is the output of an OR operation equal to 1?

---

### 2.32
Fill in the following truth table for a one-bit OR operation.
| X | Y | X OR Y |
|---|---|--------|
| 0 | 0 |        |
| 0 | 1 |        |
| 1 | 0 |        |
| 1 | 1 |        |

---

### 2.33
Compute the following:
a. 01010111 OR 11010111  
b. 101 OR 110  
c. 11100000 OR 10110100  
d. 00011111 OR 10110100  
e. (0101 OR 1100) OR 1101  
f. 0101 OR (1100 OR 1101)  

---

### 2.34
Compute the following:
a. NOT(1011) OR NOT(1100)  
b. NOT(1000 AND (1100 OR 0101))  
c. NOT(NOT(1101))  
d. (0110 OR 0000) AND 1111  

---

### 2.35
In Example 2.11, what are the masks used for?

---

### 2.36
Refer to Example 2.11 for the following questions.

- **a.** What mask value and what operation would one use to indicate that machine 2 is busy?
- **b.** What mask value and what operation would one use to indicate that machines 2 and 6 are no longer busy? (Note: This can be done with only one operation.)
- **c.** What mask value and what operation would one use to indicate that all machines are busy?
- **d.** What mask value and what operation would one use to indicate that all machines are idle?
- **e.** Using the operations discussed in this chapter, develop a procedure to isolate the status bit of machine 2 as the sign bit. For example, if the BUSYNESS pattern is `01011100`, then the output of this procedure is `10000000`. If the BUSYNESS pattern is `01110011`, then the output is `00000000`. In general, if the BUSYNESS pattern is:  
  `b7 b6 b5 b4 b3 b2 b1 b0`  
  the output is:  
  `b2 0 0 0 0 0 0 0`  
  **Hint:** What happens when you ADD a bit pattern to itself?

---

### 2.37
If `n` and `m` are both four-bit 2’s complement numbers, and `s` is the four-bit result of adding them together, how can we determine, using only the logical operations described in Section 2.6, if an overflow occurred during the addition? Develop a “procedure” for doing so. The inputs to the procedure are `n`, `m`, and `s`, and the output will be a bit pattern of all 0s (`0000`) if no overflow occurred and `1000` if an overflow did occur.

---

### 2.38
If `n` and `m` are both four-bit unsigned numbers, and `s` is the four-bit result of adding them together, how can we determine, using only the logical operations described in Section 2.6, if an overflow occurred during the addition? Develop a “procedure” for doing so. The inputs to the procedure are `n`, `m`, and `s`, and the output will be a bit pattern of all 0s (`0000`) if no overflow occurred and `1000` if an overflow did occur.

---

### 2.39
Write IEEE floating point representation of the following decimal numbers.

- **a.** 3.75
- **b.** −55.359375 (−55 23/64)
- **c.** 3.1415927
- **d.** 64,000

---

### 2.40
Write the decimal equivalents for these IEEE floating point numbers.

- **a.** `0 10000000 00000000000000000000000`
- **b.** `1 10000011 00010000000000000000000`
- **c.** `0 11111111 00000000000000000000000`
- **d.** `1 10000000 10010000000000000000000`

---

### 2.41
- **a.** What is the largest exponent the IEEE standard allows for a 32-bit floating point number?
- **b.** What is the smallest exponent the IEEE standard allows for a 32-bit floating point number?

---

### 2.42
A computer programmer wrote a program that adds two numbers. The programmer ran the program and observed that when 5 is added to 8, the result is the character "m." Explain why this program is behaving erroneously.

---

### 2.43
Translate the following ASCII codes into strings of characters by interpreting each group of eight bits as an ASCII character.

- **a.** `x48656c6c6f21`
- **b.** `x68454c4c4f21`
- **c.** `x436f6d70757465727321`
- **d.** `x4c432d32`

---

### 2.44
What operation(s) can be used to convert the binary representation for 3 (i.e., `0000 0011`) into the ASCII representation for 3 (i.e., `0011 0011`)? What about the binary 4 into the ASCII 4? What about any digit?

---

### 2.45
Convert the following unsigned binary numbers to hexadecimal.

- **a.** `1101 0001 1010 1111`
- **b.** `001 1111`
- **c.** `1`
- **d.** `1110 1101 1011 0010`

---

### 2.46
Convert the following hexadecimal numbers to binary.

- **a.** `x10`
- **b.** `x801`
- **c.** `xF731`
- **d.** `x0F1E2D`
- **e.** `xBCAD`

---

### 2.47
Convert the following hexadecimal representations of 2’s complement binary numbers to decimal numbers.

- **a.** `xF0`
- **b.** `x7FF`
- **c.** `x16`
- **d.** `x8000`

---

### 2.48
Convert the following decimal numbers to hexadecimal representations of 2’s complement numbers.

- **a.** 256
- **b.** 111
- **c.** 123,456,789
- **d.** −44

---

### 2.49
Perform the following additions. The corresponding 16-bit binary numbers are in 2’s complement notation. Provide your answers in hexadecimal.

- **a.** `x025B + x26DE`
- **b.** `x7D96 + xF0A0`
- **c.** `xA397 + xA35D`
- **d.** `x7D96 + x7412`
- **e.** What else can you say about the answers to parts (c) and (d)?

---

### 2.50
Perform the following logical operations. Express your answers in hexadecimal notation.

- **a.** `x5478 AND xFDEA`
- **b.** `xABCD OR x1234`
- **c.** `NOT((NOT(xDEFA)) AND (NOT(xFFFF)))`
- **d.** `x00FF XOR x325C`

---

### 2.51
What is the hexadecimal representation of the following numbers?

- **a.** 25,675
- **b.** 675.625 (i.e., 675 5/8), in the IEEE 754 floating point standard
- **c.** The ASCII string: "Hello"

---

### 2.52
Consider two hexadecimal numbers: `x434F4D50` and `x55544552`. What values do they represent for each of the five data types shown?

|                | x434F4D50 | x55544552 |
|----------------|-----------|-----------|
| Unsigned binary          |           |           |
| 1’s complement           |           |           |
| 2’s complement           |           |           |
| IEEE 754 floating point  |           |           |
| ASCII string             |           |           |

---

### 2.53
Fill in the truth table for the equations given. The first line is done as an example.

\( Q1 = \text{NOT}(A \text{ AND } B) \)  
\( Q2 = \text{NOT}(\text{NOT}(A) \text{ AND } \text{NOT}(B)) \)

| A | B | Q1 | Q2 |
|---|---|----|----|
| 0 | 0 |  1 |  0 |
| 0 | 1 |    |    |
| 1 | 0 |    |    |
| 1 | 1 |    |    |

Express \( Q2 \) another way.

---

### 2.54
Fill in the truth table for the equations given. The first line is done as an example.

\( Q1 = \text{NOT}(\text{NOT}(X) \text{ OR } (X \text{ AND } Y \text{ AND } Z)) \)  
\( Q2 = \text{NOT}((Y \text{ OR } Z) \text{ AND } (X \text{ AND } Y \text{ AND } Z)) \)

| X | Y | Z | Q1 | Q2 |
|---|---|---|----|----|
| 0 | 0 | 0 |  0 |  1 |
| 0 | 0 | 1 |    |    |
| 0 | 1 | 0 |    |    |
| 0 | 1 | 1 |    |    |
| 1 | 0 | 0 |    |    |
| 1 | 0 | 1 |    |    |
| 1 | 1 | 0 |    |    |
| 1 | 1 | 1 |    |    |

---

### 2.55
We have represented numbers in base-2 (binary) and in base-16 (hex). We are now ready for unsigned base-4, which we will call "quad numbers." A quad digit can be 0, 1, 2, or 3.

- **a.** What is the maximum unsigned decimal value that one can represent with 3 quad digits?
- **b.** What is the maximum unsigned decimal value that one can represent with \( n \) quad digits?  
  *Hint*: Your answer should be a function of \( n \).
- **c.** Add the two unsigned quad numbers: `023` and `221`.
- **d.** What is the quad representation of the decimal number `42`?
- **e.** What is the binary representation of the unsigned quad number `123.3`?
- **f.** Express the unsigned quad number `123.3` in IEEE floating-point format.
- **g.** Given a black box that takes \( m \) quad digits as input and produces one quad digit for output, what is the maximum number of unique functions this black box can implement?

---

### 2.56
Define a new eight-bit floating-point format with the following specifications:

- **1 sign bit**
- **4 bits of exponent**, using an excess-7 code (i.e., the bias is 7)
- **3 bits of fraction**

If the bit pattern is `xE5` in this eight-bit floating-point format, what decimal value does it represent?
