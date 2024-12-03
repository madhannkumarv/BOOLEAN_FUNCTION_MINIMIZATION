# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-12-03 at 10 23 14_8e2bcd8a](https://github.com/user-attachments/assets/cf2ef5e2-3627-4235-b31f-e67bf282120a)

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/24010027

**RTL realization** **Output:**
![screenshot1](https://github.com/user-attachments/assets/15901cb1-b489-48fb-8fcb-03f078320465)

**Timing Diagram**
![screenshot 3](https://github.com/user-attachments/assets/45dfacdb-b8e0-413b-b570-a5a9f321c82c)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

