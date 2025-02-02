# Laboratory Report for Lab 1 of BAE305 Spring 2025
# Lab 1 – Well Equipped: Knowing Your Instruments
* By: Abby Phillips and Audrey Suit

# Summary
Lab goal; summary of work performed; summary of outcome
The goal of this lab is to learn how to use lab equipment including a function generator, digital multimeter, oscilloscope, and direct current power supply. We measured resistors and capacitors using the digital multimeter. We checked the voltage coming from the D.C. power supply with the digital multimeter to see how it aligned with the supposed output voltage. We connected a resistor to the function generator to produce a sine wave, then using the oscilloscope we observed the signal and measured the amplitude and frequency. Finally, we created a repository in github to store the lab reports. This report is stored in this repository as a wiki.

# Materials
4 different Resistors, 4 different Capacitors, 10k&Omega; resistor

# Assembly Procedures
Provide basic summary of steps performed in lab (**Do not copy and paste from lab assignment.**) The important part here is to provide detail that you had to develop in the lab which will be more important in later labs.
You must include Schematics, Engineering Drawings, and Programming if appropriate in this section.

1. What *YOU* did. How *YOU* did it.
2. We solder the resistors to a solder bread board.
- We set the temperature of the soldering iron to 700 &deg;C.
- We tinned the soldering iron.
- We made contact of the soldering iron, the component to be soldered, and some solder. Below is a picture.

![A test image](https://github.com/cjarro-uky/BAE305-SP24-Lab1/blob/main/20240110_100436.jpg)

Or perhaps a nicer smaller, centered image like this (using html):

<p align="center">
  <img src=https://github.com/cjarro-uky/BAE305-SP24-Lab1/blob/main/20240110_100436.jpg width=50%>
</p>


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

Adjust the frequency and amplitude of the waveform and observe changes on the oscilloscope and DMM.

# Test Results
The results obtained for step 1.1 of this lab are shown in the table below.

**Resistor Values Table**
|Expected Value (&Omega;)|Measured Value (&Omega;)|Within Tolerance|
|----------|----------|----------|
|100K|99.89K|Yes|
|21|45|No|
   
2. The results obtained for step 1.2 of this lab are shown in the table below.

**Capacitor Values Table**
|Expected Value (&mu;F)|Measured Value (&mu;F)|Within Tolerance|
|----------|----------|----------|
|1|1.05|Yes|
|0.0002|0.032|No|

3. The code we wrote had several bugs but with some help we made it work. The values displayed for the sensor measurement were XX.XX for a physical distance of XX.XX

# Discussion
Answer every the lab questions in this section. You should do it within a written paragraph like the next one.

We were able to measure all the resistors and found out that only R5's value was not whithin the tolerance as shown in table X

Did you make any design decisions that had an impact on the results? How did they impact the results? What do the results mean?

Think about the lab exercises and make any interesting observation or analysis in this section too. Show that you learned something in this lab.

# Conclusion
Summarize what your aim was, what you did and what were the most important results. If you have any ideas or feedback about the lab you can propose them here (no complaints).

In summary, we measured the resistance using the DMM we found out that most of the resistors fell within the tolerance.
We also used a sensor and an Arduino controller to read a physical value. The error was acceptable/ too large. I think the resistance and capacitance measurements were long and repetitive, a better use of this time would have been to use the mathematical options of the oscilloscope.
