# Spatial Late Reverberation Lab

This repository is a research-oriented Python project for analyzing, synthesizing, replacing, and controlling spatial late reverberation in room impulse responses.

The purpose is to investigate which physical properties of late reverberation should be preserved or controlled when generating or replacing late reverberation.

## Research Direction

Late reverberation is not only a decaying tail in time.  
In spatial and binaural room impulse responses, it also includes directional energy distribution, frequency-dependent decay, interaural correlation, and diffuseness.

This project explores how these properties can be analyzed, modified, and evaluated.

## Current Questions

- Is matching the energy decay curve sufficient for late reverberation replacement?
- How important is directional energy distribution in late reverberation?
- How does interaural correlation affect the perceived spatial impression?
- Can late reverberation be simplified while preserving important perceptual properties?
- Which objective metrics are useful for evaluating modified late reverberation?

## Initial Implementation Goals

1. Load RIR / BRIR / SRIR data.
2. Separate early and late parts.
3. Compute energy decay curves.
4. Estimate reverberation time.
5. Generate synthetic late reverberation.
6. Replace the original late part.
7. Compare original and modified responses using objective metrics and listening examples.

## Planned Extensions

- Directional energy control
- Direction-dependent decay control
- Frequency-dependent decay control
- Binaural metrics such as IACC
- Diffuseness or spatial coherence analysis
- PyTorch-based parameter optimization

## Status

Work in progress.
