# Mehdi Belhaj

**Power Electronics & Hardware Engineer** - Toulouse, France
SiC inverters - DO-160G EMC - DAL A - embedded C/C++/Python

3 years designing high-voltage boards for aerospace (Safran, Airbus, SuperGrid
Institute): 270 VDC conversion, SiC 1200 V - 10 kW, EMC filtering and
qualification testing. I automate the software side of the bench in Python and
write embedded-grade C++.

**Pinned projects**
- [`hardware-design-kit`](https://github.com/mehdi-belhaj-eea/hardware-design-kit) - power-side design
  calculators: input protections (precharge, lightning/TVS per DO-160G Section 22, ESD, hold-up), EMI
  filter with Middlebrook check, flyback and transformer (iGSE, Dowell), measurement error budgets,
  PCB rules (IPC-2221, IEC 60664-1); cross-checked against ngspice (PyTest, CI).
- [`bldc-control-sim`](https://github.com/mehdi-belhaj-eea/bldc-control-sim) - BLDC / PMSM motor
  control from the model to the embedded code: switched-inverter simulation (dead time, diodes), FOC
  and six-step control tuned by the modulus and symmetrical optimum, C99 controller for Cortex-M4F
  run in the loop against its Python reference (PyTest, CI).
- [`scope-emi-toolkit`](https://github.com/mehdi-belhaj-eea/scope-emi-toolkit) - oscilloscope CSV
  parsing + dBuV spectrum + generic conducted-emissions pre-check (PyTest, CI).
- [`embedded-dsp-cpp`](https://github.com/mehdi-belhaj-eea/embedded-dsp-cpp) - header-only ring
  buffer & digital filters, C++17/STL, GoogleTest, CMake, CI.

[LinkedIn](https://linkedin.com/in/mehdi-belhaj-eea) - belhaj.elmehdi.98@gmail.com
