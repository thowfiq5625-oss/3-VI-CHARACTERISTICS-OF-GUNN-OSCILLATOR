
# 3-VI-CHARACTERISTICS-OF-GUNN-OSCILLATOR

**Aim:**

To study I-V characteristics of Gunn Diode and depth of modulation of modulation of PINdiode.

**Apparatus Used:**

Gunn power supply, Gunn oscillator, PIN modulator, Isolator, Frequency Meter, Variableattenuator, Detector mount, Slotted section, VSWR meter.

**Experimental Setup:**

<img width="880" height="180" alt="image" src="https://github.com/user-attachments/assets/c5e2a20b-5047-4518-886c-c020728660d5" />

**Theory**

The Gunn oscillator is base on negative differential conductivity effect in bulk semi- conductors. Gunn diode has two conduction bands separated by an energy gap (greater than thermal agitation energies). When an electron is moved to the satellite energy band, it will have negative differentialmobility. This produces the negative resistance required for the oscillations.
In a Gunn Oscillator, the Gunn diode is placed in a resonant cavity. In this case the oscillationfrequency is determined by cavity dimension than by diode itself. Although Gunn oscillator can be amplitude-modulated with the bias voltage, separate PIN modulator through is used in this experiment. A square wave modulating signal is applied through the modulator on to the microwave carrier signal.

<img width="445" height="304" alt="image" src="https://github.com/user-attachments/assets/42d87349-4aa0-4730-bb70-9b4897411b7d" />

**Procedure:**

1.	Set the components and equipments as shown in figure above.
2.	Initially set the variable attenuator for maximum attenuation.
3.	Keep the control knob of Gunn power supply as below : Meter switch	:	‘OFF’
    Gunn bias knob	:	Fully anti-clockwise Pin bias knob/Mod Amplifier:	Mid position
    Pin mod frequency	:	Mid position
4.	Keep the, control knob of VSWR meter as below:
    Meter switch	:	Normal
    Input switch	:	crystal low impedance/ 200K Range db switch	:	50db
    Gain control knob	:	Fully clockwise
5.	Set the micrometer of Gunn oscillator between 5-7mm for required frequency of operation.
6.	‘ON’ the Gunn power supply, VSWR meter and cooling fan.
7.	Keep the mode switch of Gunn power supply to square wave/internal Modulation.
8.	Turn the meter knob to voltage position and note that, as Gunn bias voltage is varied currentstarts decreasing. This indicates negative resistance characteristic of Gunn diode. Apply the voltage such that the device is in the middle of the negative resistance region.
9.	Connect detector output to SWR meter.
10.	Adjust the square wave modulation frequency to approximately 1KHz.
11.	Change the meter range if no deflection is observed.
12.	Keep the slotted line probe at position where maximum deflection in meter is observed.
13.	Adjust the attenuator setting, gain control knob on VSWR meter and tune the detectorplunger for pointer to indicate VSWR 1.
14.	Move detector probe along the slotted line and note position of probe where pointer comes to extreme left position, which is first minimum. In order to know exact position of minimum note the positions of equal response points on either side of the minimum and then the midpoint of those positions will give position of minimum. The same way note nextminimum positions.
15.	Repeat the above procedure for different settings of micrometer.

**Depth of Modulation of PIN Diode:**

1.	Apply Gunn Bias Voltage slowly so that panel meter of Gunn power supply reads 8V.
2.	Tune the PIN modulator bias voltage and frequency knob for maximum output on theoscilloscope.
3.	Coincide the bottom of square wave oscilloscope to some reference level and note down themicrometer reading of variable attenuator.
4.	Now with help of variable attenuator coincide the top of square wave to same referencelevel and note down the micrometer reading.
5.	Connect VSWR to detector mount and note down the dB reading in VSWR meter for boththe micrometer reading the variable attenuator.
6.	The difference of both dB reading of VSWR meter gives the modulation depth of PINmodulator.

*Note: After tuning the Gunn source, the procedure for VSWR & Impedance measurement depthof PIN modulator.*

**B.Observation:**


| S.No | GUNN BIAS VOLTAGE (V)  | GUNN DIODE CURRENT (mA)  |
|------|------------------------|--------------------------|
| 1    | 0.2                    | 30                       |
| 2    | 0.4                    | 60                       |
| 3    | 0.8                    | 90                       |
| 4    | 1.5                    | 150                      |
| 5    | 2.0                    | 180                      |
| 6    | 2.5                    | 210                      |
| 7    | 3.5                    | 195                      |
| 8    | 4.3                    | 180                      |
| 9    | 5.0                    | 165                      |


**Observation Analysis**

- Up to 2.5 V, current increases linearly.
- Between 2.5 V and 5 V, current slightly decreases — indicating the negative resistance region.
- This region is responsible for generating oscillations inside the resonant cavity of the Gunn oscillator.


**C.Analysis of Results:**

From the observation table, it is seen that the current through the Gunn diode initially increases linearly with the applied bias voltage. As the voltage increases further, the current reaches a **peak value** (known as *Peak Current*) and then **decreases** even though the voltage continues to increase — this region is called the **Negative Resistance Region**. After reaching the *Valley Current*, the current starts to rise again with voltage.

This behavior confirms the **negative differential resistance (NDR)** characteristic of the Gunn diode, which is essential for microwave oscillation.

#### **Sample Calculation**

<img width="779" height="279" alt="Screenshot 2025-11-04 085418" src="https://github.com/user-attachments/assets/c198862d-91c0-4a08-ad1b-2887c13a1a81" />

</br>
</br>
</br>


**Graph:**


![WhatsApp Image 2025-11-17 at 8 49 42 PM](https://github.com/user-attachments/assets/564ad48e-2f4b-4bb2-84df-0acf58b3d67d)


</br>
</br>
</br>
</br>

**D.Conclusions:**

1. The I–V characteristic of the Gunn diode exhibits a negative differential resistance region between approximately 2.5 V and 5 V, confirming its capability for microwave oscillation.  
2. The peak current and valley current were observed at 195 mA and 175 mA, respectively.  
3. The calculated negative resistance of about –125 Ω supports the theory of transferred electron effect in Gunn diodes.  
4. The experiment successfully demonstrates the working principle of a Gunn oscillator and the role of the negative resistance region in generating microwave signals.  
5. The depth of modulation of the PIN diode can be determined using the difference in dB readings on the VSWR meter corresponding to the maximum and minimum attenuation.


**Precautions:**

•	Check the connections before switching on the kit.
•	Connections should be done properly.
•	Observation should be taken properly.

**Result:**

- The I–V characteristics of the Gunn diode were plotted and the negative resistance region was identified.  
- Peak voltage (Vₚ) = 2.5 V, Valley voltage (Vᵥ) = 5 V.
- Peak current (Iₚ) = 195 mA, Valley current (Iᵥ) = 175 mA.  
- Calculated negative resistance (Rₙ) ≈ –125 Ω.
- The depth of modulation of the PIN diode can be obtained from the dB difference in the VSWR readings.  
Hence, the experiment is successfully performed, and the negative differential resistance characteristics of the Gunn diode were verified.
