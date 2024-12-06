# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 module Logic(a,b,c,d,f1); input a,b,c,d; output f1; assign f1=((~b & ~d)|(~a &
 b & d)|(a & b & ~c)); endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:SANTHOSH V
RegisterNumber:24005918


**RTL realization**
![{F94FEB7C-C18A-48B6-AAC3-21E543FDE07D}](https://github.com/user-attachments/assets/227cd52a-41c7-4d76-85cf-92e06dd102a7)

**Output:**
![{302C83AA-3321-4357-AE59-AC0B794A14CC}](https://github.com/user-attachments/assets/ef1e18b4-3073-4167-aaa2-dd7b8ef453f6)

**RTL**

**Timing Diagram**

**Result:**
 Thus the given logic functions are implemented using and their operations are verified
 using Verilog programming.
