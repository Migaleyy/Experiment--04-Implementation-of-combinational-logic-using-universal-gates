# Experiment--04-Implementation-of-combinational-logic-using-universal-gates
Implementation of combinational logic using universal-gates
 
## AIM:
To implement the given logic function using NAND and NOR gates and to verify its operation in Quartus using Verilog programming.

F=((C'.B.A)'(D'.C.A)'(C.B'.A)')' using NAND gate
F=(((C.B'.A)+(D.C'.A)+(C.B'.A))')' using NOR gate
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
Logic gates are electronic circuits which perform logical functions on one or more inputs to produce one output. 

## Using NAND gates
NAND gate is actually a combination of two logic gates i.e. AND gate followed by NOT gate. So its output is complement of the output of an AND gate.This gate can have minimum two inputs, output is always one. By using only NAND gates, we can realize all logic functions: AND, OR, NOT, X-OR, X-NOR, NOR. So this gate is also called as universal gate. First note that the entire expression is inverted and we have three terms ANDed. This means that we must use a 3-input NAND gate. Each of the three terms is, itself, a NAND expression. Finally, negated single terms can be generates with a 2-input NAND gate acting as an inverted.

F=((C'.B.A)'(D'.C.A)'(C.B'.A)')'

## Logic Diagram

Using NOR gates
NOR gate is actually a combination of two logic gates: OR gate followed by NOT gate. So its output is complement of the output of an OR gate. This gate can have minimum two inputs, output is always one. By using only NOR gates, we can realize all logic functions: AND, OR, NOT, Ex-OR, Ex-NOR, NAND. So this gate is also called universal gate. Designing a circuit with NOR gates only uses the same basic techniques as designing a circuit with NAND gates; that is, the application of deMorgan’s theorem. The only difference between NOR gate design and NAND gate design is that the former must eliminate product terms and the later must eliminate sum terms.

F=(((C.B'.A)+(D.C'.A)+(C.B'.A))')'

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function using NAND and NOR gates and to verify its operations in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
## RTL realization

## Output:
NAND

## RTL

![HALF RTL](https://user-images.githubusercontent.com/118262199/211456274-2d1f1fdc-126c-4506-8034-b6b8dee60881.jpg)

## Timing Diagram

![TIME](https://user-images.githubusercontent.com/118262199/211456308-a23b077d-9f24-43f6-a4f8-8845746160d7.jpg)

## Truth Table

![TRUTH TABLE](https://user-images.githubusercontent.com/118262199/211456362-46449b09-a3e4-4c56-b665-7abc89eb0bcc.jpg)

NOR

## RTL

![rtl](https://user-images.githubusercontent.com/118262199/211456474-c24e99bc-af4e-4d68-a25a-5327bb8a745f.jpg)

## Timing Diagram

![td](https://user-images.githubusercontent.com/118262199/211456500-114c627b-567a-482d-b8b7-8ac1c1585400.jpg)

## Truth Table

![tt](https://user-images.githubusercontent.com/118262199/211456538-81667636-b0c1-415f-b038-8953f4b2119c.jpg)

## Result:
Thus the given logic functions are implemented using NAND and NOR gates and their operations are verified using Verilog programming.
