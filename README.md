# Dispersion scan LABVIEW program
I have made LABVIEW program for acquiring dispersion scan trace using ESP301 Newport stage and HR4000 USB spectrometer from OceanOptics. 

Following files included and it's necessary to run the VI.
1. Labview driver and Firmware for ESP301 controller from Newport.
2. LABVIEW project file

## What is Dipsersion scan method?

Measuring ultrashort pulse is one of the great challenge in ultrafast laser community. There are several methods to measure the pulse duration, i.e, 2-nd order autocorrellation, FROG, SPIDER. These methods are sufficient enought to measure few cycle pulse duration. However, when the pulse duration is close to single cycle then the previous methods are not sufficient enough due to nonlinear medium effect and geometrical issues. Dispersion scan is a simple and easy method characterizing near single cycle pulse. It is based on the introduction of a known amount of dispersion (by controlling the amount of dispersive material) and subsequent recording of the spectral positions of second harmonic peaks obtained in a non-linear crystal. Such dependence allows for direct retrieval of the pulse spectral phase. 

