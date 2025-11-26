# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
![WhatsApp Image 2025-11-26 at 10 29 21_85330898](https://github.com/user-attachments/assets/b57c26ee-fc5b-4adb-a086-bcbc502d46d0)

## HIGH-PASS
![WhatsApp Image 2025-11-26 at 10 29 35_6e1e1b78](https://github.com/user-attachments/assets/80c12718-637e-4539-bc11-209aaab9faea)

## BAND-PASS
![WhatsApp Image 2025-11-26 at 10 29 53_5ebda185](https://github.com/user-attachments/assets/40516db7-e6da-476d-ba95-02a4dbea06c1)


## MODEL GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-26 at 10 30 11_b397182c](https://github.com/user-attachments/assets/c20ff828-d578-490e-b4fa-6837ff3fa432)

## HIGH-PASS
![WhatsApp Image 2025-11-26 at 10 30 32_ad445782](https://github.com/user-attachments/assets/10403275-cbb7-4e5b-806c-b1746fcd4b87)

## BAND-PASS
![WhatsApp Image 2025-11-26 at 10 30 47_224ba645](https://github.com/user-attachments/assets/279e57d5-f6e6-4d33-92b6-60faa2d27fdf)


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2025-11-26 at 10 31 06_6e3a9158](https://github.com/user-attachments/assets/0f39b5e5-f377-45d3-94b6-5854471bb0f8)

## HIGH-PASS
![WhatsApp Image 2025-11-26 at 10 31 18_307540d0](https://github.com/user-attachments/assets/52d4f76a-52c5-4772-9da5-5de6939fede4)

## BAND-PASS
![WhatsApp Image 2025-11-26 at 10 31 34_f803b93c](https://github.com/user-attachments/assets/6994ea08-1d99-4d32-8901-cafd6703be63)

## GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-26 at 10 32 02_49c61110](https://github.com/user-attachments/assets/941cb7fc-ebbf-4933-8926-f684527e0c8d)
## HIGH-PASS
![WhatsApp Image 2025-11-26 at 10 32 14_74a93130](https://github.com/user-attachments/assets/13a088f7-0e0b-4954-ae26-b14035681373)

## BAND-PASS
![WhatsApp Image 2025-11-26 at 10 32 27_c9686208](https://github.com/user-attachments/assets/3cd776f7-4b79-45a2-8d85-6c68904a0b26)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

