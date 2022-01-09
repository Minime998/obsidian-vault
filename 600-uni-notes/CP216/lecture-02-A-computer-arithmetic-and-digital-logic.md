#CP216 

# Lecture-02-A
## Computer Arithmetic and Digital Logic 

## Chapter 2 A


### 2.1 What is data

*Data* is info such as numbers, text, computer programs, music, images, etc...
- Data is represented by 0's and 1's in the computer 

*Information* is anything that can be stored and manipulated by computers

The Bit and Byte and Bit Patterns:
- One bits (**2 values**)
- Two bits (**4 values**)
- Three bits (**8 values**)
- Four bits (**16 values**)
![[Screenshot 2022-01-06 144449.png]]

*ASCII Code*
![[Screenshot 2022-01-06 144430.png]]

### 2.2 The digits used by *four number bases*
![[Screenshot 2022-01-06 144810.png]]

The *Position Notation*:

The decimal numbering system has 10 digits 0-9
- has a base of 10 with each position weight by a factor of 10
- 10^5 10^4...10^0...10^-5

$$
14.2 = 1 \times 10^1 + 4 \times 10^0 + 2 \times 10^-1
$$


The binary number system has 2 digits 0 and 1
- has a base of 2 with each position weight by a factor of 2
- 2^5...2^0...2^-5
$$
10111 = 1 \times 2^4 +0 \times 2^3 + 1 \times 2^2 + 1 \times 2^1 + 1 \times 2^0
$$

### 2.3 Binary Arithmetic

Binary addition:
- 0 + 0 = 0 Sum of 0 with a carry of 0
- 0 + 1 = 1
- 1 + 0 = 1
- 1 + 1 = 10 Sum of 1 with a carry of 1
$$
11001+1101 \line{1,0}{1cm}  100110
$$

Binary Subtraction:
- 0 -0 = 0
- 1 - 1 = 0
- 1 - 0 = 1
- 10 - 1 = 1   0-1 with a borrow of 1
```
1011
-111
-----
100
```

Binary Multiplication:
- 0 x 0 = 0
- 0 x 1 = 0
- 1 x 0 = 0
- 1 x 1 = 1
```
100110
x  101
-------
  100110
 000000
100110
-------
10111110
```
