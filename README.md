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

Developed by: S MANO SUSHMITHA

RegisterNumber:212224040187

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


**RTL realization**

![WhatsApp Image 2025-04-23 at 13 48 16_cca8264d](https://github.com/user-attachments/assets/3cf9a55f-5499-4f1e-ac6a-0235617f0914)


![WhatsApp Image 2025-04-23 at 13 48 16_8b4dd994](https://github.com/user-attachments/assets/3159561d-91e5-489b-b2ea-6cf472fa4b4f)



**Output:**

![WhatsApp Image 2025-04-23 at 13 48 16_6a88413f](https://github.com/user-attachments/assets/c12204d6-8119-4478-a7ef-a710a0a95fa9)


![WhatsApp Image 2025-04-23 at 13 48 16_968e9812](https://github.com/user-attachments/assets/3cde8e8e-bf78-4540-b032-ccf66d3e053e)



**TRUTH TABLE**

![WhatsApp Image 2025-04-23 at 13 48 16_4037ea59](https://github.com/user-attachments/assets/14cda37c-5cac-4318-a08d-dac135f54f32)


![WhatsApp Image 2025-04-23 at 13 48 16_9f32931d](https://github.com/user-attachments/assets/5b8b9e9f-8937-4733-96aa-6692e8c52c27)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

