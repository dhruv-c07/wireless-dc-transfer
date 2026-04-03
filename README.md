# Wireless DC Power Transfer System for Emergency Charging

## Overview
A wireless DC power transfer system designed for emergency scenarios 
where AC power is unavailable — enables a battery to wirelessly charge 
DC-powered devices like mobile phones without any AC adapter.

## Current Status
- Hardware prototype built and tested
- LTspice simulation completed
- Current efficiency: ~25%
- Target efficiency: 50–60% (work in progress)

## How It Works
1. Wien Bridge oscillator generates ~6.6 kHz sine wave
2. Class AB push-pull stage drives the transmitter coil
3. LC resonant filter (tuned to ~6.8 kHz) enables wireless energy transfer
4. Full-wave bridge rectifier converts received AC back to clean DC output

## Planned Improvements
- Add permanent magnets to enhance flux linkage between coils
- Optimise coil geometry to reduce flux leakage
- Target: improve efficiency from ~25% to 50–60%

## Simulation Details
- Tool: LTspice
- Oscillation frequency: ~6.6 kHz
- Supply: ±15V
- Components: Op-Amp, 2N3904/2N3906, 1N5817 Schottky diodes

## Designer
Dhruv — B.Tech ECE, NIT Jalandhar
