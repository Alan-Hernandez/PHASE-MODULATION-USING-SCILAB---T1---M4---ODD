# PHASE-MODULATION-USING-SCILAB---T1---M4---ODD


## Aim
To implement and analyze Phase Modulation (PM) using Scilab.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike Frequency Modulation (FM), where the frequency is varied, in Phase Modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.

### Mathematical Representation
The general form of a Phase Modulated signal $s(t)$ is given by:

$$s(t) = A_c \cos(2\pi f_c t + k_p m(t))$$

Where:
* $A_c$ : Amplitude of the carrier wave
* $f_c$ : Carrier frequency
* $m(t)$ : Message signal, typically $m(t) = A_m \cos(2\pi f_m t)$
* $k_p$ : Phase deviation sensitivity (in radians/volt)

---

## Algorithm
1. **Initialize Parameters:**
   * Define carrier amplitude ($A_c$), carrier frequency ($f_c$), message frequency ($f_m$), sampling frequency ($f_s$), and phase sensitivity ($k_p$).
2. **Generate Time Axis:**
   * Create a time array $t$ with suitable sampling steps over the signal duration.
3. **Generate Message Signal:**
   * Compute the message signal vector $m(t)$ using the cosine function.
4. **Generate Carrier Signal:**
   * Compute the unmodulated carrier signal vector $c(t) = A_c \cos(2\pi f_c t)$.
5. **Generate PM Signal:**
   * Compute the phase-modulated signal $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$.
6. **Plot the Signals:**
   * Use Scilab's plotting commands (`subplot`, `plot`, `xtitle`, `xgrid`) to display message, carrier, and modulated signals.

---
## TABULATION 
<img width="1600" height="992" alt="image" src="https://github.com/user-attachments/assets/0cec50dc-403a-44d7-8f0a-f01af255b442" />

## MODEL GRAPH
<img width="1512" height="832" alt="image" src="https://github.com/user-attachments/assets/9570a953-973a-4b57-a360-bbaa268ccf3c" />

## CALCULATION 

<img width="976" height="1600" alt="image" src="https://github.com/user-attachments/assets/9ed329fb-fccb-4fbb-b6da-aff617e9e854" />

## CODING 

<img width="1600" height="1430" alt="image" src="https://github.com/user-attachments/assets/0479e9ad-6572-425a-b6cc-1eb7c78e8639" />

<img width="1600" height="1242" alt="image" src="https://github.com/user-attachments/assets/effeb176-2d59-4447-ac1d-babdde14f134" />

## RESULT 

<img width="1600" height="634" alt="image" src="https://github.com/user-attachments/assets/e3cf213d-6b7d-4b56-a875-41dca605e5ae" />

## MARK ALLOCATION 

<img width="1600" height="918" alt="image" src="https://github.com/user-attachments/assets/b7820365-e784-4004-94c4-57a100d754d0" />





