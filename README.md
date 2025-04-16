# HALF_ADDER_SUBTRACTOR
###name:VINOTH K R
###reg.no:212224050060
Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB
![Screenshot 2025-04-16 081820](https://github.com/user-attachments/assets/110919d6-01dc-45b0-b961-2dabc217984b)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B
![32257aa77b6143258cbb920f2d48d539 1](https://github.com/user-attachments/assets/6787126a-054b-4fb1-bf85-bcbfbf4ac658)


Figure -02 HALF Subtractor

**Truthtable**
half adder:
![WhatsApp Image 2025-04-16 at 08 47 09_de01b381](https://github.com/user-attachments/assets/1cb17b19-0c8a-4de7-8fda-e8e09c5fdf79)

half subtract:
![WhatsApp Image 2025-04-16 at 08 47 09_003f75b2](https://github.com/user-attachments/assets/f5875946-74f3-42b4-95e4-a6dbcaad2deb)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
half adder:
![4811731a788b44639cee2bdc3fe461f3 1](https://github.com/user-attachments/assets/f82eba59-78cd-4191-9df9-386b05f4b805)
half subtract:
![e0f5072e39bf4ed38fac4920d70e996b 1](https://github.com/user-attachments/assets/bfde83ef-9bdd-452d-aaaf-fec44165c104)


**RTL Schematic**

**Output/TIMING Waveform**
half adder:
![da3ba99035654034abb6e2623e089c05 1](https://github.com/user-attachments/assets/264fef9e-5f06-4a42-a1a6-4a0fbf5993cc)
half subtract:
![f9af1707cc444818a235be77bfb8e97f 1](https://github.com/user-attachments/assets/4327de0a-a17f-4d55-b002-0862a5776438)


**Result:**
 The code is excecuted successfully.
