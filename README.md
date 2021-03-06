# Frequency-Generator-Circuit
This Project has been created in partial fulfilment of the course Microprocessors and Interfacing at BITS Pilani.
# Problem Statement
This system is used to generate a Sine/Triangular/Square waveform of frequencies ranging from 10 Hz to 99KHz. Voltage is between 0-10V.On system power up the user has to configure the desired type of waveform (square/triangle/square), frequency and amplitude. To generate a Square Waveform
of Frequency 9.35 KHz the user has to press square key, followed by 1K Key- 9 Times, 1K Key – 4 Times, 100 Key –3 Times 10 Key- 5 Times. To select the Amplitude the user will have to press Amplitude key and then press the 1V key “n” number of times where “n” is the peak to peak amplitude of the waveform to be generated. (only integer values of output voltages needs to be generated).
# Assumptions
In order to reduce the design effort as well as to get the simplest design possible using the minimum amount of hardware while meeting all the restrictions specified by our problem statement, we have made the following assumptions:
1. The user does not press a key corresponding to a frequency more than 9 time.
2. Amplitude is entered by directly pressing the ‘1V’ key, those many number of times.
3. Once the signal of specific frequency is generated, the user cannot change the frequency or the amplitude or the waveform. The system must be reset to change them.
4. The user does not press more than one key at once.
5. User cannot choose to select two different waveforms before pressing the generate key. If user wants to change the waveform, the user can do so while the signal is being produced, by pressing the relevant key.
6. The triangle and sine waves are generated by using lookup tables and are therefore approximate.
7. At the location FFFF0H, where the instruction pointer points on RESET of microprocessor, there exists a JUMP statement leading to the start of the code.
# Design Process

**Components Used :**
1. 8086 (MICROPROCESSOR)
2. 2 X 6116 (RAM – 2K)
3. 2 X 2732 (ROM - 4K)
4. 2 X 74LS245 (OCTAL BUFFER)
5. 3 X 74LS373 (OCTAL LATCH)
6.74LS04 (NOT GATE)
7. 7432 (OR GATE)
8. 74LS138 (3:8 DECODER)
9. DIGITAL OSCILLOSCOPE
10. 8253 (PROGRAMMABLE INTERVAL TIMER)
11. 8284 (CLOCK GENERATOR)
12. 8255 (PROGRAMMABLE PERIPHERAL INTERFACE)
13. LM741 (OPAMP)
14. DACO830 (DAC)
15. 3X3 KEYPAD

**For Circuit Diagram, Flowchart and detailed methodology, refer to the report.**




