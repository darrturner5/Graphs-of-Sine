# Graphs-of-Sine
Creating a full equation that models my Colpitts Oscillator sine wave.

Right now I am learning Trigonometry and the graphs of Sine and Cosine. I was curious to build my own model from a real life signal source.

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
<img width="1576" height="2100" alt="IMG_8681" src="https://github.com/user-attachments/assets/4ec0d388-3545-4333-b7a4-57a2eaf1dd41" />
<img width="2100" height="1576" alt="IMG_8680" src="https://github.com/user-attachments/assets/82a90f6e-030a-4fd6-b337-766d2e44b24d" />


Both look very similar but my real one has some distortion around the peaks and slightly shifted to the right. The second calulator photo is zoomed in about the orgin.



