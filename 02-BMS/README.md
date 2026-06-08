# Battery Management System (BMS)

## Overview

This folder contains the design, modeling, and simulation files related to the Battery Management System (BMS) developed for the Electric Motorcycle Graduation Project.

The BMS is responsible for monitoring, protecting, and managing the battery pack to ensure safe operation, maximize battery lifespan, and maintain reliable performance under various operating conditions.

---

## Objectives

* Monitor battery pack voltage and current.
* Estimate battery State of Charge (SoC).
* Protect the battery against abnormal operating conditions.
* Improve battery safety and reliability.
* Validate BMS functionality through simulation.

---

## Contents

```text
BMS/
│
├── Models/
│   ├── Battery Pack Model
│   ├── Cell Monitoring Model
│   └── Protection Logic
│
├── Simulations/
│   ├── Charging Scenarios
│   ├── Discharging Scenarios
│   └── Fault Conditions
│
├── Results/
│   ├── Voltage Profiles
│   ├── Current Profiles
│   └── SoC Estimation Results
│
└── Documentation/
```

---

## Implemented Features

### Battery Monitoring

* Cell voltage measurement
* Pack voltage monitoring
* Charge/discharge current monitoring

### Protection Functions

* Over-voltage protection
* Under-voltage protection
* Over-current protection
* Short-circuit protection
* Safe operating limit verification

### State of Charge (SoC) Estimation

* Battery charge tracking
* SoC calculation and monitoring
* Performance validation during charging and discharging cycles

---

## Simulation Environment

The BMS models were developed and tested using:

* MATLAB
* Simulink
* Simscape Electrical

Simulation scenarios were created to evaluate system behavior under normal operation and fault conditions.

---

## Key Outcomes

* Successful monitoring of battery operating parameters.
* Reliable detection of abnormal conditions.
* Accurate battery state tracking during operation.
* Verification of battery protection strategies through simulation.

---

## Integration with the Electric Motorcycle System

The Battery Management System interfaces with the following subsystems:

* Battery Pack
* Motor Drive Inverter
* PMSM Motor Control System (FOC)

The BMS provides critical battery information and protection signals to ensure safe and efficient operation of the complete electric drivetrain.

---

## Future Improvements

* State of Health (SoH) estimation
* Cell balancing algorithms
* Thermal management integration
* Embedded implementation on a microcontroller platform

---

## Author

Electric Motorcycle Graduation Project Team

Department of Electrical Engineering
