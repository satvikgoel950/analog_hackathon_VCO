# analog_hackathon_VCO
Final Submission for Analog Hackathon
# Abstract
The control system PLL generates an output oscillation generally used as clock and the prime element of that system is a voltage controlled oscillator (VCO) (Razavi 1997). In this report we are going to see a similar kind of vco which is designed using CS amplifier.
# About the circuit
The circuit comprises of 5 stages of cascaded CS amplifier based ring structure to provide full swing oscillation with high frequency and better tuning range. The PMOS transistor acts as an active load whose values are varied by the bias voltage provided by the bias circuit. The control voltage makes the transistor to switch from cut-off region to saturation region, lowering the bias voltage. The change in Vbias bring changes in the resistance of active load and hence changing the frequency.
# Tool Used
Synopsys tools have been used for creating and simuating the circuit.
# Circuit
![Screenshot (186)](https://user-images.githubusercontent.com/60666893/156043447-c4be324c-2225-4f21-a327-f74bf830f177.png)
# Circuit Output Waveform(for Vctrl@1V)
![Screenshot (183)](https://user-images.githubusercontent.com/60666893/156043687-c70819a6-4c71-447e-a639-54ba6627fc3e.png)
# Acknowledgement
Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
Cloud Based Analog IC Design Hackathon
Synopsys India
# Reference
Suraj Kumar Saw, Sandeep Kumar Yadav, Madhusudan Maiti, Abir Jyoti Mondal, Alak Majumder(May 31, 2019) “A design approach of higher oscillation VCO made of CS amplifier with varying active load”.
