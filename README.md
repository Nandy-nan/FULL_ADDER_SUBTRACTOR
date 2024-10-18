# FULL_ADDER_SUBTRACTOR

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
**full adder**
![image](https://github.com/user-attachments/assets/a56142a2-9722-48f2-adcb-ff4cdb95b98f)

**full subtarctor**
![image](https://github.com/user-attachments/assets/c8bc3cbb-9eeb-40d3-ae5a-d0a058320640)




**Procedure**



Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: NANDHANA.R RegisterNumber:212223040124
*/
**full adder**

![WhatsApp Image 2024-10-18 at 13 41 41_45e3e192](https://github.com/user-attachments/assets/ea51cf29-e170-47bb-8e94-9ac0ae83ade4)

**full subtractor**
![image](https://github.com/user-attachments/assets/901c157e-fcd3-4783-b4fa-a0ee22c87e0d)




**RTL Schematic**
**full adder**
![image](https://github.com/user-attachments/assets/2aa79f04-e25c-4c22-9580-af0a43bd8e1f)


**full subtractor**
![image](https://github.com/user-attachments/assets/0b2d172f-819b-4c92-b26e-7c6fe760f327)



**Output Timing Waveform**
**full adder**
![image](https://github.com/user-attachments/assets/461a9697-da00-46f3-989a-2ea60f416c81)

**full subtractor**
![image](https://github.com/user-attachments/assets/2c8b3a88-cf5b-4901-9a4c-64e6e4737792)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



