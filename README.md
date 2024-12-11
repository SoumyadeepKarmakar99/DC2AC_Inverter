# DC to AC Power Inverter Design

## Project Overview
This project involves the development of a functional DC to AC inverter capable of converting 12V DC to 220V AC for powering AC appliances during power outages. The circuit is designed and implemented using key components such as the CD4047BE IC, IRF Z44N MOSFETs, and a 12-0-12 to 220V transformer.

## Key Features
- **Pulse Generation**: Utilizes the CD4047BE IC as an astable multivibrator to generate a 50 Hz pulse with a 50% duty cycle.
- **Switching Mechanism**: Integrates IRF Z44N MOSFETs to amplify and drive the signal to the transformer.
- **Voltage Step-Up**: Incorporates a transformer to step up the voltage from 12V DC to 220V AC.
- **Safety Measures**: Uses 220 Ohm resistors and 1N4007 diodes for circuit protection and unidirectional current flow.

## Applications
This inverter is suitable for:
- UPS systems
- Solar power conversion
- Motor speed control

## Components Used
- **CD4047BE IC**: Astable multivibrator for pulse generation.
- **IRF Z44N MOSFETs**: For signal amplification and driving.
- **12-0-12 to 220V Transformer**: For voltage step-up.
- **220 Ohm Resistors**: For circuit protection.
- **1N4007 Diodes**: For unidirectional current flow and protection.

## Circuit Design
The circuit design includes the CD4047BE IC to generate a stable 50 Hz pulse, which is then used to drive the IRF Z44N MOSFETs. These MOSFETs amplify the signal and drive the transformer, which steps up the voltage from 12V DC to 220V AC. Resistors and diodes are incorporated for safety measures and circuit protection.

## Conclusion
This DC to AC inverter design is a reliable solution for converting 12V DC to 220V AC, making it ideal for various applications such as UPS systems, solar power conversion, and motor speed control.

----------
