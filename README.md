### NAME:DINESH KARTHIK R
### REG NO:24900716
### EXPERIMENT 4: IMPLEMENTATION OF  FULL ADDER AND SUBTRACTOR CIRCUIT

Implementation-of-Full-Adder-and-Full-subtractor-circuit

### AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

### FULL ADDER AND FULL SUBTRACTOR:

### FULL ADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

### FULL SUBTRACTOR:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

### TRUTH TABLE:
FULL ADDER

![image](https://github.com/user-attachments/assets/f8afc41a-66e1-4660-a7e1-4b28093ed2d5)

FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/a51d1be3-da7b-41e3-9888-2c8bbf222b32)

### PROCEDURE:
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram

### PROGRAM:
![Screenshot 2024-12-12 104500](https://github.com/user-attachments/assets/c33ba59e-dc84-4d69-a08d-85947b61b2c7)

### RTL:
FULL ADDER

![image](https://github.com/user-attachments/assets/4ae4e58f-7710-4b80-9bc5-08f4dc5afe6e)

FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/ff68b900-1e10-4d7a-a9ed-2000f141156c)

### TIMING DIAGRAM:
FULL ADDER

![image](https://github.com/user-attachments/assets/b192938b-00f0-4357-bc42-52d0863eac77)

FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/d392363a-6730-421f-a8f9-063246ff7bd2)

### RESULT:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



