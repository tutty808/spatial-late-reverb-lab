# spatial-late-reverb-lab

This repository is a research-oriented Python project for analyzing, generating, and replacing late reverberation in room impulse responses.

The long-term goal is to study how late reverberation can be controlled by changing parameters such as decay time, energy distribution, and binaural correlation.

## Motivation

This project is related to my master's research on late reverberation generation and replacement using binaural or spatial room impulse responses.

Late reverberation is important for perceived reverberance, spaciousness, and the impression of an acoustic space.  
This project aims to build a reproducible implementation for modifying late reverberation and evaluating the resulting changes.

## Current Goal

The first goal is to build a simple analysis pipeline that:

1. loads a room impulse response,
2. separates early and late parts,
3. computes the energy decay curve,
4. estimates reverberation time,
5. compares original and generated late reverberation.

## Planned Features

- RIR / BRIR / SRIR loading
- Early and late reverberation separation
- Energy decay curve calculation
- T20 / T60 estimation
- Late reverberation synthesis
- Late reverberation replacement
- Directional energy control
- Binaural metrics such as IACC
- PyTorch-based parameter optimization

## Status

Work in progress.
