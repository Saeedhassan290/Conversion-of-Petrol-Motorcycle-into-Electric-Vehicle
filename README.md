# Conversion-of-Petrol-Motorcycle-into-Electric-Vehicle
# Electric Motorcycle Powertrain Development

This repository contains the design, simulation, and control development files for an Electric Motorcycle Graduation Project. The project focuses on the complete electric drivetrain system, including battery management, motor control, and power electronics required for efficient vehicle operation.

## Project Overview

The objective of this project is to develop and validate the key subsystems of an electric motorcycle through modeling, simulation, and control implementation. The repository includes designs, simulation models, control algorithms, and supporting documentation for the following major components:

* Battery Management System (BMS)
* Field-Oriented Control (FOC) of Permanent Magnet Synchronous Motor (PMSM)
* Inverter Design and Control

## Repository Structure

```text
Electric-Motorcycle-Powertrain/
│
├── BMS/
│   ├── Simulation models
│   ├── Battery monitoring algorithms
│   └── Documentation
│
├── FOC/
│   ├── PMSM models
│   ├── FOC control algorithms
│   ├── MATLAB/Simulink files
│   └── Documentation
│
├── Inverter/
│   ├── Power electronics simulations
│   ├── Pcb design files
│   └── Documentation
│
└── README.md
```

---

## BMS (Battery Management System)

The BMS folder contains the models and files related to battery monitoring, protection, and management.

### Features

* Cell voltage monitoring
* Current measurement and protection
* State-of-Charge (SoC) estimation
* Battery pack simulation models

### Tools Used

* MATLAB/Simulink

---

## FOC (Field-Oriented Control)

The FOC folder contains the motor control models used to achieve high-performance control of a Permanent Magnet Synchronous Motor (PMSM).

### Features

* Clarke and Park transformations
* Current control loops
* Speed control loop
* Space Vector PWM (SVPWM)
* Complete electric drive simulation

### Tools Used

* MATLAB/Simulink
* DSP-based control implementation

---

## Inverter Design

The Inverter folder contains power electronics models and inverter control strategies used to drive the PMSM.

### Features

* Three-phase inverter modeling
* PWM switching techniques
* SVPWM implementation

### Tools Used

* LTspice XVII
* Altium Designer

---

## Software Requirements

* MATLAB
* Simulink
* Simscape Electrical 
* LTspice XVII
* LTspice XVII

---

## Project Goals

* Develop a complete electric motorcycle drivetrain model.
* Design and validate the battery management system.
* Implement efficient PMSM control using Field-Oriented Control.
* Design and evaluate inverter switching strategies.
* Verify system performance through simulation before hardware implementation.

---

## Contributors

* Saeed Mohamed 
* Seif Ahmed
* Ali Tarek
* Ahmed Ashraf
* Ahmed Mohamed
* Kirolos Sabry
* Martina Ashraf
* Esraa Mohamed
* Menna Elsayed

Electrical Power Engineering Department

---

## License

This repository is intended for educational and research purposes.

