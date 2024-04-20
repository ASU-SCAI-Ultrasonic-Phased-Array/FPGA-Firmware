# FPGA Firmware
These are files that can be programmed onto the FPGA

- [PrimaryCalib.jic](PrimaryCalib.jic) is the default calibrated file. It has no amplitude modulation, but amplitude can be modulated through animations on the Ultraino software.

- [TactileModulationCalib.jic](TactileModulationCalib.jic) is a calibrated file with amplitude modulation. We have not yet successfully created any noticeable haptic focal points using tactile modulation, but it should be possible, and may be preferable to using [PrimaryCalib.jic](PrimaryCalib.jic) if set up correctly.

- [FPGAPrimaryNoCalib.jic](FPGAPrimaryNoCalib.jic) is the default file with no calibration, from SonicSurface (<https://github.com/upnalab/SonicSurface/blob/main/Firmware/FPGAPrimaryNoCalib.jic>).

- [FPGATactileModulation.jic](FPGATactileModulation.jic) is the default file with no calibration which is supposed to be used for tactile feedback, from SonicSurface (<https://github.com/upnalab/SonicSurface/blob/main/Firmware/FPGATactileModulation.jic>). We have not yet successfully created any noticeable haptic focal points using tactile modulation.
