# FM-using-Python

Aim

To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:



Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program

<img width="430" height="430" alt="fm-code" src="https://github.com/user-attachments/assets/1f7468ed-10d2-440d-a26f-afe75e4dc2fc" />

Output Waveform

<img width="555" height="415" alt="fm-python" src="https://github.com/user-attachments/assets/046663d5-1aa2-4b08-b4ec-f6de8c71bda7" />

Tabular Column

![fmpy](https://github.com/user-attachments/assets/e0a1f4b9-c340-44e5-8c7a-f7386b5a1b20)

Calculation

![fmcal](https://github.com/user-attachments/assets/5435e115-0c61-483c-8d68-10da0811be4f)

Result

The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
