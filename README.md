
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

![WhatsApp Image 2025-11-22 at 21 50 36_20852866](https://github.com/user-attachments/assets/2b1c4f69-5cc0-4925-a4d6-bf5fce6c6ab2)


## TABULATION  
<img width="829" height="829" alt="Screenshot 2025-11-22 214914" src="https://github.com/user-attachments/assets/d2ead766-85d6-49cb-aff2-b5ca3b45afc3" />



## MODEL GRAPH
![WhatsApp Image 2025-11-22 at 21 50 56_d36b3e49](https://github.com/user-attachments/assets/5ff7e37f-f26d-47e0-99d3-b17cca5f48f5)


## RESULT
Thus, the frequency response of the digital fiber optic link was successfully verified. The measured bandwidth of the digital fiber optic link is approximately 100 kHz, confirming the expected performance characteristics of digital optical transmission.
