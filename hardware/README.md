# Hardware

This directory contains the hardware documentation for KiwiSense V1.

## Contents

- GPIO Mapping
- Wiring Diagram
- System Architecture
- Sensor Connections

---

## System Architecture

![System Architecture](architecture.png)

---

## Wiring Diagram

![Hardware Wiring](wiring_diagram.png)

---

## GPIO Mapping

See [gpio_mapping.md](hardware/pin_mapping.md) for complete GPIO assignments.

## Software Flow

The firmware continuously reads all sensors, updates the OLED, uploads telemetry to the cloud, waits for the configured interval, and repeats.

![Software Flow](docs/hardware/flowchart.png)
