# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: V MYTHILI


RegisterNumber: 212223040123*/

**CODE:**

**HALF ADDER:**



<img width="613" alt="de ex 3 1" src="https://github.com/Mythili7339267708/HALF_ADDER_SUBTRACTOR/assets/144260246/74ef746d-bcc4-4a3a-b05c-bab1f3dfba11">



**HALF SUBTRACTOR:**



<img width="610" alt="de ex3 2" src="https://github.com/Mythili7339267708/HALF_ADDER_SUBTRACTOR/assets/144260246/8f4c3e34-6dae-4edc-afbb-6b9700b23f4f">



**RTL Schematic**



**HALF ADDER:**

<img width="599" alt="de ex 3 3" src="https://github.com/Mythili7339267708/HALF_ADDER_SUBTRACTOR/assets/144260246/8fd902ef-b38e-42f0-8c8a-ae9f253a53cb">

**HALF SUBTRACTOR:**


<img width="581" alt="de ex 3 4" src="https://github.com/Mythili7339267708/HALF_ADDER_SUBTRACTOR/assets/144260246/86355e07-7243-4ca1-b814-7d81d2414b30">


**Output/TIMING Waveform**



**HALF ADDER:**


<img width="614" alt="de ex3 5" src="https://github.com/Mythili7339267708/HALF_ADDER_SUBTRACTOR/assets/144260246/a9c075c5-934c-4a05-94a8-60b1308c4816">




**HALF SUBTRACTOR:**



<img width="610" alt="de ex3 6" src="https://github.com/Mythili7339267708/HALF_ADDER_SUBTRACTOR/assets/144260246/010c85e8-d477-457b-a682-e407cfe9b1d6">


**Result:**



Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
