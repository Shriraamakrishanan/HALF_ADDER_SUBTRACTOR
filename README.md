### NAME : SHRI RAAMA KRISHANAN J ###
### REG NO : 24900816 ###
### EXP NO 3 :HALF ADDER AND HALF SUBTRACTOR ###

### AIM: ###

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENT REQUIRED: ###

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### HALF ADDER: ###

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

### HALF SUBRACTOR: ###

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


### PROCEDURE: ###

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM: ###

![Screenshot 2024-11-21 115628](https://github.com/user-attachments/assets/d9053158-9ec2-46b2-8173-72f0452a7730)


### TRUTHTABLE: ###
### HALF ADDER: ###

![half add](https://github.com/user-attachments/assets/13c0f4d7-f337-42ea-b564-54b81bc49095)


### HALF SUBRACTOR: ###

![half sub](https://github.com/user-attachments/assets/5942a20b-08af-4abf-a501-37966dbb247d)

### RTL REALIZATION OUTPUT: ###

![Screenshot 2024-11-21 115650](https://github.com/user-attachments/assets/d0e14909-6d66-4fb7-9eb2-8d87c4a0d1ac)


### TIMING DIAGRAM: ###

![Screenshot 2024-11-26 182140](https://github.com/user-attachments/assets/9e4810a7-de9f-4df0-82f9-b3ecc697b7d8)


### RESULT: ###
Designed and verified the half adder & half subractor circuit and  its truth table in quartus ll using Verilog programming successfully.

