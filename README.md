# EXP-3-FULL-ADDER-AND-SUBTRACTOR
AIM:
To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime

Full Adder and Full Subtractor

Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.
Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin
Carry = AB + ACin + BCin

 <img width="814" height="413" alt="image" src="https://github.com/user-attachments/assets/af0bd411-7a2e-4085-b304-76dc4fc4c054" />

Figure -1 FULL ADDER

Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

 <img width="940" height="407" alt="image" src="https://github.com/user-attachments/assets/cf461f16-e3be-4577-9b6b-2c915978d8b4" />

Diff = A ⊕ B ⊕ Bin
Borrow out = A'Bin + A'B + BBin

Result: Thus, the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
