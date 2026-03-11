# LTspice Simple Resistive Voltage Divider

## Overview

This project demonstrates the simulation of a **simple resistive voltage divider** using **LTspice**.
The circuit consists of two resistors connected in series with a DC voltage source. The purpose of this simulation is to observe how the input voltage is divided between the two resistors.

The simulation follows the instructions from the **LTspice Reference Book (Example 1: Simple Resistive Voltage Divider)** and runs a transient analysis over a **0 to 100 ms time interval**.

---

## Circuit Description

The circuit contains the following components:

* **V1** – DC Voltage Source (10 V)
* **R1** – 1 kΩ Resistor
* **R2** – 1 kΩ Resistor
* **Ground**

The resistors form a **voltage divider**, which splits the input voltage across the two resistors.

### Voltage Divider Formula

The output voltage is calculated using:

Vout = Vin × (R2 / (R1 + R2))

Substituting the component values:

Vout = 10 × (1k / (1k + 1k))
Vout = 5 V

---

## Simulation Settings

* **Simulation Type:** Transient Analysis
* **Time Range:** 0 ms to 100 ms
* **LTspice Command:**
  .tran 100m

---

## Files Included

This repository contains the following files:

* **voltage_divider.asc** – LTspice schematic file
* **schematic.png** – Screenshot of the LTspice circuit schematic
* **simulation.png** – Screenshot of the simulation waveform results

---

## Simulation Result

The simulation confirms that the voltage at the node between **R1** and **R2** is approximately **5 V**, which matches the theoretical calculation for a voltage divider with equal resistors.

---

## Software Used

* **LTspice** – Circuit simulation software by Analog Devices
* **GitHub** – Version control and repository hosting

---

## Author

Student submission for LTspice circuit simulation assignment.
