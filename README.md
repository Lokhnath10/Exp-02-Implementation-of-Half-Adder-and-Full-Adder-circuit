
### NAME: LOKHNATH J
###   Register No:23004865
# Experiment-03 Implementation of Half Adder and Full Adder circuit
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

####  HALF ADDER 
![image](https://github.com/Lokhnath10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138969918/06eeef19-8835-4b15-bc5b-88dbaeaae48d)
#### FULL ADDER
![image](https://github.com/Lokhnath10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138969918/5025cdec-3bd7-4125-868b-a49d235fae68)
## Procedure:

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
# Half Adder :-
```
module exp3(a,b,sum,carry);
input a,b;
output sum,carry;
xor(sum,a,b);
and(carry,a,b);
endmodule
```


# Full Adder Circuit:-

```
module exp3(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
nor(sum,a,b,c);
assign carry=a&b | b&c | a&c;
endmodule
```


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

### Output Waveform :
   Half Adder Circuit:-
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/4f7ba4b5-4cb6-47fc-872d-b94402b9dcaa)
   
   Full Adder Circuit:-
   
   ![image](https://github.com/Shilo-05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139841664/8a8e06ed-e158-444a-9547-69b548c63015)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
