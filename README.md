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
Full adder 
 ![image](https://github.com/user-attachments/assets/2341ea64-5e8d-426c-9e0b-b18496560b12)

Full subractor
![image](https://github.com/user-attachments/assets/9fd6d5c7-01a6-4af5-b1b8-aa95a425f230)

**Procedure**

1.Type the program in Quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram.


**Program:**
 Full adder
 ![image](https://github.com/user-attachments/assets/a7470cd3-ac0e-4333-af3d-cee3b0f05e68)

 Full subtractor
 ![image](https://github.com/user-attachments/assets/5d78a55b-80d6-45de-af6c-053b09f0a273)


Developed by: M RESHIKA RegisterNumber: 24011491

**RTL**
![image](https://github.com/user-attachments/assets/f6475ed7-aa49-4756-bd6d-95d27da0b698)
![image](https://github.com/user-attachments/assets/b19d4a13-73b2-41c8-a878-36cf1312ab45)

**Output**
![image](https://github.com/user-attachments/assets/56551d20-6b81-44c7-997a-865e91c70619)
![image](https://github.com/user-attachments/assets/614377ba-d5dd-488d-b98e-c3173006581f)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



