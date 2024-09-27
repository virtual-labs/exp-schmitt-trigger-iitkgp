## Oscilloscope Tutorial

An oscilloscope displays a voltage waveform versus time and has the following components:
1. a screen to display a waveform,
2. input jacks for connecting the signal to be displayed,
3. dials to control how the signal will be displayed.


The screen is cathode ray tube found in most television sets where the face of the screen is divided up into a 2 dimensional grid (or axes or scale); In this experiment we consider 8x10 grid. The vertical grid is divided up into 8 (major) divisions and the horizontal grid is divided into 10 major divisions. To improve the precision, each of these divisions is further broken up into 5 minor divisions. The horizontal axis (X-axis) represents time and the vertical axis (Y-axis) represents voltage. The scope displays (also called a signal trace or trace) the input signal voltage along the vertical (or Y-axis) while an internally generated signal (called the horizontal sweep or sweep signal) is simultaneously produced along the X-axis creating a 2- dimensional time trace of the input signal.

<div align="center">
<img src="images/oscilloscope.png" width="50%">
<p>Figure 1</p>
</div>

volts/div- This control lets you change how many volts are represented by each vertical increment of grid (vertical axis) on the screen. Basically, it allows you to zoom in and out along the y axis.

time/div- This control lets you change how much time is represented by each horizontal increment of the grid overlay on the screen. It allows you to zoom in and out along the x axis.

If volt/div is set to 1 volt which implies each mazor vertical division is 1 volt where as each minor vertical division is 0.2 volt. And time/div is set to 0.1 ms/div which implies each maor horiontal division is 0.1 ms. Voltage on the vertical scale is 1 volt/div multiply by (number of division). Time on the horizontalscale is 0.1 ms multiply by (number of division). In the figure 2, 1 volt/div and amplitude of the input signal is 1 volt. Here 0.1 ms/div, the frequency is 1 kHz and its period is 1 complete cycle in 1 ms.


<div align="center">
<img src="images/oscilloscope_1vd.png" width="50%">
<p>Figure 2</p>
</div>


In the figure 3, if volt/div is set to 2 volt/div, which implies each mazor division is 2 volt where as each minor division is 0.5 volt.

<div align="center">
<img src="images/oscilloscope_2vd.png" width="50%">
<p>Figure 3</p>
</div>

Note: If you set the Volts/Div too low, you’ll clip the signal. Similarly, setting it too high, and you’ll won’t find the signal, i.e. the signal will b flat. ncreasing the Timebase will display more cycles of a periodic signal. Conversely, reducing the Timebase, fewer cycles will be displayed.

Oscilloscope and function generator is described more elaborately->
[Oscilloscope and Function Generator](./images/Oscilloscope_and_Function_Generator_Details.pdf)



<center>
<embed src="./images/Oscilloscope_and_Function_Generator_Details.pdf" type="application/pdf">
</center>