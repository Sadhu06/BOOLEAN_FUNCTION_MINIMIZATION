# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![d2logic](https://github.com/user-attachments/assets/87a80a6f-0efe-43f7-aa32-efa69bd902e9)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Sadhana S RegisterNumber: 212224230234
```
module exp2a(a,b,c,d,F1);
input a,b,c,d;
output F1;
assign F1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule 

module exp2b(w,x,y,z,F2);
input w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule 
```
**RTL realization**

**Output:**
Exp2a
![deexp2a](https://github.com/user-attachments/assets/701aa213-b477-4ca9-9447-eacc915a8a36)
Exp2b
![deexp2b](https://github.com/user-attachments/assets/fee32507-ce7a-436d-969b-9b6f857c8e33)




**RTL**
Exp2a
![exp2a](https://github.com/user-attachments/assets/0a69f610-73e6-4ddb-966c-82599658b65c)
Exp2b
![exp2a](https://github.com/user-attachments/assets/0b3eb9e5-9b86-492b-ab87-c25d503f9790)



**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

