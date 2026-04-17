# Graphs-of-Sine
Creating a full equation that models my Colpitts Oscillator sine wave.

Using my Colpitts Oscillator build. The frequency is 1 MHz. The mathematical form of a sin wave is y = Asin(𝜔x)
- Where A = Amplitude
- Where 𝜔 = Rotations
- Where x = Angle in radians

# Measured Waveform
<img width="2100" height="1576" alt="IMG_8678" src="https://github.com/user-attachments/assets/2da1270b-39c5-4803-b0af-6c53896026d3" />



- The signal from the oscillator represents a sine wave as the cycle starts at the orgin
- The voltage peak to peak is 2.72
- 960 kHz Frequency (Really 1MHz) samples are at 200ns
- Period = 1.040us


# Measurements
- Amplitude = 2.72 / 2 = 1.36
- 𝜔 = 2π / 1.040

# Model: y = 1.36sin(2π/1.040*x)
- y = 1.36sin(2π/1.040*x)

I was very curious to see what this looks like on y graphing calculator.
<img width="1576" height="2100" alt="IMG_8679" src="https://github.com/user-attachments/assets/651059fb-7c89-441a-8d74-cb109dd6a542" />
<img width="2100" height="1576" alt="IMG_8678" src="https://github.com/user-attachments/assets/78618244-5b06-47a6-a6a8-5a23bd4088ce" />


Both look very similar but my real one has some distortion around the peaks and slightly shifted to the right.



