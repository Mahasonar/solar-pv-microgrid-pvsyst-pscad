# Grid-Connected Rooftop Solar PV Microgrid Design and Simulation

## Project Overview

This project presents the design, verification, and simulation of a three-phase grid-connected rooftop solar PV system for a residential application. The system was designed based on available rooftop area, PV module specifications, inverter constraints, solar irradiation data, and household load demand.

The designed system was verified using PVSyst and modelled in PSCAD/EMTDC as a grid-feeding PV source with MPPT control, DC-DC boost conversion, DC-link regulation, and three-phase inverter grid integration.

## Key Features

- Designed a 26.4 kWp rooftop solar PV system.
- Selected 88 monocrystalline PV modules rated at 300 W each.
- Sized and validated a Huawei SUN2000-20KTL-M5 grid-connected inverter.
- Calculated string configuration, DC/AC ratio, voltage limits, and current limits.
- Estimated monthly and annual energy generation using irradiance and derating factors.
- Verified the design using PVSyst simulation.
- Modelled the PV system in PSCAD/EMTDC as a grid-feeding source.
- Analysed PV voltage, PV current, DC-link voltage, inverter output, grid power flow, and MPPT response.

## System Specifications

| Parameter | Value |
|---|---|
| PV System Capacity | 26.4 kWp |
| PV Module Rating | 300 W |
| Number of Modules | 88 |
| String Configuration | 4 strings × 22 modules |
| Inverter | Huawei SUN2000-20KTL-M5 |
| Inverter Rated AC Power | 20 kW |
| DC/AC Ratio | 1.32 |
| MPPT Method | Perturb and Observe |
| Simulation Tools | PVSyst, PSCAD/EMTDC |

## Tools and Software

- PVSyst
- PSCAD/EMTDC
- Global Solar Atlas
- Microsoft Excel
- PV system design calculations

## Repository Structure

```text
report/      - Final project report
pvsyst/      - PVSyst reports, screenshots, and project files
pscad/       - PSCAD simulation files and input profiles
results/     - Simulation output graphs
docs/        - Datasheets and supporting documents
