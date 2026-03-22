# WIRING GUIDE - INDUSTRIAL AUTOMATION PROJECT

## 1. Power Supply (24VDC)
- Use Meanwell NDR-240-24 (10A) for Main Power.
- Use Meanwell EDR-120-24 (5A) for Auxiliary/Sensor Power.
- Red wire (+) / Black wire (-).

## 2. PLC Siemens S7-1200
- CPU 1212C: Terminals L+/M connected to 24VDC.
- DI (Digital Inputs): Connected to Field Switches.
- DQ (Digital Outputs): Connected to Interposing Relays (Phoenix Contact).
- AI (Analog Inputs): Connected to Transmitters (Honeywell/Endress+Hauser).

## 3. Instrument Loops
- Pressure Transmitters (STG74S): 4-20mA loop. Connect (+) to 24VDC, (-) to PLC AI channel.
- Temperature Sensors (PT100): Direct connection to RTD modules (3-wire/4-wire).

## 4. Output Control
- Solenoid Valves (ASCO): Powered via Phoenix Contact Relays to isolate PLC outputs.