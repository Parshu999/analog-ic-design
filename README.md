# 🎤 MEMS Microphone Interface IC Design

This repository contains the design, simulation, and analysis of a MEMS microphone interface IC. The project includes:

- Modelled the MEMS microphone as a Thevenin equivalent source
- Designed an amplifier using an op-amp
- Created a high-pass filter
- Added a buffer stage
- Running simulations to verify the design


## 🎙️ Thevenin Equivalent Model Calculations

**SPL to Pressure Conversion:**

$$
\text{Pressure (Pa)} = 10^{\frac{60 - 94}{20}} = 19.95 \times 10^{-3} \, \text{Pa}
$$

**Output Voltage (Peak):**

$$
V_{\text{out (peak)}} = 2 \times 19.95 \times 10^{-3} \times 10^{\frac{-44}{20}} = \mathbf{0.178 \, \text{mV}_{\text{pk}}}
$$
### Schematic:

