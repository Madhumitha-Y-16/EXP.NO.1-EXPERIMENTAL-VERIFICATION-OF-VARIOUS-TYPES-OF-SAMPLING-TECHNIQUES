# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
NATURAL SAMPLING:
Refer to the block diagram and carry out the following connections and switch setting.
Connect power supply in proper polarity to the kit DCL-10 and switch it on.
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the 
connecting chords provided.
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4). 
Using clock selector switch (S1) select 8khz sampling frequency.
Using switch (Sw2) select 50% duty cycle.
Connect the OUT post of the flat top sampling block to the input IN1 of the second order low 
pass Butterworth filter and take necessary observations as mentioned below.
Repeat the procedure for the 2khz sine wave signal as input.

FLAT TOP SAMPLING:
Refer to the block diagram and carry out the following connection and switch setting.
Connect power supply in proper polarity to the kit DCL-01 and switch it on.
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the 
connecting chords provided.
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4). 
Using clock selector switch(S1) select 8khz sampling frequency.
Using switch (Sw2) select 50% duty cycle.
Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low 
pass Butterworth filter and take necessary observation as mentioned below.
Repeat the procedure for the 2khz, sine wave signal as input
## CIRCUIT DIAGRAM
1. NATURAL SAMPLING
   
![image](https://github.com/user-attachments/assets/789bf2d4-1677-4c6c-b765-a26befe50321)

3. FLAT TOP SAMPLING
   
![image](https://github.com/user-attachments/assets/94401fee-fa2b-401f-8740-0028fd9ce578)


## MODEL GRAPH
![image](https://github.com/user-attachments/assets/450a1cc3-d1d8-4b19-b7b6-a3d873a5ba9a)
![image](https://github.com/user-attachments/assets/0c02ebf4-8ddf-44c7-b4a0-c12f5f779f7f)


## TABLE

![image](https://github.com/user-attachments/assets/6e1de39d-4443-4977-8de6-1f8bdb4b0455)

## OUTPUT GRAPHS

![WhatsApp Image 2025-04-14 at 21 41 29_c8ef4516](https://github.com/user-attachments/assets/5ab03a9e-b067-4b34-a5d5-2c331a30366f)

![image](https://github.com/user-attachments/assets/b99afbfd-e629-478e-a19b-8a9c523a8edb)


## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
