# Wind Turbine Technical Specifications

## Overview

This document provides the technical specifications of the wind turbines used to generate the simulated power data included in this repository. The turbine models are part of experimental wind energy systems installed at Brazilian research facilities.

The power generation data available in this repository correspond to simulated turbine output calculated from wind speed measurements using the turbine power curve and operational parameters.

---

## Turbine – Serra (ES)

Location: Serra, Espírito Santo, Brazil
Installation type: Experimental wind turbine system
Temporal resolution of dataset: **15 minutes**

### Main Characteristics

Rated Power: 1 kWA 

Cut-in Wind Speed: **3.6 m/s**

Rated Wind Speed: XX m/s

Cut-out Wind Speed: XX m/s

Rotor Diameter: XX m

Hub Height: XX m

Generator Type: XX
Control System: XX

---

## Turbine – Santa Vitória do Palmar (RS)

Location: Santa Vitória do Palmar, Rio Grande do Sul, Brazil

Temporal resolution of dataset: **60 minutes**

### Main Characteristics

Rated Power: XX kW

Cut-in Wind Speed: **3.6 m/s**

Rated Wind Speed: XX m/s

Cut-out Wind Speed: XX m/s

Rotor Diameter: XX m

Hub Height: XX m

Generator Type: XX

---

## Power Generation Modeling

The simulated wind power values (`potencia_gerada`) were calculated using a mathematical turbine model based on wind speed measurements and turbine operational parameters.

The modeling approach approximates the turbine power curve and operational limits, allowing the generation of simulated wind power time series aligned with meteorological measurements.

---

## Notes

The datasets included in this repository combine:

* simulated wind turbine power output
* real meteorological measurements from weather stations

These combined datasets were used to develop machine learning models for wind power forecasting.

---
