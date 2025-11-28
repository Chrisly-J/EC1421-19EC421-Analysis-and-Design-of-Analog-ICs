# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DIFFERENTIATOR

## AIM:
To design and test the performance of differentiator circuits using Op-amp.

## APPARATUS REQUIRED:
<img width="984" height="273" alt="image" src="https://github.com/user-attachments/assets/2bfcbf8e-9b24-441c-a0c5-b04e0b1bee8d" />

## THEORY:
## DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,

Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1. Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 μF, calculate the value of Rf.
2. Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.
The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM:

<img width="693" height="547" alt="image" src="https://github.com/user-attachments/assets/6efb1bb1-b178-4a4f-8461-743afba09dbf" />

## MODEL GRAPH:

<img width="692" height="1122" alt="image" src="https://github.com/user-attachments/assets/a72f83ce-1bfb-4e3f-b763-d43784915378" />

## PROCEDURE:
### Differentiator:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
   
## DESIGN:
<img width="837" height="443" alt="image" src="https://github.com/user-attachments/assets/fee44ef4-8ae5-4b7a-938e-927c4492992e" />

## TABULATION:

<img width="692" height="655" alt="image" src="https://github.com/user-attachments/assets/73dd7329-8a6a-4bea-bb4e-077fa57cc19b" />

## GRAPH:

<img width="692" height="1150" alt="image" src="https://github.com/user-attachments/assets/462dfd26-07e5-4945-a928-2bcadbefcd89" />

## RESULT:
Thus the Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
