# ligo-gw-analysis
Gravitational Wave Analysis - GW1501914

Reproducing the detection fo GW150914 using LIGO open data.
Includes signal processing, matched filtering, and chirp mass extermination.

Author: Van Jessup-Dascher
Summer 2026

Project Goals:
  - Detect GW150914 via matched filtering on LIGO strain data
  - Estimate chirp mass from frequency evolution
  - Produce publication-qaulity figures

Structure:
  - notebooks/ - Juptyer notebooks for each analysis stage
  - data/ strain data (not committed, see data access below)
  - figures/ output plots
  - writeup/ mini-paper PDF

Dependencies
numpy, scipy, matplotlib, gwpy, pycbc

Data access
Strain data from LIGO Open Science Center: gwosc.org