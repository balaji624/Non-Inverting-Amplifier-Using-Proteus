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
<img width="875" height="471" alt="Screenshot 2026-02-23 091127" src="https://github.com/user-attachments/assets/0f8c6810-f66e-45e3-ab10-a9cbf826dcf8" />

Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
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
<img width="697" height="449" alt="lic exp2" src="https://github.com/user-attachments/assets/6271415c-7a8e-4674-8380-2ce935b3c1d9" />

## Tabulation
| S.No | Vin (V) | Theoretical Gain (Av) | Theoretical Vout (V) | Practical Vout (V) |
| ---- | ------- | --------------------- | -------------------- | ------------------ |
| 1    | 0.1     | +10                   | 1.0                  | ≈ 0.95             |
| 2    | 0.2     | +10                   | 2.0                  | ≈ 1.9              |
| 3    | 0.3     | +10                   | 3.0                  | ≈ 2.85             |
| 4    | 0.4     | +10                   | 4.0                  | ≈ 3.8              |
| 5    | 0.5     | +10                   | 5.0                  | ≈ 4.7              |

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1. What is a Non-Inverting Amplifier?
   ANS : A non-inverting amplifier is an op-amp circuit in which the input signal is applied to the non-inverting (+) terminal and the output voltage is amplified without phase inversion.
2. What is the gain formula?
   ANS : Av​=1+R1​/Rf​​
3. Why is output in phase?
   ANS : Because the input signal is applied to the non-inverting terminal, the output follows the same polarity as the input.
4. What happens if Rf increases?
   ANS : The voltage gain of the amplifier increases.
5. What is the input impedance of non-inverting amplifier?
   ANS : Very high (ideally infinite).

