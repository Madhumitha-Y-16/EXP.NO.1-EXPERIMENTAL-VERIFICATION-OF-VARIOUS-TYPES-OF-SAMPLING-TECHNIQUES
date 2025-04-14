# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
 
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   

## PROCEDURE
  ### Natural Sampling:
1. Refer to the block diagram and carry out the following connections and switch setting.
2. Connect power supply in proper polarity to the kit DCL-10 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the 
connecting chords provided.
4. Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4). 
5. Using clock selector switch (S1) select 8khz sampling frequency.
6. Using switch (Sw2) select 50% duty cycle.
7. Connect the OUT post of the flat top sampling block to the input IN1 of the second order low 
pass Butterworth filter and take necessary observations as mentioned below.
8. Repeat the procedure for the 2khz sine wave signal as input.

### FLAT TOP SAMPLING:
1. Refer to the block diagram and carry out the following connection and switch setting.
2. Connect power supply in proper polarity to the kit DCL-01 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the 
connecting chords provided.
4. Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4). 
5. Using clock selector switch(S1) select 8khz sampling frequency.
6. Using switch (Sw2) select 50% duty cycle.
7. Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low 
pass Butterworth filter and take necessary observation as mentioned below.
8. Repeat the procedure for the 2khz, sine wave signal as input.

## CIRCUIT DIAGRAM
 #### NATURAL SAMPLING
![image](https://github.com/user-attachments/assets/ee5b2067-5a45-470a-9aee-d58de192bf8f)

 ### FLAT TOP SAMPLING
![image](https://github.com/user-attachments/assets/41c3a023-fb20-459e-a08c-c1d3fe107772)

## MODEL GRAPH

1.NATURAL SAMPLING 

![image](https://github.com/user-attachments/assets/247e595d-fbc1-4654-896a-a060b50afb7d)

2.FLAT TOP SAMPLING

![image](https://github.com/user-attachments/assets/692688b0-6b19-4037-994d-cb542bf5b497)

## TABLE

![image](https://github.com/user-attachments/assets/b7f9b682-ef99-415f-910f-2e5292da3817)


## OUTPUT GRAPHS

![WhatsApp Image 2025-04-14 at 21 41 29_c8ef4516](https://github.com/user-attachments/assets/9d5576ab-d206-41db-8a7e-be04d7e56b67)

![WhatsApp Image 2025-04-14 at 21 41 28_b1e54aac](https://github.com/user-attachments/assets/ef961bf0-b5f1-496e-b189-868be44c92f5)


## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
