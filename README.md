# Exp-03 Implementation of Half Adder and Full Adder circuit..

### Project By: MASINA SREE KARSH
###   Register No:23005860


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

#### Figure -01 HALF ADDER 

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)


#### Figure -02 FULL ADDER

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

## Procedure:

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
# Half Adder Circuit:-

![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/22925cc5-3594-4624-a94e-a1d0a9e550e8)


# Full Adder Circuit:-

![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/26cc1c46-2eea-4984-860c-1112a233aa11)


*/
### Truthtable:-
   Half Adder Circuit:

   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/e10af706-82c8-4d25-a306-a0a07c6cabe9)

   Full Adder Circuit:-
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/af2b52f4-f405-40b8-99b3-edc56a770c5c)

*/
### RTL realization:
   Half Adder Circuit:
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/f3ae3d80-95e6-4d4f-b68a-6bf780821a09)

   Full Adder Circuit:-
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/bd185f3b-fe74-4da2-94d7-7e06a89c399c)

### Output Waveform $ Timing Diagram:-
   Half Adder Circuit:-
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/4f7ba4b5-4cb6-47fc-872d-b94402b9dcaa)
   
   Full Adder Circuit:-
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/8a8e06ed-e158-444a-9547-69b548c63015)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
