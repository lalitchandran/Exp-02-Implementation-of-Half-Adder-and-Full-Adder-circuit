# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
Half Adder
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/295d73f2-9c88-4a1a-b372-325580091d59)

Full Adder
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/ea0d403b-f0fd-45c8-94a3-0d9e5865a7ad)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: S LALIT CHANDRAN
RegisterNumber: 23004048
*/
RTL realization
HALF ADDER
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/36cb1da7-1efc-4fd3-bed8-e45aa1e548e9)

FULL ADDER
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/bf2cb324-f63e-4500-b2ab-a64109c7bd9b)

### Output:
### TIMING DIAGRAM
HALF ADDER
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/00fd326c-3382-4e07-ad37-b9e71adbf111)

FULL ADDER
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/bf6bd1b8-ce51-4e21-acb8-debe288e9e54)

### TRUTH TABLE 
HALF ADDER
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/39de11fa-5408-42c7-98b4-e4dd5fd22ccf)

FULL ADDER
![image](https://github.com/lalitchandran/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/137707725/2132a958-f031-4a0c-9f02-239fae9e7b5a)

### Result:
