# EMARI: Infrared-Assisted Metabolite Extraction System

An RTOS-driven, fuzzy-logic controlled mechatronic prototype for precise thermal and mechanical agitation.

## System Architecture

MCU: ESP32-S3

OS: FreeRTOS (Task scheduling for dual-motor control and sensor polling)

Control Algorithm: Custom Fuzzy Logic Controller (replacing standard PID for non-linear thermal dynamics)

Hardware: Industrial PT100/LM35 sensors, BLDC motors, Ceramic Fiber insulation.

Protocols: SPI, I2C, UART

## Repository Structure

/firmware: Core C/C++ code.

/control: The fuzzy logic math and rule base.

/rtos_tasks: The FreeRTOS scheduler handling concurrent operations.

/drivers: Low-level sensor communication.

/hardware: Wiring diagrams and physical constraints (ceramic fiber specs).
