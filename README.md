# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: v.sanjay
RegisterNumber:  23012749

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: SANJAY M
RegisterNumber:23013084

module ex_02(a,b,c,d,f1);
input a,b,c,d;
output f1;
wire x1,x2,x3,x4,x5;
assign x1=(~a)&(~b)&(~c)&(~d);
assign x2=(a)&(~c)&(~d);
assign x3=(~b)&(c)&(~d);
assign x4=(~a)&(b)&(c)&(d);
assign x5=(b)&(~c)&(d);
assign f1=x1|x2|x3|x4|x5;
endmodule
*/
## RTL realization
![2](https://github.com/sanjayy2431/Experiment--02-Implementation-of-combinational-logic-/assets/149365143/8b4519c8-fb3c-4142-a38d-a0efd88e7e34)
## Truth Table
![2](https://github.com/sanjayy2431/Experiment--02-Implementation-of-combinational-logic-/assets/149365143/f747f979-5945-439e-a9d2-6afe7e73fb8e)
## Timing Diagram
![2](https://github.com/sanjayy2431/Experiment--02-Implementation-of-combinational-logic-/assets/149365143/43a78e41-a885-4092-93bc-308ddac82bb2)





## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
