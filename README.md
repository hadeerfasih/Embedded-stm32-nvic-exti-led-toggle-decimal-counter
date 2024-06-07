# STM32 NVIC and EXTI - LED Toggle and Decimal Counter

This repository contains the implementation of a lab exercise to understand the Nested Vectored Interrupt Controller (NVIC) and External Interrupt/Event Controller (EXTI) capabilities on an STM32 microcontroller. The project includes toggling an LED based on a button press and a decimal counter on a 7-segment display controlled by two buttons.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Objectives](#objectives)
- [Project Description](#project-description)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project demonstrates the use of NVIC and EXTI on an STM32 microcontroller. It covers configuring interrupts, writing interrupt service routines (ISRs), and managing race conditions.

## Prerequisites
- Understanding of interrupts 
- Basic knowledge of STM32 microcontroller and GPIO configuration

## Objectives
- Understand NVIC capabilities and its differences from typical interrupt controllers
- Review NVIC registers
- Configure and handle interrupts from start to finish
- Implement EXTI driver 

## Project Description
The project consists of two main parts:
1. **LED Toggle**: Detect a falling edge event on a button pin to toggle an LED in an ISR.
2. **Decimal Counter**: Increment or decrement a counter displayed on a 7-segment display using two buttons with interrupts configured on GPIO falling edge.

### System Inputs and Outputs
- **Inputs**: Two push buttons connected to pins PA9 and PB5
- **Output**: One 7-segment display

## Hardware Requirements
- STM32 microcontroller
- Push buttons
- LED
- 7-segment display
- Connecting wires and breadboard

## Software Requirements
- STM32CubeMX (for initialization code generation)
- Keil MDK or STM32CubeIDE (for coding and debugging)

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/stm32-nvic-exti-led-toggle-decimal-counter.git
    ```
2. Open the project in STM32CubeIDE or Keil MDK.
3. Build and flash the project to your STM32 microcontroller.

## Usage
1. Connect the hardware as described in the hardware requirements section.
2. Flash the microcontroller with the provided code.
3. Press the buttons to see the LED toggle and the decimal counter increment or decrement on the 7-segment display.

   


https://github.com/hadeerfasih/Embedded-stm32-nvic-exti-led-toggle-decimal-counter/assets/104545742/12d3d728-4053-48ee-9761-b1a78e932a51

