# BeaconTXv1a
Small footprint Si5351a-based transmitter with TCXO reference, intended for flight / telemetry

This transmitter was designed to be a replacement for existing Si5351a based synthesizer breakout boards, for applications requiring small size, light weight and TCXO reference frequency stability. For flight telemetry from a supressure balloon, the board also incorporates static bleed resistors on the Clk0 and Clk1 outputs, which are intended to drive a dipole.

This module is a drop-in replacement for the synthesizer board used by Ken Daniel for his airborne beacon described here:  https://github.com/kenndaniel/K9YO_WSPR Benefits are that it saves about 2 grams of weight vs the Adafruit synth, and is more temperature stable.

