# Diode Model Comparison – LTspice

## Circuit Description

The circuit used in this simulation consists of a voltage source (V1), a 1 kΩ resistor (R1), and a diode (D1) connected in series to ground. A DC sweep was applied to the voltage source from −1 V to +1 V with a step of 0.01 V to observe the current–voltage behavior of the diode.

Two simulations were performed:
1. Ideal diode model
2. Real diode model (1N4148)

## Difference in Turn-On Voltage

The ideal diode begins conducting immediately when the voltage becomes positive. It assumes zero voltage drop across the diode. In contrast, the real diode (1N4148) requires approximately 0.6–0.7 V before significant current begins to flow. This voltage is known as the forward voltage drop.

## Difference in Current Behavior

In the ideal diode model, the current changes instantly from zero to conduction once the voltage becomes positive. The transition is abrupt. However, in the real diode model the current increases gradually and follows an exponential curve due to the physical properties of semiconductor junctions.

## Why Ideal Models Are Used

Ideal diode models simplify circuit analysis and make calculations easier. They allow engineers to understand the general behavior of circuits without complex mathematical equations.

## When Ideal Models Become Inaccurate

Ideal models become inaccurate when precise voltage levels or current values are required. Real circuits must consider forward voltage drop, leakage current, temperature effects, and non-linear behavior of semiconductor devices.
