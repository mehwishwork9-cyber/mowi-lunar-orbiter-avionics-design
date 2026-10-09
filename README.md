# Moon Orbiter for Water Imaging (MOWI) — Avionics Design

**Spacecraft Systems Engineering | Avionics | Satellite Communications | Power Systems | Mission Design**

## Project Overview

The Moon Orbiter for Water Imaging (MOWI) is a conceptual lunar nanosatellite mission designed to identify and map water-ice distribution at the Moon's north and south poles.

This academic group project investigates the design of a spacecraft avionics architecture capable of supporting a four-year lunar water-imaging mission.

The proposed spacecraft operates in a 100 km circular polar lunar orbit and uses Lunar Pathfinder as a communications relay to Earth.

## Mission Objectives

- Map lunar water-ice distribution between 60° and 90° latitude at both poles.
- Support onboard processing and storage of LIDAR imaging data.
- Transmit science data and spacecraft telemetry using Lunar Pathfinder.
- Investigate the use of Commercial Off-The-Shelf (COTS) components to balance performance, cost and reliability.
- Develop an avionics architecture capable of supporting the proposed four-year mission.

## Engineering Design Areas

### 1. Spacecraft Avionics Architecture

The conceptual design investigates a centralised avionics architecture integrating:

- Onboard Computer (OBC)
- Electrical Power System (EPS)
- Communications subsystem
- Imaging payload
- Propulsion subsystem
- AOCS and housekeeping sensors

The architecture considers spacecraft data interfaces, subsystem integration, redundancy and fault recovery.

### 2. Satellite Communications and Link Budget

The communications design investigates an S-band relay link between MOWI and Lunar Pathfinder.

Key analysis areas include:

- Spacecraft orbital geometry and contact windows
- Free-space path loss
- Antenna gain and transmitter power
- BPSK and QPSK modulation
- Forward error correction
- Link margins and adaptive data rates
- Daily data throughput limitations

The proposal investigates data transmission rates of 48.8 kbps, 256 kbps and 1 Mbps under different separation distances.

### 3. Electrical Power Subsystem

The electrical power design covers:

- Spacecraft operational power budgets
- Battery capacity and depth-of-discharge considerations
- Solar array sizing
- Beginning-of-life and end-of-life performance
- Power conditioning and distribution
- Fault protection and component resilience

### 4. Onboard Computing and Data Handling

The onboard computing investigation considers:

- Radiation-tolerant processor selection
- LIDAR data processing
- Data storage requirements
- Compression and downlink constraints
- Avionics interfaces
- Memory reliability in the lunar radiation environment

### 5. Mission Operations and Requirements

The proposal defines three operational modes:

1. Nominal operations
2. Payload collection
3. Data downlink

Mission and subsystem requirements are documented alongside assumptions, operational constraints and component trade-offs.

## Engineering Methods

- Spacecraft subsystem architecture development
- Requirements analysis and traceability
- Communications link-budget calculations
- Mission geometry assessment
- COTS versus space-grade hardware trade studies
- Subsystem interface assessment
- Power and data-budget analysis
- Reliability and fault-tolerance considerations

## Repository Contents

- `documentation/` — Technical avionics proposal
- `figures/` — Selected spacecraft architecture and operational diagrams
- `README.md` — Project overview

## Project Scope

This repository documents an academic, conceptual spacecraft avionics design study.

It is a systems engineering and technical analysis project rather than a software implementation or flight-validated spacecraft design.

The work was completed as a group project, with contributions covering multiple spacecraft subsystems.

## Author

Mehwish Akram

MSc Astronautics & Space Engineering
