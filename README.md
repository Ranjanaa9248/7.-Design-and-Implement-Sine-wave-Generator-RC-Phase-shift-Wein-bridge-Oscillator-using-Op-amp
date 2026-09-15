# 7.-Design-and-Implement-Sine-wave-Generator-RC-Phase-shift-Wein-bridge-Oscillator-using-Op-amp
**Aim:**
To design and implement Sine-wave-Generator-RC-Phase-shift-Wein-bridge-Oscillato-using-Op-amp

**APPARATUS REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,3.3K,1.5K,33K,15K,1MΩ	2
7.	Capacitor	0.1 µF	3
8.	Connecting wires and probes	As required	


**THEORY:**

**RC PHASE SHIFT OSCILLATOR**

RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .

**WIEN BRIDGE**

A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
 

**DESIGN:**

**RC PHASE SHIFT OSCILLATOR**

fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1  > 10 R
R1 =10 R = 33 k.
Rf = 29R1=1MΩ


**WIEN BRIDGE OSCILLATOR**

Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ


**PROCEDURE:**

1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.


  **CIRCUIT DIAGRAM**
<img width="437" height="237" alt="image" src="https://github.com/user-attachments/assets/4a2af3f2-3876-4982-989f-7ea8f06c57b6" />

<img width="408" height="252" alt="image" src="https://github.com/user-attachments/assets/3be12422-77f5-438a-bd84-1eb98fc9ead3" />

  **MODEL GRAPH:**
<img width="371" height="193" alt="image" src="https://github.com/user-attachments/assets/00b69e60-2e6d-48a6-84b4-4fcb67143ba1" />

<img width="392" height="180" alt="image" src="https://github.com/user-attachments/assets/b11163ce-2d8a-4a38-9456-95fd020c4b75" />

  **TABULATION:**
 
<img width="1600" height="605" alt="WhatsApp Image 2026-09-15 at 10 34 19 AM" src="https://github.com/user-attachments/assets/5084bb45-f7cc-4c78-8183-ecca59e7fbd7" />
<img width="1600" height="716" alt="WhatsApp Image 2026-09-15 at 10 34 37 AM" src="https://github.com/user-attachments/assets/bdb91de4-cdec-4a3e-905a-ebf16d5b5e18" />

  **GRAPH:**

  <img width="1163" height="1600" alt="WhatsApp Image 2026-09-15 at 10 35 13 AM" src="https://github.com/user-attachments/assets/a18b6f76-6a4a-4723-af96-e071df04c97f" />




**RESULT:**
Thus a RC Phase Shift and Wien Bridge oscillators designed and tested using op-amp IC 741.
 

