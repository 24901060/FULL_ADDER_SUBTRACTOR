# EXP4:FULL ADDER AND SUBTRACTOR
##NAME:PRAVEEN.S
##REGISTRATION NO:24901060

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**
![image](https://github.com/user-attachments/assets/a37cf26e-aa3b-4c09-ae4a-cd5c29a1f241)
![image](https://github.com/user-attachments/assets/31abc1c6-fec1-49a3-bcba-73393f0337c3)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![image](https://github.com/user-attachments/assets/53d472b3-a36e-495d-9afc-454f6c925d33)
![image](https://github.com/user-attachments/assets/7fc2d178-3d46-40fd-a12f-eb63ad9a9df6)

**Output Timing Waveform**
![image](https://github.com/user-attachments/assets/c56f73bb-3c45-4f61-9e9d-632ea8bd5f7b)
![image](https://github.com/user-attachments/assets/6248c6b8-6e54-41bc-a9d9-d3d901215cc9)

**Result:**
Hence Proved

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



