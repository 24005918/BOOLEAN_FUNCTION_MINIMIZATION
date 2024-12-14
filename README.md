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

![{C51966D3-5999-4F76-86A8-66ABF54F159A}](https://github.com/user-attachments/assets/40779e5e-0ee0-4ac7-a567-efa9a91ba74d)

![{67173E19-8F7C-4CE3-871D-8F5B8B1FFC5A}](https://github.com/user-attachments/assets/e8d53050-3042-4a72-9cdf-ecf84545daef)

**RTL Timing Diagram**
![{D15B525D-4C36-41B9-8B75-4E47E5F46FE9}](https://github.com/user-attachments/assets/339929cb-6907-49a5-baf1-f5dbc897def4)
![{D07E97F0-30AC-4FA2-BF9B-C7B8227D671C}](https://github.com/user-attachments/assets/85cdd59f-7b41-4e0b-b272-deb9fbc30a54)

**Result:**
 Thus the given logic functions are implemented using and their operations are verified
 using Verilog programming.
