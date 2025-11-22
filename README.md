# SSB

EXP NO: 3	SSB-SC-AM MODULATION using SCILAB

AIM:

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

EQUIPMENTS REQUIRED

•	Computer with i3 Processor

•	SCI LAB

Note: Keep all the switch faults in off position


Algorithm
1.	Define Parameters:
•	Fs: Sampling frequency.
•	T: Duration of the signal.
•	Fc: Carrier frequency.
•	Fm: Frequency of the message signal.
•	Amplitude: Maximum amplitude of the message signal.
2.	Generate Signals:
•	Message Signal: The baseband signal that will be modulated.
•	Carrier Signal: A high-frequency signal used for modulation.
•	Analytic Signal: Constructed using the Hilbert transform to get the in-phase and quadrature components.
3.	SSBSC Modulation:
•	Modulated Signal: Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.
4.	SSBSC Demodulation:
•	Mixing: Multiply the SSBSC signal with the carrier to retrieve the message signal.
•	Low-pass Filtering: Apply a low-pass filter to remove high-frequency components and recover the original message signal.
5.	Visualization:
•	Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.


PROCEDURE

•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
 
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Model Waveform

<img width="704" height="178" alt="image" src="https://github.com/user-attachments/assets/32ee29b3-0d95-4192-9762-972d50c05c90" />
<img width="706" height="167" alt="image" src="https://github.com/user-attachments/assets/bff0d8fd-d679-444e-af37-0b34585853c1" />

Program



<img width="561" height="791" alt="image" src="https://github.com/user-attachments/assets/6ce4120f-2a8f-40a5-bfd7-78647b9f1332" />

OUTPUT WAVEFORM


<img width="759" height="664" alt="image" src="https://github.com/user-attachments/assets/72206b05-6a58-4dc6-8295-3545aa1191da" />



TABULATION



![WhatsApp Image 2025-11-22 at 07 49 24_8b07adeb](https://github.com/user-attachments/assets/6f954f33-39ff-4eef-b621-95f21364008f)


# calculation
![WhatsApp Image 2025-11-22 at 07 50 29_31cb2c45](https://github.com/user-attachments/assets/7a8f3e09-40b3-46b2-8fcf-ef7cfcec1745)




RESULT:

Thus, the SSB-SC-AM Modulation and Demodulation is experimentally done and the output is verified.





