# EXP-8-SIMULATION-OF-REGULATED-POWER-SUPPLY
Aim
To design and simulate a complete AC to DC power supply using LTspice, consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode, voltage regulator and load, and to observe the output waveform at each stage. 
Software Required
LTspice
Components Required
•	AC source 
•	Transformer 
•	Diodes – 4 
•	Smoothing capacitor 
•	Zener diode 
•	Series resistor 
•	Load resistor 
________________________________________
Procedure
1.	Double-click on the LTspice icon and open a new schematic window. 
2.	Pick and place the required components from the library and draw the transformer circuit using AC source, L1L_1, L2L_2 and coupling. 
3.	Run the simulation and observe the transformer secondary output. 
4.	Pick and place four diodes and draw the bridge rectifier circuit. 
5.	Run the simulation to obtain the rectified waveform. 
6.	Place the smoothing capacitor across the rectifier output. 
7.	Run the simulation again to observe the filtered DC waveform. 
8.	Add the Zener diode regulator with a series resistor and connect the load resistor. 
9.	Right-click each component and set the required values. 
10.	Save the file with a suitable name. 
11.	Click Run → Advanced → Transient Analysis and set the stop time, for example 60 ms. 
12.	Click Run and place the probe at each stage to observe: 
•	Transformer output 
•	Rectifier output 
•	Filter output 
•	Regulated output 
•	Load voltage 
________________________________________
CIRCUIT DIAGRAM:

AC INPUT WAVEFORM:
The AC input waveform is observed in LTspice before applying it to the transformer.
<img width="1917" height="1016" alt="Screenshot 2026-11-17 204346" src="https://github.com/user-attachments/assets/634a2fbb-e28a-4760-addd-3b69cac0a3f2" />


OUTPUT GRAPHH:

SIGNAL OUTPUT(WITHOUT FILTER)
The output of the bridge rectifier is observed. The waveform is a pulsating DC waveform.
<img width="1916" height="1017" alt="Screenshot 2026-11-17 204233" src="https://github.com/user-attachments/assets/c93474f4-f8dd-4343-baa5-a8546360a637" />
<img width="1912" height="1012" alt="Screenshot 2026-11-17 205130" src="https://github.com/user-attachments/assets/89d7fd72-dae9-419d-aeaa-6ba23cfb4598" />


SIGNAL OUTPUT(WITH FILTER)
The smoothing capacitor is connected across the rectifier output. The capacitor reduces the variations in the rectified waveform and produces a smoother DC output.

<img width="1917" height="1016" alt="Screenshot 2026-11-17 211502" src="https://github.com/user-attachments/assets/e1b01744-3bff-4ebd-91f4-8902f70f4fc9" />

<img width="1916" height="1020" alt="Screenshot 2026-11-17 211223" src="https://github.com/user-attachments/assets/161080e0-d1b8-4de4-aaf0-7342b0422d33" />


Result


Thus, the regulated power supply was simulated using LTspice. The output waveform at each stage was observed and analysed, and a stable regulated DC output was obtained at the load. 
