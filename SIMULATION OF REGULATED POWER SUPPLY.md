# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
<img width="1255" height="662" alt="image" src="https://github.com/user-attachments/assets/fdfa5f3e-ea72-4e25-a991-e62f43cd80f7" />

## AC INPUT WAVEFORM:
<img width="1262" height="692" alt="image" src="https://github.com/user-attachments/assets/a3d93e86-39cb-4e86-bdc5-62b125e731b3" />

## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="1253" height="685" alt="image" src="https://github.com/user-attachments/assets/631a8f2d-ab13-4a02-bba9-d334f0a1c04f" />
<img width="1656" height="882" alt="image" src="https://github.com/user-attachments/assets/5fb7426e-9720-481d-9c02-095ed84a6f87" />


## SIGNAL OUTPUT(WITH FILTER)
<img width="996" height="506" alt="image" src="https://github.com/user-attachments/assets/ad5bfd87-71e7-4aa2-a231-4102d920126e" />
<img width="1055" height="542" alt="image" src="https://github.com/user-attachments/assets/df89cc3a-bd54-4479-8944-34d01c70dfb5" />

<img width="1272" height="666" alt="image" src="https://github.com/user-attachments/assets/628c79a2-406d-4e01-8d39-7a8d16b197d7" />
<img width="1180" height="630" alt="image" src="https://github.com/user-attachments/assets/5390af58-377f-4388-8aae-d6f09ae2343a" />
## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
