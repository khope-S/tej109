---
title: "My Vending Machine Midterm"
date: 2025-01-15 12:00:00 +0000
categories: [Projects]
tags: [Vending Machine, Midterm, TEJ20R]
pin: false
---

![Final Vending Machine](https://github.com/user-attachments/assets/cf389e08-7e82-4ec8-877b-a53acc4cf320)
*Final Vending Machine Product*

# Function:
### The function of this project is to dispense candy and chocolates from a vending machine.

# Explanation
This project is a simple 3-product vending machine. Users input a code (e.g., A1, A2) and insert money to receive a product. If multiple buttons are pressed simultaneously, the program shuts down. Both code and money are required for the system to operate. 

The first breadboard feeds into a NAND gate. NAND gates provide a mostly HIGH output to an NPN transistor, keeping the 555 timer reset. If the NAND gate outputs LOW, the 555 timer activates.

## Inputs
- The inputs are button switches for the code and a card input.

## Outputs
- Outputs include three servo motors connected to metal wires, spinning clockwise to dispense products.

# Circuit Diagram
![Circuit Diagram](https://github.com/user-attachments/assets/09c4a6b2-43b6-485f-8743-859ebcb2149a)

# Back Wiring
![Back Wiring](https://github.com/user-attachments/assets/f8e6aa3e-175a-4fab-9e99-13184f32aca6)

# Logic Diagram
![Logic Diagram](https://github.com/user-attachments/assets/fd1fc8bc-e0c7-46dd-87d8-d95fb2bcc7d5)
