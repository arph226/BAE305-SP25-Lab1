# Laboratory Report for Lab 1 of BAE305 Spring 2025
# Lab 1 – Well Equipped: Knowing Your Instruments
* By: Abby Phillips and Audrey Suit
* Submitted: February 3rd, 2025

# Summary
The goal of this lab is to learn how to use lab equipment including a function generator, digital multimeter, oscilloscope, and direct current power supply. We measured resistors and capacitors using the digital multimeter. We checked the voltage coming from the D.C. power supply with the digital multimeter to see how it aligned with the supposed output voltage. We connected a resistor to the function generator to produce a sine wave, then using the oscilloscope we observed the signal and measured the amplitude and frequency. Finally, we created a repository in github to store the lab reports. This report is stored in this repository as a wiki. Our group is certainly more familiar and accustomed to the lab equipment as a result of this lab period.

# Materials
4 Resistors: (10M&Omega;, 3.3k&Omega;, 150&Omega;, 2.2&Omega;) 4 Capacitors (10 mF, 1mF, 1.02nF, 0.22 nF), 10k&Omega; resistor

![image](https://github.com/user-attachments/assets/0286002a-d320-4795-852a-907021ab1572)


# Assembly Procedures

You must include Schematics, Engineering Drawings, and Programming if appropriate in this section.

1. Using the Fluke DMM, we measure the actual resistance of each resistor by attaching each lead to one side of the resistor via its alligator clips. Using the resistor color code, we found the labeled resistance of each resistor.
![image](https://github.com/user-attachments/assets/e0337021-37bb-46b8-a0fe-ba46322ba3dc)
4. Using the Fluke DMM, we measure the actual capacitance of each capacitor by attaching each lead to one side of the capacitor via its alligator clips, in the same way as the resistors.
6. Using the D.C. Power Supply, we set the voltage to three different values: +1.5V, +7.0V and +12.0V. We also set the 3.3/5.0V and 12V outputs. To double check each voltage, we attached the leads of the D.C. Power Supply to the leads of the Fluke DMM.
![image](https://github.com/user-attachments/assets/0a378cdb-018d-49af-b115-c81c60ab78a4)
8. We mounted a 10k&Omega; resistor to the breadboard and connected it to the Function Generator by clipping the FG's cables to either side of the resistor. We set the FG to produce a 2kHz sine wave to the maximum amplitude supplied by the FG using its amplitude dial.
9. Using the Oscilloscope Tektronix TS2012, we looked at the signal by attaching its leads to each side of the resistor.
    ![image](https://github.com/user-attachments/assets/640ec8e8-cb27-42f6-867c-91b89974aef6)
	a) We counted each square on the Oscilloscope Tektronix TS2012 screen to read the amplitude and frequency.
	b) We used the moveable cursors on the Oscilloscope Tektronix TS2012 and placed them at a crest and trough of the wave and measured the amplitude. We changed the cursor orientation and placed them at two crests to measure the frequency.
	c) We used the Oscilloscope Tektronix TS2012's measurement features to have the machine output the wave's amplitude and frequency values
	d) We used the Fluke DMM and clipped its leads to each side of the resistor to read off the amplitude and frequency values.
![image](https://github.com/user-attachments/assets/fcfae7b9-c87d-4db5-8fc4-18fd24f46ffc)
11. We set the Oscilloscope Tektronix TS2012 to various frequency and amplitude values by rotating the frequency and amplitude dials of the Function Generator.
12. Using GitHub, we created our own accounts and we followed the tutorial "Hello World" to familiarize ourselves with its general pages and features. We ended the tutorial and created a repository titled "hello-world". 
13. Using GitHub, we created a new public repository titled "BAE305-SP25-Lab 1" and clarified "initialize this repository with a READM" was selected.
14. Using Github, we navigated to the Wiki tab and created our lab report using the wiki page and the provided lab report template for this class.

# Test Equipment
1. Fluke 87 V DMM
2. Oscilloscope Tektronix TS2012
3. Function Generator
4. DC Power Supply

# Test Procedures
This section deals with the method for obtaining your results. Make sure to be clear and concise such that a student next year can replicate the laboratory. How did you test the system to get your results.
* To measure the equivalent resistance we placed the DMM in terminal X of R1 and terminal X on R3.
* To measure the capacitance of the capacitor we used the DMM in mode X.
1. Measure and verify the resistance of various resistors.
- Using the Fluke Digital Multimeter (DMM) in the DC resistance mode, we measured each resistor’s actual resistance by placing the DMM on each terminal of the resistor.
- For each resistor, we record the color code, expected resistance, and calculated the tolerance limits.
- We compared measured resistance with expected values and noted any deviations beyond tolerance.
2. Measure and verify the capacitance of various capacitors.
- We measured the capacitance of each provided capacitor using the Fluke DMM in DC capacitance mode.
- We determined capacitance expected values by reading the values on each capacitor and using the letter chart to determine tolerance
- Observed whether polarity affects the measurement of the electrolytic capacitor by changing the switching where the terminals of the DMM were connected on the capacitor.
3. Measure and verify the voltage output of the DCPS.
- We measured the voltage output of the DCPS by connecting the power supply leads to the respective voltage port we were measuring.
- Using the DMM in DC Voltage mode, we measured voltage for the 3.3V, 5V, and 12V outputs and compared the results to the expected value.
4. Measure and verify the function generator output
- We connected a 10KΩ resistor to the output of the Function Generator and configured the FG to output a 2kHz sine wave at maximum amplitude.
- We adjusted the Volts/DIV and SEC/DIV knobs on the oscilliscope to observe the wave
- We measured the amplitude and frequency of the wave using four methods:
  - Counting squares on the oscilloscope screen.
  - Using the oscilloscope’s moveable cursors.
  - Using the oscilloscope’s automatic measurement feature.
  - Using the DMM
 - We compared measured values to the function generator’s dial settings
 - We adjusted frequency and amplitude of the waveform to observe changes

# Test Results
The results obtained for step 1 of the Test Procedures are shown in the table below. All resistors were found to be in tolerance

**Resistor Values Table**
|Color Code|Expected Value (&Omega;)|Tolerance(%)|Measured Value (&Omega;)|Within Tolerance|
|----------|----------|----------|----------|----------|
|Brown Black Blue|10M|5|10.25M|yes|
|Orange Orange Red|3.3k|5|3.297k|yes|
|Brown Green Brown|750|5|749.9|Yes|
|Red Red Gold|2.2|5|2.3|yes|

The results obtained for step 2 of the Test Procedures are shown in the table below. The 22&mu;F capacitor was not in tolerance, all other capacitors were.

**Capacitor Values Table**
|Expected Value (&mu;F)|Tolerance(%)|Measured Value (&mu;F)|Within Tolerance|
|----------|----------|----------|----------|
|10|20|10.44|Yes|
|1|10|1.1|Yes|
|102|10|1.34|No|
|22|5|6.36|No|

The results obtained for step 3 of the Test Procedures are shown in the table below. The set voltages were very close, if not exactly the same, as the measured voltages. Errors were likely due to DMM measurement since sometimes values would continue to change on the DMM after the probes were attached. This could lead to some measurement error.

**DC Power Source Voltage Output Table**
|Set Voltage (V)|Measured Voltage (V)|
|----------|----------|
|1.56|1.494|
|7.00|7.00|
|12.00|12.01|
|3.3|3.389|

The results obtained for step 4 of the Test Procedures are shown in the table below. All values were close to one another, however were not the same as the frequency set by the function generator (2kHz), this is likely due to the age of the machine and calibration. The amplitude was similar to what we set the function generator (5V). The DMM did not read amplitude accurately as we could not measure the varying voltage accurately since it does not measure a range of values, only one value at a time. The measurement feature of the frequency generator is the most accurate since it can exactly read the amplitude peaks.

**Function Generator Output Table**
|Measurement Method|Frequency (kHz)|Amplitude (V)|
|----------|----------|----------|
|Cursors|4.81|5.04|
|Counting Squares|5|5|
|Measurement Features|4.66|5.25|
|Fluke DMM|4.66|0.126|


# Discussion

2a-Do the instruments agree with the expected value?

Yes, each capacitor value fell within the expected range for its capacitance.

2b- Does polarity affect the measurement of the electrolytic capacitor?

Polarity did not affect the measurement. If anything, it was a negligible amount that could be attributed to measurement error.

Discussion Question 1: Do the instruments agree with each other in part 3? Why?

They agreed with each other as the voltage output shown on the D.C. Power Supply's screen matched the measured value from the Fluke DMM. Thus, the Fluke DMM verified that the D.C. Power Supply was delivering its reported voltage.

Discussion Question 2: Do the instruments agree in part 4 for the oscilliscope/function generator? Why?

When measuring the amplitude and frequency, the instruments didn't produce the exact same values. However, the difference was so small, it could be counted as negligible and it can be determined that the values were more or less the same. As we increased the frequency values, the amplitude of the sine wave decreased, when it should have remained the same since the voltage source did not change.


# Conclusion

In summary, this lab aimed to incorporate commonly used circuit components and devices into a test procedure. We verified values for components like resistors and capacitors and devices like the Function Generator. By using many different tools, we are now familiarity with the usage and purpose of the Oscilloscope Tektronix TS2012, Fluke DMM, D.C. Power Supply, and Function Generator. The completion and learning attained by this lab will help us in future labs as we expand on the usage of these instruments with more complex projects and purposes.
