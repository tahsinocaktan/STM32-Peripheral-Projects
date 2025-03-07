# STM32 Peripheral Learning Projects

## Overview

This repository contains a collection of STM32 projects aimed at understanding and utilizing various **peripherals** such as GPIO, timers, PWM, and ADC. Each project is designed to provide hands-on experience with STM32 microcontrollers by implementing fundamental embedded system applications.

## Projects

### **1. Blinking LED with a Timer**

- Utilizes an **STM32 timer** to generate a periodic signal.
- Controls an LED blinking rate using the timer overflow event.
- Demonstrates **interrupt handling** for precise timing.

### **2. Button LED Control**

- Implements **GPIO input and output** functionality.
- Reads a push button state and toggles an LED accordingly.
- Debouncing techniques can be applied for a stable response.

### **3. LED Blink**

- A basic project to blink an LED using **GPIO control**.
- Introduces the fundamental structure of an STM32 firmware project.
- A great starting point for beginners learning STM32 development.

### **4. Potentiometer and LED (led\_with\_pot)**

- Reads **analog values** from a potentiometer using the **ADC**.
- Maps the potentiometer value to control LED brightness.
- Demonstrates **analog-to-digital conversion (ADC) and PWM**.

### **5. PWM Signal**

- Generates a **PWM (Pulse Width Modulation)** signal using STM32 timers.
- Shows how to control the duty cycle for applications like LED dimming and motor control.
- Useful for understanding **timer-based PWM generation**.

### **6. Reading Potentiometer Value**

- Reads an analog value from a potentiometer using the **ADC module**.
- Prints the real-time ADC values to a **serial monitor (UART)** for debugging.
- Can be extended for real-time sensor-based applications.

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/<your-username>/STM32-Peripheral-Projects.git
   cd STM32-Peripheral-Projects
   ```
2. Open the project in **Keil uVision** or **STM32CubeMX**.
3. Open the `.ioc` file in STM32CubeMX to check and modify configurations.
4. Generate the project code and build it in **Keil uVision**.
5. Compile and flash the firmware onto an STM32 microcontroller using **ST-Link**.
6. Observe the output using LEDs, buttons, and a serial terminal.

## Required Tools

- **Microcontroller:** STM32F0/F1/F4 Series (Depends on project setup)
- **Development Environment:** Keil uVision
- **Code Generator:** STM32CubeMX
- **Debugger & Programmer:** ST-Link v2
- **Additional Components:** LEDs, push buttons, potentiometer (for ADC projects)

## Contributors

- Developed by [Tahsin OCAKTAN]

---

This repository provides a structured approach to learning STM32 peripherals with practical applications. Contributions and improvements are welcome!


