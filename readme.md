# W3MBG / Uno-LFO
## A quick and dirty 8-bit sine generator for Arduino / AVR

- Frequency range of 250 Hz - 1000 Hz
- R2R Ladder construction

Uno-LFO is an extremely basic sine wave generator I'm working on for testing low-frequency AC circuits in my home lab.  Running on Arduino's 16Mhz clock it can generate frequencies between 250 and 1000 Hz.  The frequency could be decreased by using a prescaler, or increased by reducing the bit depth of the converter.  