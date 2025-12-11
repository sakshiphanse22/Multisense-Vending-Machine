# Multisense-Vending-Machine
Accessible vending machine using Raspberry Pi, sensors, servo motors, and touchscreen with Python firmware.

## Overview
The Multisense Vending Machine is an inclusive, intelligent vending solution designed to assist visually and hearing-impaired users.  
It integrates Raspberry Pi, sensors, servo motors, and a touchscreen to provide multiple interaction methods including voice, touch, and keypad inputs.  

---

## Features
- Multilingual voice guidance for accessibility  
- Touchscreen and keypad input support  
- Coin acceptor and UPI payment integration  
- Real-time dispensing control with sensor feedback  
- Servo/DC motor control for item dispensing  
- Inclusive user experience for visually and hearing-impaired users  

---

## Hardware Components
- Raspberry Pi (ARM-based SBC)  
- Servo motors and DC motors  
- Touchscreen display  
- Coin acceptor  
- Various sensors (proximity, IR, etc.)  
- Power supply and connectors  

---

## Software / Firmware
- Programming Languages: Python  
- Operating System: Linux (Raspberry Pi OS)  
- Communication Protocols: UART, I2C, GPIO, PWM  
- Libraries: RPi.GPIO, smbus, pyttsx3 (for voice), Tkinter (for touchscreen UI)  

---

## Working
User Interaction: The user selects an item via touchscreen, keypad, or voice command.
Payment Processing: The system accepts coins or UPI payments and confirms the transaction.
Item Dispensing: Based on the selection, servo/DC motors are activated to dispense the product.
Sensor Feedback: Sensors monitor dispensing and detect errors or blockages in real-time.
Accessibility Features: Multilingual voice guidance and visual feedback ensure inclusive operation for visually and hearing-impaired users.
