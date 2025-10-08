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

i) 
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii) 
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


**RTL realization**

i) <img width="742" height="462" alt="image" src="https://github.com/user-attachments/assets/3673eb7a-e583-4b51-ab23-fc9b4cccb645" />

ii) <img width="742" height="476" alt="image" src="https://github.com/user-attachments/assets/778e1b88-f7ac-4233-98f2-b4ee2124339b" />


**Output:**

**RTL**

i) <img width="1883" height="823" alt="image" src="https://github.com/user-attachments/assets/738e3a86-f403-4ebc-9850-4acfb7fa0e69" />

ii) <img width="1873" height="828" alt="image" src="https://github.com/user-attachments/assets/24db2d54-dc12-43ad-8941-13b86c9e2843" />


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

