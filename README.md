# Audio-Feature-Analysis
This repository contains of analyzing and visualizing key audio features from sound recordings, including MFCC, Spectrogram, and Beat Tracking. It leverages Python libraries to extract and plot these features, providing insights into audio characteristics.

# Audio Feature Analysis Assignment
## Overview
This repository contains an assignment focused on analyzing and plotting key audio features from sound recordings. The aim is to derive meaningful insights from various audio representations that are essential in fields like speech processing and music analysis.

## Features Analyzed
The following audio features are analyzed and plotted:

- **MFCC (Mel-Frequency Cepstral Coefficients)**: Captures the power spectrum, crucial for speech processing.
- **Spectrogram**: Visualizes the evolution of frequency content over time.
- **Chromagram**: Shows the energy distribution across pitch classes, aiding in harmonic analysis.
- **Mel Spectrogram**: Scales frequencies based on human perception, highlighting important sounds.
- **Short-term Fourier Transform (STFT)**: Examines frequency changes in non-stationary signals.
- **Beat Tracking**: Identifies rhythmic patterns and tempo in music.
- **Constant-Q Transform (CQT)**: Provides enhanced frequency resolution for musical analysis.

## Requirements
- Python 3.x
- Libraries: `librosa`, `numpy`, `matplotlib`, and `IPython`

You can install the required libraries using pip:

```bash
pip install librosa numpy matplotlib
