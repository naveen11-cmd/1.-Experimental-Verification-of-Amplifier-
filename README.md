#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-11-28 at 13 32 34_0865b8c0](https://github.com/user-attachments/assets/fbaf341e-22c8-489c-840f-ce0eb3a7e974)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-28 at 12 56 05_41a7135d](https://github.com/user-attachments/assets/d388e937-4bdb-4be3-a670-1f0e03bb7025)


MODEL GRAPH 

![WhatsApp Image 2025-11-28 at 12 56 10_88f07f89](https://github.com/user-attachments/assets/eb618e41-e4ee-4d29-9a35-1ed51842585a)

DESIGN:

![WhatsApp Image 2025-11-28 at 13 26 41_3126f903](https://github.com/user-attachments/assets/3fe31ad3-01d2-4483-a27e-dc7913e35768)

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![WhatsApp Image 2025-11-28 at 12 56 05_314e08fe](https://github.com/user-attachments/assets/205dfe41-257b-4095-af89-ff7e4a379985)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-27 at 18 49 39_ac2028e9](https://github.com/user-attachments/assets/ff0980bc-9128-41b0-b505-4cbe7a4d2018)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-11-27 at 18 11 10_7892462b](https://github.com/user-attachments/assets/ac51aeeb-577f-4560-b9a1-f3b04cbec8b2)

---

## MODEL GRAPH

![WhatsApp Image 2025-11-28 at 12 56 11_8ad6ce75](https://github.com/user-attachments/assets/555ef718-6b45-488e-a99e-24d53c653b3a)


---
## DESIGN
![WhatsApp Image 2025-11-28 at 13 26 41_b919ea42](https://github.com/user-attachments/assets/6f4e3ff8-0f0c-4cde-9ec6-13d5a983f262)

PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![WhatsApp Image 2025-11-28 at 12 56 08_cfe36e3d](https://github.com/user-attachments/assets/542a317c-d1d9-4cfa-8a17-f7f82dc97444)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-27 at 18 49 40_0d0cec83](https://github.com/user-attachments/assets/6384c0bc-4ea6-4cd4-b313-dc71f417cdba)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 12 56 11_d6b4fab4](https://github.com/user-attachments/assets/c5853507-15f1-4d08-9488-9274aa92aa30)



## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 12 56 12_ab15a587](https://github.com/user-attachments/assets/776b39cc-d3b2-4f22-8cb7-9e1724dcc676)


---

## DESIGN
![WhatsApp Image 2025-11-28 at 13 26 42_46b9bda2](https://github.com/user-attachments/assets/c61bad39-46cd-4885-90d4-7518799b27ec)


---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-28 at 13 11 50_08dc5b36](https://github.com/user-attachments/assets/8a224e0b-e8a1-4da0-b1f0-7c27ec00284e)



---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-27 at 18 49 40_77884391](https://github.com/user-attachments/assets/12541ac0-2e7f-4562-8d87-60e118bfb083)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-11-28 at 13 18 51_d0f1b794](https://github.com/user-attachments/assets/defee038-7f01-4cce-8dd3-53dd3741a9e8)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-11-28 at 13 18 53_1f406441](https://github.com/user-attachments/assets/0f44f7c1-8ac5-46c9-a18b-a4b15f083917)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-27 at 18 49 41_7986e58b](https://github.com/user-attachments/assets/c4be838e-ee01-45fd-8d00-64bfd5d4ece9)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
