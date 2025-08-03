# Hyperspectral Signature Identification using Linear Unmixing with VCA and NNLS

This project presents a linear unmixing pipeline for hyperspectral image (HSI) analysis, aimed at identifying pure spectral signatures (endmembers) from mixed pixels in hyperspectral data. The approach integrates **Vertex Component Analysis (VCA)** for endmember extraction and **Non-Negative Least Squares (NNLS)** for abundance estimation.

## Key Features

- **Linear Unmixing Framework:** Decomposes mixed hyperspectral signals into their constituent endmembers and corresponding abundance maps.
- **Endmember Extraction using VCA:** Efficiently identifies pure spectral signatures present in the scene.
- **Abundance Estimation using NNLS:** Ensures physically meaningful (non-negative) abundance values for each pixel.
- **Dataset:** Applied and tested on the **Samson hyperspectral dataset**.
- **Performance Highlights:**
  - Successfully identified up to **5 distinct endmembers**.
  - Achieved **angular deviation as low as 1.23°** between estimated and true endmember spectra.
  - Attained a **Signal-to-Noise Ratio (SNR) of 32.33 dB**, indicating high unmixing fidelity.

## Applications

- Remote sensing
- Mineral exploration
- Agricultural monitoring
- Environmental analysis

This implementation provides a strong baseline for hyperspectral unmixing tasks and can serve as a foundation for more advanced models involving nonlinear mixing or deep learning approaches.
