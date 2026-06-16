# Pure Sine Wave Inverter

A closed-loop pure sine wave inverter designed to convert a 12V DC source into a regulated 220VAC, 50Hz output using Sinusoidal Pulse Width Modulation (SPWM), MOSFET-based switching, and PI feedback control.

The project explores inverter control techniques, waveform synthesis, output regulation, and power electronics design for low-distortion AC power generation.

---

## Objective

The objective of this project was to design and validate a pure sine wave inverter capable of generating a stable 220VAC output from a 12V DC source while maintaining waveform quality and output voltage regulation through closed-loop control.

---

## System Architecture

12V DC Input

↓

SPWM Generator (Arduino)

↓

PI Feedback Controller

↓

Gate Driver Stage (IR2112)

↓

MOSFET H-Bridge

↓

12V–220V Transformer

↓

Output Filter

↓

220VAC Output (50Hz)

---

## Hardware Components

* Arduino Microcontroller
* IR2112 Gate Driver
* MOSFET H-Bridge
* 12V–220V Transformer
* Output Filter Network
* Voltage Feedback Circuit

---

## Control Strategy

The inverter uses Sinusoidal Pulse Width Modulation (SPWM) to synthesize an AC waveform from a DC source.

A feedback signal from the output stage is continuously monitored and processed through a Proportional-Integral (PI) control loop. The controller adjusts the modulation characteristics to compensate for output voltage deviations and improve waveform stability under varying operating conditions.

---

## Engineering Contributions

* SPWM waveform generation
* PI feedback control implementation
* Power electronics design
* Gate driver integration
* H-bridge switching control
* Output voltage regulation
* Simulation and verification
* Hardware prototyping and testing

---

## Simulation Results

Simulation was performed to validate inverter operation, switching behavior, and output waveform quality before hardware implementation.

---

## Hardware Validation

Oscilloscope measurements were used to verify waveform generation and evaluate inverter performance during testing.

---

## Demonstration

Hardware Demonstration:
https://www.youtube.com/watch?v=baxVjNvxOzI

Simulation Demonstration:
https://www.youtube.com/watch?v=YOkIT0XrTNo

---

## Technologies

* Embedded C/C++
* Arduino
* SPWM
* PI Control
* Power Electronics
* H-Bridge Topology
* IR2112
* MOSFET Drivers
* Inverter Design
* Closed-Loop Control Systems
