# LED_6: STM32F4 Discovery Board LED Blinking Example

## Project Overview

This project demonstrates how to test the clock and I/O pin functionality by blinking **LED 6** on the STM32F4 Discovery board (STM32F407VG). The goal is to verify that the clock system and GPIO pin configuration are working as expected by toggling the LED connected to GPIO pin PG13.

## Hardware Used

- **STM32F4 Discovery Board** (STM32F407VG)
- **LED 6** (Green LED) connected to **GPIO pin PG13**
- **System Clock:** Default configuration (adjustable in STM32CubeMX)
- **Programming Environment:** STM32CubeIDE or any IDE supporting STM32 development

## Features

- Blinks **LED 6** (PG13) every 500ms.
- Configures **GPIO pin PG13** as an output to drive the LED.
- Tests **system clock** and **GPIO configuration** on STM32F4 Discovery board.

## How to Run the Project

### Step 1: Set up the Project in STM32CubeIDE

1. **Open STM32CubeIDE** and create a new project for the STM32F407VG microcontroller.
2. **Configure the GPIO pin PG13** (used for LED 6) as an output in STM32CubeMX (integrated in STM32CubeIDE).


