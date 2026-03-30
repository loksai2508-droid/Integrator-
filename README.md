## Experiment No: 4
INTEGRATOR USING OP-AMP (μA741)
## Aim
To design and simulate an Integrator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the integral of the input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R = 10 kΩ
•	Capacitor Cf = 0.01 µF
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1919" height="1149" alt="Screenshot 2026-02-02 091452" src="https://github.com/user-attachments/assets/828e6e6c-055d-4254-b43b-c0163b6c5790" />

## Connection Details:
•	Input signal → Resistor (R) → Inverting terminal (Pin 2)
•	Feedback capacitor (Cf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
An Integrator circuit produces an output voltage proportional to the integral of the input voltage.
## Working Principle:
•	When input is constant → output is ramp signal
•	Output is inverted
•	Output depends on time
For Sine Wave Input:
•	Output lags input by 90°
•	Output amplitude decreases with frequency
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistor, capacitor, signal generator, and CRO.
3.	Connect circuit in integrator configuration.
4.	Apply ±15V power supply.
5.	Set input waveform (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
S.No	           Input Signal	 Frequency	      Expected Output	               Practical Observation
| S.No | Input Signal        | Frequency | Expected Output              | Practical Observation                                  |
| ---- | ------------------- | --------- | ---------------------------- | ------------------------------------------------------ |
| 1    | Sine Wave           | 100 Hz    | Cosine wave (leads by 90°)   | Output leads input by ~90°, slight amplitude variation |
| 2    | Triangular Wave     | 100 Hz    | Square wave                  | Nearly square waveform observed                        |
| 3    | Square Wave         | 100 Hz    | Positive and negative spikes | Sharp spikes at rising and falling edges               |
| 4    | High Frequency Sine | >100 Hz   | Increased amplitude          | Slight distortion due to high-frequency gain           |

## Waveforms
<img width="1743" height="1132" alt="Screenshot 2026-02-02 090436" src="https://github.com/user-attachments/assets/45c9c68a-30c9-4d80-a3fd-d6b4fbf06efa" />
<img width="1919" height="1145" alt="Screenshot 2026-02-02 090740" src="https://github.com/user-attachments/assets/0ec5ed43-5804-410c-8369-6baa7508b7cc" />
<img width="1919" height="1145" alt="Screenshot 2026-02-02 090836" src="https://github.com/user-attachments/assets/b8d46816-d7fb-4bd7-b426-419121790e8b" />


## Result
The Integrator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the integral of the input signal.
The circuit behaves as an integrator.
## Conclusion
•	Output lags input by 90° (for sine input).
•	Output amplitude decreases with increase in frequency.
•	Used in waveform generation and analog computation.
## Viva Questions
1.	What is an integrator circuit?
2.	Write the output equation of integrator.
3.	Why does output lag input?
4.	What happens at very low frequency?
5.	What is practical integrator?
## Answers
1. An integrator is an op-amp circuit that produces an output voltage proportional to the integral (area under the curve) of the input voltage.
2. <img width="268" height="64" alt="image" src="https://github.com/user-attachments/assets/1a64a91c-af3f-44b2-a4bb-ae34db0d8e6d" />
3. Because integration of a sine wave produces a negative cosine wave, resulting in a 90° phase lag. Hence, output lags input.
4. At very low frequency, gain becomes very high, which may cause output saturation and drift.
5. A practical integrator includes a resistor in parallel with the feedback capacitor to reduce low-frequency gain and prevent saturation.




