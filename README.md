# EV-DC-DC-Boost-Converter-PI-Control
Closed-loop DC-DC Boost Converter designed in MATLAB Simulink using PI control and PWM duty-cycle regulation. The controller maintains a regulated 48 V output under changing operating conditions.
# Closed-Loop DC-DC Boost Converter using PI Controller

## Overview

This project presents the design and simulation of a closed-loop DC-DC Boost Converter using MATLAB Simulink.

A PI controller continuously regulates the converter output voltage by adjusting the PWM duty cycle.

The controller maintains a reference voltage of **48 V** despite disturbances such as load variations.

---

## Features

- Closed-loop voltage regulation
- PI Controller
- PWM generation using Comparator + Carrier Wave
- MOSFET switching
- Output voltage sensing
- Feedback control
- Stable 48 V output

---

## Software Used

- MATLAB
- Simulink
- Simscape Electrical

---

## Control Strategy

Reference Voltage

↓

Error Calculation

↓

PI Controller

↓

Duty Cycle Saturation

↓

PWM Generation

↓

MOSFET

↓

Boost Converter

↓

Voltage Sensor

↓

Feedback

---

## Circuit Components

- DC Voltage Source
- Inductor
- MOSFET
- Diode
- Output Capacitor
- Load Resistance
- Voltage Sensor
- PI Controller
- PWM Comparator
- Repeating Sequence Carrier

---

## Simulation Results

### Test 1

Reference Voltage = 48 V

Result:
Stable output around 48 V.

---

### Test 2

Load Resistance changed

Result:
Controller compensated and recovered output voltage.

---

### Test 3

Reference voltage changed

Result:
Controller tracked the new reference with expected transient response.

---

## Future Improvements

- Buck-Boost topology
- Bidirectional converter
- Battery charging mode
- Motor drive integration
- Battery Management System interface
- Digital controller implementation

---

## Author

Vidhanshu Tenwalia

EV Engineering Portfolio
