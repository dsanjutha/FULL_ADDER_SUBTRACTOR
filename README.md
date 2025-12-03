
Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
<img width="1919" height="1079" alt="digital ex4,fa1,program" src="https://github.com/user-attachments/assets/8c6f1eae-1dc7-4259-bbc3-3afa8616ebec" />
<img width="1919" height="1079" alt="digital ex4,fs2,program" src="https://github.com/user-attachments/assets/bb45bca1-1098-447c-8e6d-f695ace05bac" />
 Developed by:d.sanjutha RegisterNumber:25015927*/

 
**RTL realization output:**

<img width="1917" height="1059" alt="digital ex4,fa1,output" src="https://github.com/user-attachments/assets/3c6543e4-6e17-468b-8b4f-393ed8a84f94" />
<img width="1919" height="1079" alt="digital ex4,fs2,output" src="https://github.com/user-attachments/assets/fa14673b-0f60-49a0-9c32-7e63be1a6bca" />
**Output Timing Waveform:**
<img width="1919" height="1079" alt="digital ex4,fa1,wave" src="https://github.com/user-attachments/assets/d498baab-ef0c-47b8-bf16-ba892f0f8acd" />
<img width="1919" height="1079" alt="digital ex4,fs2,wave" src="https://github.com/user-attachments/assets/35e0588e-0910-4d53-8a85-d4d89256c3fe" />

**Result:**
Thus the full Adder and Full Substractor circuits are designed and the truth tables is verifield using Quartus software.
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



