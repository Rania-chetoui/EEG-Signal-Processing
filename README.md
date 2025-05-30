# EEG-Signal-Processing
This project focuses on the processing and analysis of EEG (Electroencephalogram) signals using Python. It includes filtering, spectral analysis using FFT, Welch's method, periodogram, and parametric spectral estimation methods (Yule-Walker and Burg).

## Dataset

The dataset used for this project is from Kaggle:  
[Complete EEG Dataset](https://www.kaggle.com/datasets/amananandrai/complete-eeg-dataset)

## Features

- Bandpass filtering of EEG signals (0.5 Hz to 45 Hz)
- Normalization and preprocessing of raw EEG data
- Power spectral density estimation using multiple methods:
  - FFT (Fast Fourier Transform)
  - Welch's method
  - Periodogram
  - Autoregressive models (Yule-Walker and Burg methods)
- Visualization of raw and filtered signals along with their spectral representations

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- scipy
- spectrum

Install dependencies via:

```bash
pip install numpy pandas matplotlib scipy spectrum
```
## Code Overview
The script reads EEG signal files in CSV format.

Applies a Butterworth bandpass filter.

Computes and plots spectral analyses using several methods.

Saves plots for further inspection.
