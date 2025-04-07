# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
### Natural Sampling
Refer to the block diagram and carry out the following connections and switch setting.

Connect power supply in proper polarity to the kit DCL-10 and switch it on.

Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the connecting chords provided. 

Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).

Using clock selector switch (S1) select 8khz sampling frequency.

Using switch (Sw2) select 50% duty cycle.

Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.

Repeat the procedure for the 2khz sine wave signal as input. 

### Flat top sampling

Refer to the block diagram and carry out the following connection and switch setting.

Connect power supply in proper polarity to the kit DCL-01 and switch it on.

Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the connecting chords provided.

Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).

Using clock selector switch(S1) select 8khz sampling frequency.Using switch (Sw2) select 50% duty cycle. 

Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low pass Butterworth filter and take necessary observation as mentioned below.

Repeat the procedure for the 2khz, sine wave signal as input 

## CIRCUIT DIAGRAM
### Natural Sampling
![natural sampling block](https://github.com/user-attachments/assets/630150a8-0d6c-4030-aec1-cc61c2e5eb37)
### Flattop Sampling
![flattop block](https://github.com/user-attachments/assets/69f4b0cc-ce64-482b-a7e8-8c157e48d36c)


## MODEL GRAPH
### Natural Sampling
![natural sampling model graph](https://github.com/user-attachments/assets/0e759ab9-8c39-4438-9b2d-be331205608f)

### Flattop Sampling
![flattop model graph](https://github.com/user-attachments/assets/0d98553b-f701-4131-acef-6eb79e166542)

## TABLE
![natural tab col](https://github.com/user-attachments/assets/186a03ef-583f-492c-9b25-739ff550e140)

## OUTPUT GRAPHS
![natural op graph 1 png](https://github.com/user-attachments/assets/07dcf18f-c2dc-4754-9c21-0e39da14b880)
![natural op graph 2](https://github.com/user-attachments/assets/1b27f185-4c1d-4ab7-a9f4-de577cbc4f88)
![natural op graph 3](https://github.com/user-attachments/assets/01577dbb-886d-448e-8b92-5df8f7d71296)

## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
