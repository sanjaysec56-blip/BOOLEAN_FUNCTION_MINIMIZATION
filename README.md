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


**Program:**EXPT: 2
module all_gates (
    input  A, B,
    output AND_out,
    output OR_out,
    output NOT_out,
    output NAND_out,
    output NOR_out,
    output XOR_out,
    output XNOR_out
);
    assign AND_out  = A & B;
    assign OR_out   = A | B;
    assign NOT_out  = ~A;       // NOT is applied to A
    assign NAND_out = ~(A & B);
    assign NOR_out  = ~(A | B);
    assign XOR_out  = A ^ B;
    assign XNOR_out = ~(A ^ B);
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**

**Output:**<img width="743" height="569" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/4e0a06e1-3c1e-4b21-8529-8245c87d075f" />


**RTL**

**Timing Diagram**<img width="923" height="389" alt="image" src="https://github.com/user-attachments/assets/bafc482d-f7f5-4dcc-9cd5-36b91e5f991a" />
<img width="847" height="448" alt="image" src="https://github.com/user-attachments/assets/26773fc9-7079-4c03-be60-2cd9a3565188" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

