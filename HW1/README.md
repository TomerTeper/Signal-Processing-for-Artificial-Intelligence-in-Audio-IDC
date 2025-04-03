# Homework 1 - Understanding Sound

## Assignment Overview
- Reconstruct a unique `.wav` audio file using sinusoidal wave synthesis.
- Analyze the signal using waveform plots and spectrograms.
- Gain practical experience in audio signal processing using tools like NumPy, Matplotlib, and Librosa.
- The original audio is made up of sine waves with different frequencies and amplitudes, each lasting between 3 to 7 seconds.

## Key Topics Covered
- Waveform synthesis using sine functions  
- Audio signal manipulation with NumPy  
- Visualizing waveforms and spectrograms  
- Frequency and amplitude matching  
- Working with audio files (`.wav`) in Python  
- Use of Librosa for time-series and frequency analysis

## What I Did
- Loaded and listened to my unique audio file from the shared Google Drive folder.
- Reconstructed the signal by iteratively generating sine waves with estimated frequencies and amplitudes.
- Aligned wave segments based on time to match the original.
- Visualized and compared the original and reconstructed audio using:
  - Waveform plots (`librosa.display.waveplot`)
  - Spectrograms (`librosa.stft`, `matplotlib.pyplot.specgram`)
- Validated the reconstruction by listening and visually inspecting similarity between the original and synthesized signals.

## Notes
- Frequencies start exactly at the beginning of each second.
- Amplitudes used were one of: 0.5, 1, 1.5, 2, or 2.5.
- Helpful Librosa docs used:
  - [Waveplot](http://librosa.org/doc/0.8.1/generated/librosa.display.waveplot.html)
  - [STFT](https://librosa.org/doc/main/generated/librosa.stft.html)
