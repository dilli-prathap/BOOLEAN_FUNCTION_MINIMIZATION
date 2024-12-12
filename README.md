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

![Screenshot 2024-12-12 152517](https://github.com/user-attachments/assets/68d8bd1d-ef6d-43bf-b03d-3219dc9b453b)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
 module function1(a,b,c,d,f1); input a,b,c,d; output f1; assign f1=((~b & ~d)|(~a & b & d)|
 (a & b & ~c)); endmodule
```

**RTL realization**

![Screenshot 2024-12-12 153113](https://github.com/user-attachments/assets/91a147ac-c472-430e-adde-9c9ee90c6ff9)



**Output:**
![Screenshot 2024-12-12 152730](https://github.com/user-attachments/assets/f19d6824-1661-443e-95fa-03f761de0d4f)

**RTL**

**Timing Diagram**

![Screenshot 2024-12-12 152928](https://github.com/user-attachments/assets/1c3f7c91-359c-4420-a649-ebf8d9b746b0)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

