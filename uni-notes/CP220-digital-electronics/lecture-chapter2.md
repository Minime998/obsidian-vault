#digital-electronics 
# Number systems operations and codes
## Chapter 2

### Summary

[[#2 1 Decimal Numbering System]]

[[#2 2 Binary Numbers]]
- [[#Binary-to-decimal Conversion]]

#### 2.1 Decimal Numbering System

The decimal numbering system has 10 digits 0-9

The decimal numbering system has a base of 10 with each position weighted by a factor of 10

...10^5, 10^4..10^0, 10^-1..

14.2 = 1 X 10^1 +4 X 10^0 + 2 X 10^-1

#### 2.2 Binary Numbers

The binary number system has 2 digits 0 and 1

The binary numbering system has a base of 2 with each position weighted by a factor of 2

...2^5...2^0...2^-2

10111 = 1 X 2^4 + 0 X 2^3 + 1 X 2^3 + 1 X 2^0

The largest decimal number = 2^n-1

**Example**: n=4
2^n - 1 = 2^4 - 1 = 15

##### Binary-to-decimal Conversion

**Example**: convert binary 0.1011 to decimal
- **Solution**: Determine the weight of each bit that is a 1, and then sum the weights to get the decimal fraction

Weight: 2^-1 2^-2 2^-3 2^-4
Binary number: 0 . 1 0 1 1

0.1011 = 2^-1 - 2^-3 - 2^-4 => 0.5 + 0.125 + 0.0625 => 0.6875

##### Decimal-to-Binary Conversion

**Sum-of-weight Method**:
- Decompose the decimal number into 2-power terms

Example: 9 = 8 +1 => 2^3 + 2^0 --> 1 0 0 1

---

### Summary

#### Binary Arithmetic

- Binary addition
- Binary subtraction
- Binary multiplication
- Binary division

##### Binary Addition

0 + 0 Sum of 0 with a carry of 0

0 + 1 = 1 Sum of 1 with a carry of 0

1 + 0 = 1 Sum of 1 with a carry of 0

1 + 1 = 10 Sum of 1 with a carry of 1

11001 + 1101 = 100110

##### Binary Subtraction

0 - 0 = 0

1 - 1 = 0

1 - 0 = 1

10 - 1 = 1 0-1 with a borrow of 1

1011 - 111 = 100

##### Binary Multiplication

0 X 0 = 0

0 X 1 = 0

1 X 0 = 0

1 X 1 = 1

100110 X 101 = 100110
 
 ##### Binary Division
 
 #### 1's and 2's Complements of Binary numbers
 
 The 1's **complement** of a binary number is found by changing all 1's to 0's and all 0's to 1's as show below:
 
0 0 0 1 1 0 0 1 0 0 1 0 1 | Binary number

1 1 1 0 0 1 1 0 1 1 0 1 0

##### Finding 2's complement

2's complement = 1's complement + 1

#### Signed Numbers

**Sign bit** - a 0 is for positive a 1 is for negative

**Sign-Magnitude** - a negative number has the same magnitude as the corresponding positive number but the sign bit is q rather than 0
- 0 0011001 = +0011001 | 1 0011001 = -0011001

1's complement form a negative number is the 1's complement of the corresponding positive number
- +25 == **0**0011001; | -25 == **1**1100110 (1's Comp.)

2's complement form a negative number is the 2's complement of the corresponding positive number
- +25 == **0**0011001; | -25 == **1**1100111 (2's Comp.)

##### Decimal value of signed numbers



 

