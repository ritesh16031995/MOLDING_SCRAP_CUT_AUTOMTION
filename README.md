# Mitsubishi PLC Automation Project – Sheet Feeding & Hydraulic Cutting Machine
This project is an industrial automation system developed using Mitsubishi PLC, HMI, and Servo technologies. The machine performs automatic sheet feeding, hydraulic cutting, production counting, and manual maintenance operations.

### Software Used
- GX Works2 (PLC Programming)
- GT Works3 / GOT HMI (Operator Interface Development)
- MR Configurator2 (Servo Configuration & Tuning)

## Features

### PLC Control System
- Auto and Manual operation modes
- Hydraulic cutter control
- Servo-based sheet feeding mechanism
- Production counting and scrap counting
- Sensor-based machine sequencing
- Safety interlocks and machine protection logic
- Pneumatic and hydraulic actuator control

### HMI System (GT Works3)
- User-friendly navigation screens
- Auto operation interface
- Manual operation interface
- Production monitoring
- Scrap count monitoring
- Parameter setting screens
- Machine status and alarm indication

### Servo Motion Control
- Feed length control through pulse positioning
- RPM-to-pulse conversion calculations
- Adjustable feed length from HMI
- Servo speed parameterization
- Positioning accuracy optimization

## PLC Program Structure

### AUTO Program
- Automatic feeding sequence
- Hydraulic cutter operation
- Production counting
- Skip-cut functionality
- Sensor-based machine sequencing

### MANUAL Program
- Feeder Forward
- Feeder Reverse
- Hydraulic ON/OFF
- Cutter UP
- Cutter DOWN
- Maintenance operations

### SERVO Program
- Feed length calculations
- RPM calculations
- Pulse generation
- Positioning control
- Speed conversion logic

## Key Functions Implemented
- Servo pulse positioning control
- Hydraulic cutting automation
- HMI-based machine operation
- Auto/Manual mode switching
- Sensor interlocking logic
- Real-time machine status monitoring

## Technologies
- Mitsubishi FX Series PLC
- Mitsubishi GOT HMI
- Mitsubishi Servo System
- GX Works2
- GT Works3
- MR Configurator2

## Applications
This project architecture can be applied to:
- Sheet Feeding Machines
- Hydraulic Cutting Machines
- Press Automation Systems
- Material Handling Equipment
- Packaging Machinery
- Industrial Production Lines

## Author
**Ritesh Mohanty**
