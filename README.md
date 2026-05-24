# PIC 28-Pin Development Board – KiCad PCB Design

A compact and versatile **PIC 28-Pin Development Board** designed using **KiCad EDA** for schematic capture and PCB layout. This project is based on the **PIC16F873A / PIC16F876A / PIC16F877A family architecture**, providing GPIO breakout pins, push buttons, EEPROM interface, IR sensor support, LEDs, and expansion headers for embedded systems development.

The board is suitable for learning PIC microcontrollers, embedded programming, sensor interfacing, and electronics prototyping.

---

# Project Overview

This project demonstrates:

* PIC 28-pin microcontroller minimum system design
* PCB layout using KiCad
* EEPROM interfacing
* IR sensor interface
* Push-button inputs
* LED status indicators
* GPIO breakout headers
* 3D PCB visualization

---

# Features

* Supports 28-pin PIC microcontroller
* GPIO breakout headers
* Push-button interface
* External EEPROM support
* IR sensor module interface
* Status LEDs
* Compact PCB layout
* Through-hole component design
* Designed using KiCad

---

# Software Used

* KiCad

Official Website: [KiCad Official Website](https://www.kicad.org?utm_source=chatgpt.com)

---

# Hardware Components

| Component               | Description                  |
| ----------------------- | ---------------------------- |
| PIC16F873A / PIC16F876A | PIC Microcontroller          |
| AT24Cxx                 | EEPROM Memory IC             |
| TSOP1738                | IR Receiver Module           |
| Push Buttons            | User Input                   |
| LEDs                    | Status Indicators            |
| Capacitors              | Power filtering              |
| Resistors               | Pull-up and current limiting |
| Pin Headers             | GPIO breakout                |

---

# Project Structure

```bash id="f4jv7a"
PIC-28PIN-DEVELOPMENT-BOARD/
│
├── Schematic/
│   └── pic_28pin_board.kicad_sch
│
├── PCB/
│   └── pic_28pin_board.kicad_pcb
│
├── Gerber/
│   └── Manufacturing_Files
│
├── Images/
│   ├── PIC_28PIN_3D_FRONT.png
│   ├── PIC_28PIN_3D_BACK.png
│   ├── PIC_28PIN_PCB.png
│   └── PIC_28PIN_SCHEMATIC.png
│
└── README.md
```

---

# Circuit Description

The development board is centered around a **28-pin PIC microcontroller** with additional peripheral support circuits.

The design includes:

* Push-button input interface
* EEPROM communication support
* IR receiver module connection
* LED output indicators
* GPIO expansion headers
* Power regulation and filtering

---

# Working Principle

1. +5V supply powers the microcontroller and peripherals.
2. PIC microcontroller executes embedded firmware.
3. Push buttons provide user input.
4. EEPROM stores external data.
5. IR receiver detects remote control signals.
6. LEDs indicate system status or outputs.
7. GPIO headers allow external module interfacing.

---

# PCB Design

The PCB was designed with:

* Organized GPIO routing
* Compact component placement
* Easy soldering access
* Through-hole assembly
* Proper grounding layout
* Beginner-friendly prototyping structure

---


# Electrical Specifications

| Parameter         | Value             |
| ----------------- | ----------------- |
| Microcontroller   | PIC 28-Pin Series |
| Supply Voltage    | +5V DC            |
| EEPROM Support    | Yes               |
| IR Sensor Support | Yes               |
| GPIO Expansion    | Yes               |
| PCB Tool          | KiCad             |

---

# Pin Interfaces

The board exposes:

* Digital GPIO Pins
* Analog Input Pins
* UART Communication
* I2C Interface
* SPI Interface
* EEPROM Interface
* IR Sensor Interface

for embedded application development.

---

# Applications

* Embedded Systems Development
* PIC Programming Practice
* Sensor Interfacing
* IR Remote Projects
* EEPROM Data Logging
* Robotics
* Automation Projects
* Academic Embedded Labs

---

# Development Notes

Compatible with:

* MPLAB X IDE
* XC8 Compiler
* PICkit Programmer
* MikroC
* Embedded C Programming

---

# Future Improvements

* Add onboard USB programmer
* Add voltage regulator section
* Add LCD display connector
* Add relay driver outputs
* Add wireless communication modules

---


This project is open-source and available under the MIT License.
