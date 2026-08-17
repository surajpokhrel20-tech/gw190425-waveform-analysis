# GW190425 Waveform Analysis

### Bayesian Parameter Estimation and Waveform-Model Comparison for a Binary Neutron-Star Merger

A computational gravitational-wave data-analysis project focused on
**GW190425**, a binary neutron-star merger observed during the
LIGO/Virgo O3 observing run.

The project investigates how the choice of gravitational-wave waveform
model affects the inferred astrophysical parameters and their
uncertainties.

---

## Overview

This project applies a complete gravitational-wave data-analysis
workflow, from publicly available detector data to Bayesian parameter
estimation and posterior analysis.

The analysis includes:

- Gravitational-wave data retrieval and preprocessing
- Time-domain and frequency-domain signal analysis
- Noise characterization and power spectral density (PSD) estimation
- Q-transform and Fourier-transform analysis
- Matched filtering
- Bayesian parameter estimation
- Nested sampling
- Posterior analysis and visualization
- Comparison of different waveform models

The primary scientific focus is the dependence of inferred binary
neutron-star parameters on the waveform model used in the analysis.

---

## Scientific Objectives

The main objectives are to:

1. Analyze publicly available gravitational-wave data for GW190425.
2. Identify and characterize the gravitational-wave signal.
3. Estimate astrophysical parameters using Bayesian inference.
4. Compare parameter-estimation results obtained using different
   waveform models.
5. Investigate waveform-model dependence of the inferred parameters.
6. Compare the results with published analyses of GW190425.

---

## Event

| Property | Description |
|---|---|
| Event | GW190425 |
| Source | Binary neutron-star merger |
| Observing run | LIGO/Virgo O3 |
| Analysis | Bayesian parameter estimation |
| Main investigation | Waveform-model dependence |

---

## Waveform Models

The analysis considers the following waveform models:

- **IMRPhenomPv2**
- **TaylorF2**
- **SEOBNRv4T_surrogate**

These models are used to investigate how waveform-model selection
influences the inferred properties of the binary neutron-star system.

---

## Analysis Workflow

```text
Public GW Data
      │
      ▼
Data Retrieval & Preprocessing
      │
      ▼
Time-Frequency Analysis
      │
      ├── Q-transform
      └── Fourier Transform (FFT)
      │
      ▼
Noise Characterization
      │
      └── PSD Estimation
      │
      ▼
Matched Filtering
      │
      ▼
Bayesian Parameter Estimation
      │
      └── Nested Sampling
      │
      ▼
Posterior Analysis
      │
      ├── Parameter Marginalization
      └── Corner Plots
      │
      ▼
Waveform-Model Comparison
      │
      ▼
Comparison with Published Results
