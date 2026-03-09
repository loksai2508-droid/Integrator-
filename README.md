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

<img width="1181" height="641" alt="image" src="https://github.com/user-attachments/assets/9a33f818-cb9b-45b0-8857-97c2df0457ae" />

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

| Sl. No | Input Voltage (Vin) | Time (ms) | Output Voltage (Vout) |
| ------ | ------------------- | --------- | --------------------- |
| 1      | +5 V                | 0 ms      | 0 V                   |
| 2      | +5 V                | 0.5 ms    | –2.5 V                |
| 3      | +5 V                | 1 ms      | –5 V                  |
| 4      | –5 V                | 1.5 ms    | –2.5 V                |
| 5      | –5 V                | 2 ms      | 0 V                   |
| 6      | +5 V                | 2.5 ms    | –2.5 V                |
| 7      | +5 V                | 3 ms      | –5 V                  |

## Waveforms

<img width="1372" height="871" alt="image" src="https://github.com/user-attachments/assets/46947497-9fd3-40f6-b141-08f1801c825a" />

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

Integrator Circuit: An op-amp circuit whose output is proportional to the integral of the input signal.

2.	Write the output equation of integrator.

Vout​=−RC1​∫Vin​dt

3.	Why does output lag input?

Why Output Lags Input: Because integration introduces a 90° phase lag for a sinusoidal input signal.

4.	What happens at very low frequency?

At Very Low Frequency: Gain becomes very high and the output may drift or saturate.

5.	What is practical integrator?

Practical Integrator: A modified integrator with a resistor in parallel with the capacitor to prevent drift and saturation at low frequencies.
