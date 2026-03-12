
# Diode Circuit Simulation

## Name(s)
- Name: MD Shahriar Fardin Protya
## Sweep Range / Step
- Simulation type: Transient analysis
- Time range: **0 ms – 40 ms**
- Input signal: `SINE(0 100 50)`
  - Offset: 0 V
  - Amplitude: 100 V
  - Frequency: 50 Hz

## Circuit Description
The circuit consists of:
- Two diodes (**D1, D2**)
- Three resistors (**R1, R2, R3**, each 2.2 kΩ)
- A sinusoidal voltage source (**V1**)

The output voltage **Vout** is measured at the node after the diodes and resistor network. The simulation plots:
- **Vin** (input voltage)
- **Vout** (output voltage)

## Behavior Analysis

The plot shows two waveforms:

- **Green waveform:** Input voltage `Vin`
- **Blue waveform:** Output voltage `Vout`

### Observations

1. **Input Signal**
   - A sinusoidal waveform with **100 V peak amplitude**.
   - Frequency of **50 Hz**.

2. **Output Signal**
   - The output waveform has a **smaller amplitude than the input**.
   - This occurs because the signal passes through **two diodes and the resistor network**, which causes voltage drops and attenuation.

3. **Diode Operation**
   - The diodes conduct only when they are **forward biased**.
   - When the input voltage exceeds the diode threshold, current flows through the diodes and resistors toward the output node.

4. **Voltage Reduction**
   - The resistors **R1, R2, and R3** form a voltage divider.
   - This reduces the amplitude of the output waveform compared to the input waveform.

5. **Overall Effect**
   - The circuit behaves like a **diode-controlled attenuator**.
   - The waveform shape remains sinusoidal, but its **amplitude is reduced** due to diode drops and resistive division.

## Conclusion
The simulation demonstrates how diodes and resistors affect signal amplitude. The output voltage follows the input waveform but with reduced magnitude due to diode conduction characteristics and the resistor network acting as a voltage divider.
