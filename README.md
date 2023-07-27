## PROJECT BY:EZHIL NEVEDHA.K                                             
## REG-NO:23007496
## Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
 Hardware – PCs, Cyclone II , USB flasher
 Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor & Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.
## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
*/
## Half Subtractor:
![Screenshot 2023-07-27 081445](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/4cfbe99b-d9e6-4f08-849e-7983978b282d)
## Full Subtractor:
![Screenshot 2023-07-27 090032](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/634adda9-0524-4778-a543-35a98845d19a)

## Truthtable
## Half Subtractor:

![Screenshot 2023-07-27 085542](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/19d97bfc-f7cb-498b-bf78-576950816e02)
## Full Subtractor:
![Screenshot 2023-07-27 091307](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/ce030bcd-5ee3-42f3-913a-66b2ee1dc66d)


##  RTL realization
## Half Subtractor:
![Screenshot 2023-07-27 082416](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/bb29375c-9c29-4ddb-8299-19cc83d00026)

## Full Subtractor:
![Screenshot 2023-07-27 090146](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/8b233872-b1d6-4817-9488-4bffe877a873)

## Timing diagram 
## Half Subtractor:
![Screenshot 2023-07-27 085322](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/3cf881ff-bfd5-4792-942d-9be10d78ccad)

## Full Subtractor:
![Screenshot 2023-07-27 091019](https://github.com/ezhilnevedha/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/140057992/3fc866e8-7675-4523-bf14-ae72dace15cf)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
