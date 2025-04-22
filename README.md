# BOOLEAN_FUNCTION_MINIMIZATION
Developed by : SHANJAY KUMAR.S

Register No : 212224230245

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

 module funct1(a,b,c,d,f1);
 
 input a,b,c,d;
 
 output f1;
 
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));



 module funct2(w,x,y,z,f2);
 
 input w,x,y,z;
 
 output f2;
 
 assign f2=((~y&z)|(w&y)|(x&y));
 
 endmodule


**RTL realization**

**Output:**
![image](https://github.com/user-attachments/assets/02b66bde-cc08-49ea-86db-e9f47949f4ae)

![image](https://github.com/user-attachments/assets/bf2055d6-0be5-4c75-8789-5b1e7245b735)



**RTL**

**Timing Diagram**
![image](https://github.com/user-attachments/assets/ffc52852-52fa-469d-8e9f-decb3236da75)
![image](https://github.com/user-attachments/assets/90ad2a72-ac58-4f51-a93a-c586b76dce16)



**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


