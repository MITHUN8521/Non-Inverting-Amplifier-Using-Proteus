## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
<img width="764" height="524" alt="2 circuit" src="https://github.com/user-attachments/assets/a42e3c9d-2c89-4bfd-ad5d-d27d1b35fdb8" />

## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="1375" height="871" alt="2 waveform" src="https://github.com/user-attachments/assets/8de495ba-47e9-49db-a73c-805430946875" />

## Tabulation
S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)
<img width="590" height="287" alt="2 tabular" src="https://github.com/user-attachments/assets/1d148695-d40f-499a-84fb-6f312f9a9a05" />

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?
A **Non-Inverting Amplifier** is an op-amp circuit in which the **input signal is applied to the non-inverting (+) terminal**, and the output is fed back to the inverting (–) terminal through a feedback resistor.The output signal is **in phase** with the input signal.
2.	What is the gain formula?
The voltage gain of a non-inverting amplifier is:
A_v = 1 + \frac{R_f}{R_{in}}
Where:
( R_f ) = Feedback resistor
( R_{in} ) = Resistor connected to ground
3.	Why is output in phase?
The input is applied to the **non-inverting (+) terminal** of the op-amp.
Since there is **no phase inversion** in this configuration, the output follows the input.
Therefore, **phase shift = 0°**
Output and input rise and fall together.
4.	What happens if Rf increases?
 From the formula:
 A_v = 1 + \frac{R_f}{R_{in}}
 If ( R_f ) increases:
 Gain increases
 Output voltage increases
 Amplification becomes higher
5.	What is the input impedance of non-inverting amplifier?
The input impedance is **very high**.
Ideally infinite (because input is given to + terminal of op-amp). Practically, it is in **mega-ohms (MΩ)** range.

