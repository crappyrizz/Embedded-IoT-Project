# ICS 4111 – Embedded Systems & IoT

## Semester Project – Deliverable 2

### Embedded Device Prototypes Using ESP32

---

**Institution:** Strathmore University

**Group:** Group 1: The Resistance

---

## Team Members

- Edgar Kareithi – 164951
- Mohamed Bile – 152802
- Evans Mwendwa – 166997
- Annejoy Warigi – 169915
- Tim Hubert – 166070
- Hope Murimi – 150468
- Martha Muinde – 166319

---

## Project Overview

This repository contains the implementation of the Semester Project, Deliverable 2 for the ICS 4111 Embedded Systems & IoT course. The project focuses on the design, implementation, and testing of embedded system prototypes using ESP32 microcontrollers and various sensors through both physical hardware and Wokwi simulations.

The prototypes demonstrate sensor integration, communication between ESP32 devices, environmental monitoring, gas detection, relay control, and LCD output. Each prototype is documented with its architecture, implementation, source code, simulation link, output, and supporting evidence.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Prototype A](#prototype-a)
- [Prototype B](#prototype-b)
- [Prototype C](#prototype-c)
- [Prototype D](#prototype-d)
- [Challenges Encountered](#challenges-encountered)
- [Evidence of Group Work](#evidence-of-group-work)
- [Repository Structure](#repository-structure)
- [Conclusion](#conclusion)

  ---

# Prototype A
## Description

This prototype consists of one ESP32 microcontroller connected to an MQ-5 gas sensor, a DHT22 temperature and humidity sensor, and a 16×2 LCD display. The system continuously monitors environmental conditions and gas concentration, displaying the readings on the LCD while simultaneously sending the data to the Serial Monitor.

## Physical Prototype

![Prototype A Physical Circuit](images/physical-prototype-A.jpg)

## Wokwi Simulation

![Prototype A Wokwi Simulation](images/schematic-wokwi-A.png)

**Simulation Link:**

https://wokwi.com/projects/467714861679761409

## Source Code

The complete source code for Prototype A is available in:

`code/prototype A`

## Working Principle

1. The ESP32 initializes the DHT22 sensor, MQ-5 gas sensor, and LCD display.
2. The DHT22 measures temperature and humidity.
3. The MQ-5 detects gas concentration.
4. Sensor readings are processed by the ESP32.
5. The measured values are displayed on the LCD.
6. The same values are sent to the Serial Monitor for monitoring.

## Output

The prototype successfully displays temperature, humidity, and gas concentration readings on the LCD while transmitting the same information to the Serial Monitor.
