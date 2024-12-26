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
module ha_dataflow(a, b, s, ca); 
    input a; 
    input b; 
    output s; 
    output ca; 
  assign#2 s=a^b; 
  assign#2 ca=a&b;
  endmodule

Developed by:Sriranjani.M
RegisterNumber:24900016

**RTL realization**
<img width="673" alt="ex 2" src="https://github.com/user-attachments/assets/d532bd93-b0a5-4b35-9900-14fa4adcd809" />


**Timing Diagram**
<img width="632" alt="ex 2 timing diagram" src="https://github.com/user-attachments/assets/fd06f508-8b54-4062-8ac8-b27d21f7f9af" />

**Output:**
Hence we have implemented the given logic function and verified its operation in Quartus using Verilog programming.


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

