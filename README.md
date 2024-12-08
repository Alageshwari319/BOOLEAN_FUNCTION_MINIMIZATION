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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
```

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by:Alageshwari.V  RegisterNumber:24900791


**RTL realization**

![image](https://github.com/user-attachments/assets/3bfa754f-31a1-4431-9df6-124870bf2a74)

![image](https://github.com/user-attachments/assets/87df2b54-53a2-4ea6-95a1-49479c5b1a75)

**K map**

![image](https://github.com/user-attachments/assets/94bed551-ef16-4b51-b756-7f339ad5ff74)

![image](https://github.com/user-attachments/assets/d0624c87-acbb-4526-a19d-23344e3dfdc3)


**Output:**

![image](https://github.com/user-attachments/assets/767deee8-0820-4e0f-9592-491ebff29798)

![image](https://github.com/user-attachments/assets/4b863c7d-b641-4679-911b-0580ba795c16)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

