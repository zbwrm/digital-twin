# digital-twin
This repository is for the "digital twin" of the power converter my lab team is building in Power Electronics, Fall '21.

### Problems
- Vcomp calculation means that Vout is off by -200 to -600 mV.
- Clamp circuit does not account for rampant high-frequency ringing after rising edge of Vd.
- It's laid out kinda weird.

### Goals
- Implement autocalculation of clamp/snubber circuit given a frequency and a zeta value.
