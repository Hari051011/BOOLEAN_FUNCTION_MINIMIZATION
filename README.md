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

Developed by: HARI KRISHNAN S

RegisterNumber: 24006616

```
module experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization**

![image](https://github.com/user-attachments/assets/89433ae2-7317-4202-b35b-90bfb7d264f1)


**TRUTH TABLE**

![image](https://github.com/user-attachments/assets/002ea23e-44a3-48ab-914b-dca44989e5e0)

![image](https://github.com/user-attachments/assets/b9f1929b-1fef-4234-885b-ee6f39049e5c)



**Output:**

**RTL**

![image](https://github.com/user-attachments/assets/77fc6273-d80f-4f03-b904-ffcafc9b0ecb)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

