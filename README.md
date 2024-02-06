# ECU Drivers for PIC18F4620

## Overview

Welcome to the ECU Drivers repository for PIC18F4620! This collection of drivers empowers your Electronic Control Unit (ECU) functionality on the powerful PIC18F4620 microcontroller. Dive in, explore, and enhance your embedded projects with ease.

## Table of Contents

- [Microcontroller Abstraction Layer (MCAL)](#microcontroller-abstraction-layer-mcal)
  - [GPIO Interrupt](#gpio-interrupt)
  - [EEPROM](#eeprom)
- [Electronic Control Unit (ECU) Layer](#electronic-control-unit-ecu-layer)
  - [LED, Motor, Relay, LCD, Push Button Drivers](#led-motor-relay-lcd-push-button-drivers)
- [Happy coding!](#happy-coding)

## Microcontroller Abstraction Layer (MCAL)

### GPIO Interrupt

#### Overview

The GPIO interrupt driver in the MCAL layer empowers you to seamlessly handle interrupts triggered by General-Purpose Input/Output (GPIO) pins. Embrace the event-driven programming model on the PIC18F4620 microcontroller with configurable pin selection, edge triggers, and user-defined interrupt service routines (ISRs).

#### Features

- Configurable GPIO pin selection for interrupt monitoring.
- Configurable edge trigger (rising, falling, or both).
- User-defined ISR callback.

### EEPROM

#### Overview

The EEPROM driver in the MCAL layer enables smooth read and write operations to the Electrically Erasable Programmable Read-Only Memory (EEPROM) of the PIC18F4620. Harness the power of non-volatile storage for preserving critical data across power cycles.

#### Features

- Read and write operations to EEPROM memory.
- Configurable EEPROM addresses for data storage.
- Error handling for write protection and boundary checks.

## Electronic Control Unit (ECU) Layer

### LED, Motor, Relay, LCD, Push Button Drivers

#### Overview

The ECU layer brings simplicity and efficiency to your projects with high-level drivers for essential peripherals. The drivers build upon the GPIO interrupt functionality provided by the MCAL layer.

#### Features

- Abstraction of hardware details for easy integration.
- Support for LED control (on/off, blinking).
- Motor control with direction and speed settings.
- Relay activation and deactivation.
- LCD display control (write characters, clear screen).
- Push button state monitoring with debounce.



#### EEPROM

Extend your project's memory with the new EEPROM driver in the MCAL layer. Seamlessly read and write data to EEPROM, ensuring your critical information persists across power cycles.



## Happy coding!

Explore the drivers, integrate them into your projects, and embark on a journey of innovation. Feel free to contribute, share your experiences, and, most importantly, happy coding!
