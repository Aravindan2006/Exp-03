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
### CODE :
### HALF ADDER : 
![Screenshot 2023-12-26 225405](https://github.com/Aravindan2006/Exp-03/assets/151760062/1062bbba-e0d2-4394-a259-6f982d346c53)

### FULL ADDER :
![image](https://github.com/Aravindan2006/Exp-03/assets/151760062/0eff2be1-2290-44ff-8cc6-f9ceff4690e4)
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Aravindan D
RegisterNumber: 23013092

### RTL
![Screenshot 2023-12-26 225918](https://github.com/Aravindan2006/Exp-03/assets/151760062/90dc5639-c226-41c2-98eb-79681269b468)
![Screenshot 2023-12-26 225950](https://github.com/Aravindan2006/Exp-03/assets/151760062/955dc32a-570e-48ae-90f0-9e730e68ccc0)

### TIMING DIAGRAM
![Screenshot 2023-12-26 230028](https://github.com/Aravindan2006/Exp-03/assets/151760062/8882c6de-e72f-4784-852b-2fdf94a93d5b)

![Screenshot 2023-12-26 230059](https://github.com/Aravindan2006/Exp-03/assets/151760062/f426eed3-21d2-4feb-b8bb-a3ca42053959)


### TRUTH TABLE 
![Screenshot 2023-12-26 230125](https://github.com/Aravindan2006/Exp-03/assets/151760062/ffd804b8-e45d-4fc2-92c4-e62d6fdc8886)
![Screenshot 2023-12-26 230200](https://github.com/Aravindan2006/Exp-03/assets/151760062/3592b76f-af59-49cc-98d7-97684df1481f)



### Result:
Thus the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
