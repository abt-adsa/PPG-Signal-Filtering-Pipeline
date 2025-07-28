# PPG Signal Filtering Pipeline

MATLAB script for filtering photoplethysmography (PPG) signals and calculating heart rate and SpO2 metrics.

The script processes synthetic PPG signals and reports:
- Heart rate (BPM) estimation
- SpO2 calculation
- Filter performance comparison
- Time and frequency domain plots

## Requirements

```
MATLAB R2018b or later
Signal Processing Toolbox
```

Install MATLAB with Signal Processing Toolbox.

## Usage

```matlab
mainScript
```

The script generates synthetic PPG signals, applies filtering, and produces:
- Console output with heart rate and SpO2 values
- Comparison plots of original vs filtered signals
- FFT analysis plots

The main pipeline applies moving average, median, notch (60Hz), bandpass (0.5-5Hz), and lowpass filters to extract clean PPG signals for metric calculation.
