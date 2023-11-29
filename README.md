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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: ARULARSI.U
RegisterNumber: 23013049 
*/
Logic symbol & Truthtable
RTL realization

### Output:
![CODE FULLADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/00572614-c0cb-4172-befa-b7262dfc3c05)
![WAVEFORM FULLADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/9b341943-c024-4772-a2be-c3f92616683a)
![CODE HALF ADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/29210648-affd-4225-9299-650e10e9306c)
![WAVEFORM HALFADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/5e14ac86-9fd8-46a0-baa8-f25ecb1561d4)



### RTL
![LOGIC GATE FULLADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/d5a81e72-8d5b-4e6b-adef-5f1edcf2ad9d)
![LOGIC GATE HALFADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/d44339b5-4843-4071-b502-5bf6685beee9)


### TIMING DIAGRAM
![TIME LINE DIAGRAM FULLADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/331f6da8-a28e-4639-8d1f-0501eac0b905)
![TIME LINE DIAGRAM HALF ADDER](https://github.com/Arularasi-17/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147410018/c5848930-3496-4f83-987c-38a06890ac7a)



### TRUTH TABLE 

### Result:
