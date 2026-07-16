# STM32F407 ADC Sensor Interfacing

## Overview

This project demonstrates **Analog-to-Digital Converter (ADC)** interfacing on the **STM32F407 Discovery Board** using **Embedded C**, **STM32CubeIDE**, and the **STM32 HAL Library**. An analog input from a **potentiometer** is converted into a digital value using the ADC peripheral and monitored through **UART** in **Proteus**.

## Hardware Required

* STM32F407 Discovery Board
* 10kΩ Potentiometer
* Jumper Wires
* Breadboard
* USB Cable

## Software Used

* STM32CubeIDE
* Embedded C
* STM32 HAL Library
* Proteus (for UART monitoring)

## Features

* ADC initialization using STM32 HAL
* Analog voltage reading from a potentiometer
* Analog-to-digital conversion
* UART transmission of ADC values
* Real-time monitoring in Proteus

## Hardware Connections

* **STM32F407 Discovery Board**
* **10kΩ Potentiometer**

  * One terminal → **3.3V**
  * One terminal → **GND**
  * Wiper (middle pin) → **ADC Input Pin**
* **UART TX/RX** connected for serial monitoring (Proteus or USB-to-UART module)

> *The ADC channel and UART pins can be changed according to the STM32CubeMX configuration.*

## Project Structure

```text
Core/
├── Inc/
│   └── main.h
├── Src/
│   └── main.c
```

## How to Run

1. Open the project in **STM32CubeIDE**.
2. Build the project.
3. Flash the program to the **STM32F407 Discovery Board**.
4. Rotate the potentiometer to change the analog input voltage.
5. Observe the converted ADC values through **UART** in Proteus or a serial terminal.

## Technologies Used

* Embedded C
* STM32 HAL Library
* STM32F407 Discovery Board
* ADC
* UART
* GPIO
* Proteus

## Author

**Nitin Ghugarkar**
