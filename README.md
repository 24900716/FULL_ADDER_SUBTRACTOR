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
![Screenshot (32)](https://github.com/user-attachments/assets/45a1254e-ea7a-4c2b-81fb-af79048e84b4)
![Screenshot (34)](https://github.com/user-attachments/assets/a95e88de-b756-4694-ac91-e7be69306887)

### PROCEDURE:
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram

### PROGRAM:
![Screenshot 2024-12-12 104500](https://github.com/user-attachments/assets/c33ba59e-dc84-4d69-a08d-85947b61b2c7)

### RTL:
![Screenshot (30)](https://github.com/user-attachments/assets/0c25791a-da25-4a94-939e-aa028105d98c)

### TIMING DIAGRAM:
![Screenshot (37)](https://github.com/user-attachments/assets/2c40513e-a854-4049-a40f-91a631e7a436)

### RESULT:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



