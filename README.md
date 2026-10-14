# MOSFET Analog Voltage Amplifier

## Project Overview

Designed and simulated a four-stage MOSFET-based analog voltage amplifier powered by a single 3.3 V DC supply. The amplifier incorporates three cascaded common-source NMOS amplification stages followed by a source-follower output buffer.

The project focuses on analog circuit design, transistor biasing, voltage amplification, frequency response, impedance analysis, and low-power operation.

The circuit was developed using KiCad and evaluated through SPICE simulations, with analytical calculations performed to predict and verify circuit performance.

## Key Features

- **Four-Stage Amplifier:** Three common-source NMOS stages and one source-follower output stage.
- **3.3 V Supply:** Designed for low-voltage operation.
- **High Voltage Gain:** Cascaded amplification stages provide substantial signal amplification.
- **High Input Resistance:** Designed to minimize input loading.
- **Output Buffer:** Source-follower stage improves the amplifier's load-driving capability.
- **AC Coupling:** Coupling capacitors separate DC operating points between stages.
- **Low-Power Design:** MOSFET biasing selected to minimize DC power consumption.

## Technologies Used

- **Circuit Design:** KiCad
- **Simulation:** SPICE
- **Components:** NMOS Transistors, Resistors, Capacitors
- **Engineering Concepts:** Analog Electronics, MOSFET Biasing, Small-Signal Analysis, Frequency Response, Impedance Matching, Low-Power Circuit Design

## Design Methodology

### 1. Circuit Architecture
Designed a four-stage amplifier using three common-source stages to achieve high voltage gain, followed by a source-follower buffer for the output.

### 2. DC Biasing
Calculated transistor operating points, drain currents, gate-source voltages, and resistor values to establish suitable amplifier bias conditions.

### 3. Small-Signal Analysis
Analyzed individual stages to determine transconductance, output resistance, voltage gain, and input resistance.

### 4. Frequency Response
Evaluated the effects of coupling capacitors and transistor characteristics on the amplifier's frequency response and bandwidth.

### 5. SPICE Verification
Performed circuit simulations to evaluate operating points, gain, input resistance, and DC power consumption. Compared analytical predictions with simulated performance.

## Simulation Results

| Parameter | Result |
|---|---|
| Supply Voltage | 3.3 V |
| Amplifier Stages | 4 |
| Simulated Voltage Gain | 65.5 dB |
| Simulated Input Resistance | 794 kΩ |
| Simulated DC Power Consumption | 0.997 mW |
| Theoretical Voltage Gain | Approximately 66.7 dB |

The simulated gain was close to the theoretical prediction, demonstrating reasonable agreement between analytical design calculations and SPICE simulation.

## Project Files

- **Circuit Design:** KiCad schematic and supporting project files.
- **Simulation Results:** DC operating-point and AC frequency-response plots.
- **Design Calculations:** Analytical calculations for MOSFET biasing and amplifier performance.
- **Circuit Images:** Screenshots illustrating the amplifier architecture.
- The images and calculations are included in the report for practical viewing.

## Project Status

Circuit design and SPICE simulation completed. Results represent simulated performance.
