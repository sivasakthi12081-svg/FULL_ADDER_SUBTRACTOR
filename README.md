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
<img width="716" height="622" alt="Screenshot 2025-12-09 225459" src="https://github.com/user-attachments/assets/91d0d64f-fd17-4016-baad-3d5a5df8744c" />

<img width="790" height="620" alt="Screenshot 2025-12-09 225625" src="https://github.com/user-attachments/assets/3a1b590b-eae1-4d1e-84be-20baf7911efb" />

**Procedure**

Step-1:Write the Verilog code for Full Adder and Full Subtractor using the logical expressions and save the files in the Quartus project.

Step-2:Compile the project in Quartus to check for errors and ensure the design is successfully synthesized.

Step-3:Run functional simulation using the Quartus/ModelSim simulator by applying all input combinations of A, B, and Cin/Bin.

Step-4:Observe and verify the outputs and compare them with the theoretical truth tables of the Full Adder and Full Subtractor.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Sivasakthi S RegisterNumber:25017123
*/
<img width="539" height="282" alt="EX4 4 4" src="https://github.com/user-attachments/assets/be1a8e63-b75b-4864-971b-2b092186c424" />

**RTL Schematic**
<img width="952" height="728" alt="EX4" src="https://github.com/user-attachments/assets/803eee3f-c9aa-45e9-a50a-6b5b8d2f7c0b" />

**Output Timing Waveform**
<img width="1919" height="427" alt="Ex4 4" src="https://github.com/user-attachments/assets/abb7f665-feee-48bb-92f8-786e123ab3ee" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



