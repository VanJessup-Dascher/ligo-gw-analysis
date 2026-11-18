# Reproducing GW150914 from LIGO Open Data
Independent project reproducing the first direct detection of gravitational waves from raw LIGO strain data

**Author** Van Jessup-Dascher, Physics, University of Minnesota - Twin Cities
**Started:** Summer 2026

<img width="1176" height="926" alt="download" src="https://github.com/user-attachments/assets/2d6f25f9-77ce-4dea-8914-cea3113c20e1" />

## Completed
- Implemented the discrete Fourier transform from scratch to build intuition
- Estimated detector noise (PSD) using Welch's method
- Whitened H1 strain data using ASD with a Hann window
- Applied a 35-350 Hz Butterworth bandpass filter, which reveals the GW150914 chirp

## In Progress
- Matched filtering with pyCBC
- Chirp mass estimation from the signal's frequency evolution
- Publication-quality figures and a short paper-style writeup

## Repository Structure 
- [`notebooks/01_fourier_transform_basics.ipynb`](notebooks/01_fourier_transform_basics.ipynb): Fourier transform fundamentals
- [`notebooks/02_gw150914_analysis.ipynb`](notebooks/02_gw150914_analysis.ipynb): noise estimation, whitening, filtering
- [`Figures/`](Figures/): important plots and figures

## How To Run
pip install numpy scipy matplotlib gwpy pycbc
Data files are not committed; the notebooks download them directly
