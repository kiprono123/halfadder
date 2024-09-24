# BInary Addition
Binary addition is much like your normal everyday addition (decimal addition), except that it carries on a value of 2 instead of a value of 10.
For example: in decimal addition, if you add 8 + 2 you get ten, which you write as 10; in the sum this gives a digit 0 and a carry of 1. Something similar happens in binary addition when you add 1 and 1; the result is two (as always), but since two is written as 10 in binary, we get, after summing 1 + 1 in binary, a digit 0 and a carry of 1.

Therefore in binary:
0 + 0 = 0
0 + 1 = 1
1 + 0 = 1
1 + 1 = 10 (which is 0 carry 1)
# Halfadder
A half adder is a digital circuit that adds two single-bit binary numbers and produces a sum bit (s) and a carry bit (c) as output.
It is the simplest type of adder circuit and is used in combinational logic design and arithmetic logic units (ALUs) in microprocessors.
A half adder can be implemented using various logic gates, including:
One EX-OR gate for the sum output (s)
One AND gate for the carry output  (c)
Alternatively, a half adder can be constructed using NAND gates or NOR gates.
Half adder adds two single-bit binary numbers
Produces a sum bit (s) and a carry bit  (c) as output
No forwarding of carry addition; the carry output is immediate
Used in combinational logic design and arithmetic logic units (ALUs) in microprocessors
# Truthtable
![Screenshot 2024-09-19 121257](https://github.com/user-attachments/assets/2938dfc9-faaa-4964-8a7e-b31d4407c3f6)

![Screenshot 2024-09-23 224032](https://github.com/user-attachments/assets/a29a0b3a-69e5-4c5c-9d57-e879cafe8242)

The first digit, we can denote as A and the second digit we can denote as B, are added together and we can see the summation result and carry bit. In the first three row 0 + 0, 0 + 1 or 1+ 0 the addition is 0 or 1 but there is no carry bit, But in the last row we added 1 + 1  and it is produce a carry bit of 1 along with result 0.

So, if we see the operation of an adder circuit, we need only two inputs and it will produce two outputs, one is addition result, denoted as SUM and other one is CARRY OUT bit.

![Screenshot 2024-09-19 121324](https://github.com/user-attachments/assets/68394aac-80cb-4e0d-a820-161a9bbf7e9b)

# Half adder Implemented with two logic gates, XOR and AND gates
![Screenshot 2024-09-19 121338](https://github.com/user-attachments/assets/caa78955-e6b3-4141-94b9-100de681d91d)

# Construction of a halfadder circuit.
![Screenshot 2024-09-23 210408](https://github.com/user-attachments/assets/64aab246-d2b2-4295-9642-fff790c16bbe)

# This is a physical demonstration of a Half Adder
This is when both switches are on or when the binary adition is 1 + 1

![Screenshot 2024-09-23 215527](https://github.com/user-attachments/assets/cdc39413-8e33-4749-ac5a-0cb4440c109e)

# This is when the binary adittion 1 + 0 

![Screenshot 2024-09-23 220444](https://github.com/user-attachments/assets/b5399ccd-9b65-4051-a3d0-3bf9c5b31996)

# Primitive computer With A Half Adder

![image](https://github.com/user-attachments/assets/c73b0fb8-8a6b-4930-a595-63002209dee0)

References:

Binary Adittion. (2008, August ). Retrieved from https://web.math.princeton.edu/math_alive/1/Lab1/BinAdd.html

Gupta, S. (2018, June 25). Retrieved from Half Adder and its construction: https://circuitdigest.com/tutorial/half-adder-circuit-and-its-construction












