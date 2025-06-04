# OSC2
This is a 2 oscillator synth, created in HISE.
The documents contained here are what's required for the GPL v3 open-source license to share, sell, distribute.

The synth has 2 Waveform Generators that contain multiple oscillators

1.	Sine:		a sinusoidal curve

2.	Triangle"		a triangular waveform

3.	Saw:		a sawtooth waveform (only odd harmonics)

4.	Square:		a square waveform. You can adjust the pulse with with the PulseWidthX attributes

5.	Noise:		white noise

6.	Triangle 2:		a variation of the triangle waveform

7.	Square 2:		a variation of the square waveform

8.	Trapezoid 1:		a variation of the saw waveform

9.	Trapezoid 2:		a variation of the saw waveform

The Generator parameters are as follows. 

Parameters:
4	OctaveTranspose1	The octave shift for the first oscillator
5	WaveForm1	the waveform of the first oscillator
6	Detune1	Detunes the first oscillator
7	Pan1	Pans the first oscillator
8	OctaveTranspose2	The octave shift for the second oscillator
9	WaveForm2	the waveform of the second oscillator
10	Detune2	Detunes the second oscillator
11	Pan2	Pans the second oscillator
12	Mix	The balance between osc1 and osc2
13	EnableSecondOscillator	Turn the second OSC on and off
14	PulseWidth1	Changes the pulse of the OSC1 Square and Trapezoid oscillator
15	PulseWidth2	Changes the pulse of the OSC12 Square and Trapezoid oscillator
16	HardSync	-
17	SemiTones1	-
18	SemiTones2	-

