# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

<img width="800" height="490" alt="WhatsApp Image 2026-09-23 at 12 51 41 PM" src="https://github.com/user-attachments/assets/1ff59023-888c-40cf-a9d6-23f2c7ce5c22" />

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
<img width="800" height="454" alt="WhatsApp Image 2026-09-23 at 12 48 58 PM" src="https://github.com/user-attachments/assets/cd331770-1a4f-41b0-b20d-ba0bad18a6b1" />


  **MODEL GRAPH:**
  
<img width="713" height="467" alt="WhatsApp Image 2026-09-23 at 12 59 13 PM" src="https://github.com/user-attachments/assets/e50f157c-82ee-4a16-8246-99bcab577559" />


  **TABULATION AND CALCULATION:**
 
<img width="800" height="564" alt="WhatsApp Image 2026-09-23 at 12 53 31 PM" src="https://github.com/user-attachments/assets/297c0d39-5fc1-4736-883a-7af946e589fb" />

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**

<img width="781" height="547" alt="WhatsApp Image 2026-09-23 at 12 59 40 PM" src="https://github.com/user-attachments/assets/92f1e960-4cff-4bf0-b14b-7b3b25e57eb8" />

  **MODEL GRAPH:**
  
<img width="800" height="465" alt="WhatsApp Image 2026-09-23 at 1 01 47 PM" src="https://github.com/user-attachments/assets/fbf93482-ea68-4279-aeee-ee4bbb2774f5" />


  **TABULATION:**
  
<img width="800" height="562" alt="WhatsApp Image 2026-09-23 at 12 59 56 PM" src="https://github.com/user-attachments/assets/50939f10-9b3a-4d43-8510-47f84194c766" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
<img width="652" height="488" alt="WhatsApp Image 2026-09-23 at 1 02 22 PM" src="https://github.com/user-attachments/assets/e01e096b-ae6b-46b2-865c-e8443f168014" />


  **MODEL GRAPH:**
  
<img width="799" height="576" alt="WhatsApp Image 2026-09-23 at 1 02 40 PM" src="https://github.com/user-attachments/assets/412db040-3ae9-45af-a27d-d9d1c00ebb27" />


  **TABULATION:**
  
<img width="695" height="800" alt="WhatsApp Image 2026-09-23 at 1 04 32 PM" src="https://github.com/user-attachments/assets/88dd0fd3-f500-445e-8876-f8b3b311a398" />

**GRAPH:**

<img width="1061" height="1490" alt="WhatsApp Image 2026-09-23 at 1 12 26 PM" src="https://github.com/user-attachments/assets/c0f5a551-de7b-410f-b3c4-212ff0e1f2da" />

<img width="1129" height="1552" alt="WhatsApp Image 2026-09-23 at 1 13 05 PM" src="https://github.com/user-attachments/assets/639c26cb-964e-444e-aad0-1fe6e6ca9d0c" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**

<img width="477" height="800" alt="WhatsApp Image 2026-09-23 at 1 08 13 PM" src="https://github.com/user-attachments/assets/a78e7eb7-7074-4ffc-a2f5-43c31327046c" />

<img width="800" height="610" alt="WhatsApp Image 2026-09-23 at 1 10 13 PM" src="https://github.com/user-attachments/assets/e8be2bd5-55b7-4135-b940-fff428522d0e" />


  **MARK SPLITUP:**

  <img width="800" height="738" alt="WhatsApp Image 2026-09-23 at 1 09 25 PM" src="https://github.com/user-attachments/assets/e8422f01-e73e-4da3-acc8-f6d9b025f5fd" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






