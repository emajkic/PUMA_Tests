## Repository for PUMA/little PUMA Testing Phase
*By Ella Majkic - TRIUMF Co-Op Jan-Apr 2025*

A **purity monitor assembly (PUMA)** is needed for experiments such as PIONEER, nEXO, and LolX to measure the amount of impurity in liquid xenon (LXe). This is improtant for precise measurement as these impurities will affect the light yield in LXe based scintillators. For example, PIONEER is a rare pion decay experiment measuring $R_{e/ \mu}$, the ratio between pion ($\pi^{+}$) decay to positron ($e^{+}$) and pion decay to muon ($\mu^{+}$):

$$R_{e/ \mu} = \frac{\pi^{+} \rightarrow e^{+}\nu_{e}(\gamma)}{\pi^{+} \rightarrow \mu^{+}\nu_{\mu}(\gamma)} $$

Measurement of $R_{e/ \mu}$ informs potential new physics realted to the current Standard Model and addresses unanswered questions in the flavour sector. PIONEER uses a LXe calorimeter to detect scintillation light produced by energy deposit - the purity of the LXe affects this scintillation and must be known for precise measurement.


It is necessary to calibrate PUMA by experimentally determining the transparency of the grids mounted in the assembly. To this end, a small version of PUMA ("Little PUMA") was developed. Little PUMA allows for calibration of PUMA in various media by measuring the grid transparency of the device. 

The goal of the testing phase was to analyze the function of little PUMA in vacuum and gas as well as create simulations regarding particle interactions in PUMA.

This repository contains:

- Simulations with COMSOL model of PUMA (Purity Monitor Assembly) using the Garfield++ library to gain insight about how electrons drift in PUMA;

- Images and setup of vacuum system designed for PUMA calibration assembly tests;

- Schematic for electrical box used to connect vacuum pressure gauge to data collection devices.
