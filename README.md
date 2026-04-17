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

curious to see what this looks like on my graphing calculator.
<img width="1576" height="2100" alt="IMG_8679" src="https://github.com/user-attachments/assets/651059fb-7c89-441a-8d74-cb109dd6a542" />
<img width="1576" height="2100" alt="IMG_8681" src="https://github.com/user-attachments/assets/4ec0d388-3545-4333-b7a4-57a2eaf1dd41" />
<img width="2100" height="1576" alt="IMG_8680" src="https://github.com/user-attachments/assets/82a90f6e-030a-4fd6-b337-766d2e44b24d" />


Both look very similar but my real one has some distortion around the peaks and slightly shifted to the right. The second calulator photo is zoomed in about the orgin.
- Domain is all real numbers
- Range is [-1.36,1.36]


# Common Emitter Amplifier
I probed the signal coming out of the amplifer. You can see the inversion of the two signals.
- Common Emitter Output (Blue), Feedback loop (Yellow)

<img width="2100" height="1576" alt="IMG_8684" src="https://github.com/user-attachments/assets/3694a538-5707-48bf-ac52-d94e1930acfb" />

- 4.20V Peak to peak voltage
- 961Khz
- Period 1.040us


Since its an inversion, the graphis flipped over the x axis so y is negative.
- Amplitude = 4.20/2 = 2.10
- Period 1.040us
- 𝜔 = 2π / 1.040

# Model: y = -2.10sin(2π / 1.040*x)
- y = -2.10sin(2π / 1.040*x)

<img width="2100" height="1576" alt="IMG_8687" src="https://github.com/user-attachments/assets/e3abf361-de00-4e45-bb4b-7e9d38ac824e" />
<img width="1576" height="2100" alt="IMG_8686" src="https://github.com/user-attachments/assets/85344115-4752-445c-98ab-de7fafb2b50c" />
<img width="1576" height="2100" alt="IMG_8685" src="https://github.com/user-attachments/assets/ee03305d-6606-4e2e-8ddd-4bbb2a2d3c87" />


- Domain = All real Numbers
- Range [-2.10, 2.10]


The signals look roughly the same but not exactly. It shows a similar pattern but the real signals are more distorted around the edges. It is really cool to see everything come together. 






