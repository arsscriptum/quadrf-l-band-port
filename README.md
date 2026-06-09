# open-space-sdr L-band variant

Derivative of [open-space-sdr/main](https://github.com/open-space-sdr/main)
targeting **1-3 GHz operation** instead of the upstream 4.9-6 GHz C-band.

I have a personal Research&Development Project, in the field of microwaves RF.
Currently building a control module for a PA. Will future proof my system for other R&D
projects in the 1-Ghz - 6Ghz. I found this very interesting QuadRF project. I cannot
prevent myself from geeking out!

## Goals

1. My first goals is to support L-Band, in my power range.
2. My second is R&D in constructive&destructive interference and analysis of beam properties.

## 
- Target frequency band: L-band (1-2 GHz primary, extending to S-band as feasible)
- RF front-end designs scaled to longer wavelengths
- Antenna geometry recomputed for half-wavelength spacing at target bands
- Power level scaling notes for higher-power chains

## 
- FPGA-side beamforming software (frequency-agnostic)
- SoapySDR driver framework
- Calibration algorithms (QEC, SPSA)
- Systemd service architecture
- OpenOCD Pi 5 JTAG configuration

## Status

Currently analysis stage, scoping / RF chain design / antenna design / protope

[https://arsscriptum.ca](https://arsscriptum.ca)


