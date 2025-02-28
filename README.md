# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Lathika Sree R
 # REGISTER NUMBER : 212224040169
 # DEPARTMENT : CSE
 # YEAR : 1

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
AND Gate

![WhatsApp Image 2025-02-27 at 22 52 16_e288a9a4](https://github.com/user-attachments/assets/62930f79-a25f-4acf-8a2b-aeaa9b915fec)

OR Gate

![WhatsApp Image 2025-02-27 at 22 52 38_0ce86342](https://github.com/user-attachments/assets/88ec5951-763f-4042-87e4-f405b3af7512)

NOT Gate

![WhatsApp Image 2025-02-27 at 22 53 13_5897d057](https://github.com/user-attachments/assets/3fa10097-a4a8-4297-a718-8cad727729b1)

NAND Gate

![WhatsApp Image 2025-02-27 at 22 53 43_cbc278df](https://github.com/user-attachments/assets/f8ec58d6-5812-4f7f-8087-e392e9fab44c)

NOR Gate

![WhatsApp Image 2025-02-27 at 22 55 22_3d264ecd](https://github.com/user-attachments/assets/1a1e0164-4c5f-4d45-ac16-60e6cd395405)

XOR Gate

![WhatsApp Image 2025-02-27 at 22 54 20_e4783afd](https://github.com/user-attachments/assets/237474f5-0da7-4878-8073-03ded59aca44)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
![WhatsApp Image 2025-02-27 at 22 40 35_1ec67c70](https://github.com/user-attachments/assets/ae57453b-67d3-42bf-956b-e36dee28fb00)
![WhatsApp Image 2025-02-27 at 22 40 35_e88a3ced](https://github.com/user-attachments/assets/1af8662c-d772-436f-9205-29ccee6d20eb)
![WhatsApp Image 2025-02-27 at 22 43 35_9c5efec1](https://github.com/user-attachments/assets/44e032fd-e889-4d2f-aada-753ed0803fbf)
![WhatsApp Image 2025-02-27 at 22 45 51_c50cf0db](https://github.com/user-attachments/assets/dc736c26-4984-4fc5-82ed-9a7a0a7989f3)
![WhatsApp Image 2025-02-27 at 22 45 51_f31b1ec0](https://github.com/user-attachments/assets/84732f7e-cdc9-4c7e-ab8a-d020f2b5e981)
![WhatsApp Image 2025-02-27 at 22 45 53_5fce9a24](https://github.com/user-attachments/assets/3927c93b-906c-4adf-9925-b768641fc81c)
![WhatsApp Image 2025-02-27 at 22 50 15_83d8f6b6](https://github.com/user-attachments/assets/5fcb45b8-b36b-4221-886f-1b71daa66cc8)
![WhatsApp Image 2025-02-27 at 22 50 15_f26ff0b2](https://github.com/user-attachments/assets/8b46e22f-8f18-4ddc-82e7-032d08bbe34e)
![WhatsApp Image 2025-02-27 at 22 50 16_0fca15a1](https://github.com/user-attachments/assets/7b1f6277-15a9-4343-a650-3a404040951a)
![WhatsApp Image 2025-02-27 at 22 50 16_b447c7f7](https://github.com/user-attachments/assets/93b958fb-a07d-4d7c-bf0c-136dca6647a4)
![WhatsApp Image 2025-02-27 at 22 50 16_d82596f6](https://github.com/user-attachments/assets/345855cf-466b-420e-95cd-7cde01122cc1)
![WhatsApp Image 2025-02-27 at 22 50 16_0156c467](https://github.com/user-attachments/assets/a368e0af-11ac-4558-b9e0-746e287f70a9)
![WhatsApp Image 2025-02-27 at 22 50 17_d9f88f69](https://github.com/user-attachments/assets/b6b50fd5-abef-4dcd-8184-e94de89aa26f)
![WhatsApp Image 2025-02-27 at 22 50 17_d9f88f69](https://github.com/user-attachments/assets/3a4c77e0-8a4f-435d-b553-a21fd65726fb)
![WhatsApp Image 2025-02-27 at 23 07 58_e4527d43](https://github.com/user-attachments/assets/08ba1864-f613-450d-bc40-a2b26daf5faf)
![WhatsApp Image 2025-02-27 at 23 07 34_77043411](https://github.com/user-attachments/assets/bd469e2c-91c8-4b1b-842d-18ac23454af8)
![WhatsApp Image 2025-02-27 at 23 07 14_ed99b6f3](https://github.com/user-attachments/assets/97037b82-2732-482e-8fba-4b984080f50c)
![WhatsApp Image 2025-02-27 at 23 06 53_12b01f40](https://github.com/user-attachments/assets/c3971725-02d9-4069-8516-1180d21be489)
![WhatsApp Image 2025-02-27 at 23 06 33_33ee0d02](https://github.com/user-attachments/assets/02a3813e-ac24-4743-a9ab-05aea6fdfb7b)



#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
