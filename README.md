### NATHER NABEEL S.A.C
### REG NO : 24900919
# FULL ADDER SUBTRACTOR

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

FULL ADDER :

![image](https://github.com/user-attachments/assets/abc113e3-2e6a-466f-839a-472dd3cdb69b)

FULL SUBTRACTOR :

![image](https://github.com/user-attachments/assets/4bbf1d4c-ef91-4d65-a51c-6c287a240575)

**Procedure**

Write the detailed procedure here

**Program:**

FULL ADDER :

![Screenshot 2024-12-21 210904](https://github.com/user-attachments/assets/a2aa42a8-2954-4bd4-8abe-eea57866ad4c)

FULL SUBTRACTOR :

![Screenshot 2024-12-21 214528](https://github.com/user-attachments/assets/9b86c759-fbff-4bb6-a01a-a5acba83294c)

**RTL Schematic**

FULL ADDER :

![Screenshot 2024-12-21 210444](https://github.com/user-attachments/assets/2ef79360-fe7d-4cbd-af0f-abcc9f5d2dc7)

FULL SUBTRACTOR :

![Screenshot 2024-12-21 214541](https://github.com/user-attachments/assets/140549c0-bbdf-4917-bc87-e171b6475bbb)

**Output Timing Waveform**

FULL ADDER :

![Screenshot 2024-12-21 210817](https://github.com/user-attachments/assets/0118492c-147c-4ca2-a1f2-8729b405f9ab)

FULL SUBTRACTOR :

![Screenshot 2024-12-21 214938](https://github.com/user-attachments/assets/8f3f5f92-1ba2-494c-b333-bfa0e30b36ad)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



