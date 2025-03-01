# Multipath Rayleigh Channel with Different Doppler Frequencies

## Introduction
Rayleigh fading is a statistical model that describes how radio signals propagate in an environment with multiple paths between a transmitter and a receiver. The presence of multiple paths causes signal variations due to constructive and destructive interference.

This project models a **Multipath Rayleigh Channel** with different **Doppler frequencies** using MATLAB and Python simulations. The impact of Doppler shift on received signal power and spectral density is analyzed.

## Features
- Simulation of **Rayleigh fading** in a multipath channel
- Implementation in both **MATLAB** and **Python**
- Analysis of **Power Spectral Density (PSD)** for different Doppler shifts
- Avoids division-by-zero errors using a small epsilon for numerical stability

## Implementation Details
### MATLAB Code
- Simulates a Rayleigh fading channel with multiple Doppler frequencies
- Uses **Fast Fourier Transform (FFT)** to analyze frequency response
- Generates **Power Spectral Density (PSD) plots**
- MATLAB script available in `rayleigh_fading.m`

### Python Code
- Implements the MATLAB simulation in **NumPy & Matplotlib**
- Generates **PSD plots** for different Doppler frequencies
- Python script available in `rayleigh_fading.py`

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/multipath-rayleigh.git](https://github.com/ApoorvaN1701/Multipath-Rayleigh-Channel.git)
   cd multipath-rayleigh
   ```

2. **For MATLAB:**
   - Open `rayleigh_fading.m` in MATLAB
   - Run the script to generate PSD plots

3. **For Python:**
   - Install dependencies:
     ```bash
     pip install numpy matplotlib
     ```
   - Run the script:
     ```bash
     python rayleigh_fading.py
     ```

## Results & Observations
- The **power spectral density (PSD)** varies for different Doppler shifts.
- Higher **Doppler frequencies** result in greater spectral broadening and more severe signal fading.
- The project provides insights into wireless **channel modeling** and **fading effects** in communication systems.

## References
- MATLAB Central File Exchange
- Electronics Notes on Rayleigh Fading
- ScienceDirect on Doppler Frequency Shift

## License
This project is open-source and available under the MIT License.
