## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF SCHMITT TRIGGER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
<img width="1918" height="1086" alt="image" src="https://github.com/user-attachments/assets/11dc6b18-8788-4419-8d9d-e63e2a8e2c81" />



## OUTPUT GRAPH:
### DAC:
![WhatsApp Image 2025-11-26 at 10 47 58_13c5462d](https://github.com/user-attachments/assets/be4bd5f0-64ae-49ef-96db-7170d60bac7c)

![WhatsApp Image 2025-11-26 at 10 48 14_eb623619](https://github.com/user-attachments/assets/d9438f54-66df-4df9-9d7c-49f860ae0f1a)

## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
