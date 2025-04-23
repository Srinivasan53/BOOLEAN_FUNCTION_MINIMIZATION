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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
Developed by:Srinivasan S
RegisterNumber: 21224220105
```

module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module exp22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/adcf2b24-45b2-475d-85df-5656823fafff)

![image](https://github.com/user-attachments/assets/05a0cf6e-4920-414d-85ed-32a324d1091d)


**Timing Diagram**
![image](https://github.com/user-attachments/assets/9f6324eb-bb6d-4c9c-95a5-3b9383302c32)

![image](https://github.com/user-attachments/assets/29cba165-181a-4b35-8739-71e942cf85f2)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

