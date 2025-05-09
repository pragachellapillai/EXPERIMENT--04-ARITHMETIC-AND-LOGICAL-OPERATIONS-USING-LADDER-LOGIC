# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME:PRAGAHARSHITHA NC
# REGISTER NUMBER:212222110033
# DEPARTMENT:CSE(IOT)
# YEAR:3rd
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots
Addition
![image](https://github.com/user-attachments/assets/391eaa1c-a848-4452-ac63-11702e1bb4ef)

![image](https://github.com/user-attachments/assets/f6e02952-f721-4798-851f-44f8bd59ae54)

![image](https://github.com/user-attachments/assets/b9ba6c07-a516-49b7-a163-4e4e865a1822)

![image](https://github.com/user-attachments/assets/53ee48b4-cfb4-4c1d-aeb1-80dc95c97b63)

Subtraction
![image](https://github.com/user-attachments/assets/81384209-473c-44db-b6a2-1fb8b2ec8f97)

![image](https://github.com/user-attachments/assets/452cadad-0775-4c2f-9cb1-6f863f6ae2da)

![image](https://github.com/user-attachments/assets/1813fe6b-8910-4fea-a4d9-3f5b711865d6)

![image](https://github.com/user-attachments/assets/89bffed5-db27-4e71-9edc-d71fc0ebdc2b)

Multiplication

![image](https://github.com/user-attachments/assets/41150e66-8b15-489e-a608-36ed82e7aa70)

![image](https://github.com/user-attachments/assets/57eabb16-8924-4086-a667-c253845e17c2)

![image](https://github.com/user-attachments/assets/d9232019-c19a-44d9-90d6-3d7b1f06885a)

![image](https://github.com/user-attachments/assets/08063718-f2ba-4a3b-b287-a1fa9ff1814a)

Division 

![image](https://github.com/user-attachments/assets/9e4b00ab-bdcd-4de3-b6f9-fbb7751b51ef)

![image](https://github.com/user-attachments/assets/a5caa770-f98c-41a8-83f5-231b299560d7)

![image](https://github.com/user-attachments/assets/3cd9d0c4-a418-405c-811d-6472801584ce)

![image](https://github.com/user-attachments/assets/89c482c8-b86a-40b9-b7f3-a51f794285b7)

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
