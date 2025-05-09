# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: PRAGAHARSHITHA NC
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
Addition

![Screenshot 2025-05-09 155434](https://github.com/user-attachments/assets/daee3a9d-f739-44c7-9598-89489ca2df0f)


![Screenshot 2025-05-09 155446](https://github.com/user-attachments/assets/8cd79a1c-8c85-4394-9ca3-cc402df1c714)

![Screenshot 2025-05-09 155440](https://github.com/user-attachments/assets/4cac1068-b2e1-4c15-b3f4-e67ec5aa6c7d)


![Screenshot 2025-05-09 155450](https://github.com/user-attachments/assets/1357e73f-056c-4c91-8ea3-81e3001414b9)

Subtraction

![image](https://github.com/user-attachments/assets/1a1b63ce-dbbe-403a-875f-26f57fa12791)

![Screenshot 2025-05-09 160056](https://github.com/user-attachments/assets/f02ea44c-f1bf-433e-a03b-da4701f2c066)

![image](https://github.com/user-attachments/assets/0147557c-7279-4690-a6db-9ce97cd3f2eb)

![image](https://github.com/user-attachments/assets/3003cfa7-cf17-451f-8aeb-720119752cf7)


Multiplication

![image](https://github.com/user-attachments/assets/fbf566e9-9747-4444-ab42-03af4a234c6a)

![image](https://github.com/user-attachments/assets/6cb1cd9a-855e-4c02-8435-0cdeb18bafe3)

![image](https://github.com/user-attachments/assets/726d1f9a-d471-4fa1-9924-9fd75b596980)

![image](https://github.com/user-attachments/assets/5d1dbcc6-5c1f-43f2-879e-879c9248257e)

Division
![image](https://github.com/user-attachments/assets/bc832497-880b-4ae2-9df4-1da12126b234)

![image](https://github.com/user-attachments/assets/8e49dd52-6ecd-4a15-9d29-096115a14ae0)

![image](https://github.com/user-attachments/assets/9dfc97b6-e327-42b6-9170-37d6a3cc8c8f)

![image](https://github.com/user-attachments/assets/92707a1f-691a-4a6b-a59b-713bc33d3202)

## Results:

The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
