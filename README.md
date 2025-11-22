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



<img width="576" height="819" alt="Screenshot 2025-10-09 153247" src="https://github.com/user-attachments/assets/d4f7affa-5653-4b2b-b961-30bb07be409a" />

OUTPUT WAVEFORM


<img width="1687" height="852" alt="Screenshot 2025-10-09 153308" src="https://github.com/user-attachments/assets/755e2c74-96f1-4262-b609-dbcf5279d103" />


TABULATION



![WhatsApp Image 2025-10-09 at 16 13 50_d5e3d330](https://github.com/user-attachments/assets/77d9aec1-32ee-4f33-8ab2-48aa4f4884d0)


# calculation
![WhatsApp Image 2025-10-09 at 16 13 50_052bd90c](https://github.com/user-attachments/assets/5e68c473-69e8-4cfe-a3ca-8d157a06d618)




RESULT:

Thus, the SSB-SC-AM Modulation and Demodulation is experimentally done and the output is verified.





