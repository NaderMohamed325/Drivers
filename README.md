# ECU Drivers for PIC18F4620

## Overview

This repository contains drivers for Electronic Control Unit (ECU) functionality using the PIC18F4620 microcontroller. The drivers are organized into two layers: the Microcontroller Abstraction Layer (MCAL) and the Electronic Control Unit (ECU) layer. The focus of this README is on the GPIO interrupt functionality implemented in the MCAL layer, along with drivers for LED, motor, relay, LCD, and push buttons in the ECU layer.

## Microcontroller Abstraction Layer (MCAL)

### GPIO Interrupt

#### Overview

The GPIO interrupt driver in the MCAL layer enables handling interrupts triggered by General-Purpose Input/Output (GPIO) pins. The PIC18F4620 microcontroller provides interrupt-on-change functionality for specific pins, allowing efficient event-driven programming.

#### Features

- Configurable GPIO pin selection for interrupt monitoring.
- Configurable edge trigger (rising, falling, or both).
- User-defined interrupt service routine (ISR) callback.




## Electronic Control Unit (ECU) Layer

### LED, Motor, Relay, LCD, Push Button Drivers

#### Overview

The ECU layer provides high-level drivers for common peripherals like LEDs, motors, relays, LCDs, and push buttons. These drivers build upon the GPIO interrupt functionality provided by the MCAL layer.

#### Features

- Abstraction of hardware details for easy integration.
- Support for LED control (on/off, blinking).
- Motor control with direction and speed settings.
- Relay activation and deactivation.
- LCD display control (write characters, clear screen).
- Push button state monitoring with debounce.







**Happy coding!**
