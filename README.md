# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

TRUTH TABLE :

![Screenshot 2024-12-03 120815](https://github.com/user-attachments/assets/b0c37d1c-d88a-4e62-afa8-2aaec0dea87a)

**Procedure**

/* 1.Type the program in Quartus software using Verilog.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.Generate the timing diagram for different input combinations. */



**PROGRAM**

![Screenshot 2024-12-03 120824](https://github.com/user-attachments/assets/2aebd197-b6f9-4609-8a76-01239ae71596)







/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: BARANI S S  RegisterNumber:24900119
*/

**RTL LOGIC FOR FLIPFLOPS**

![Screenshot 2024-12-03 120832](https://github.com/user-attachments/assets/8f85e660-7269-47d2-b554-1b6a99d0387a)


**TIMING DIGRAMS FOR FLIP FLOPS**

![Screenshot 2024-12-03 120840](https://github.com/user-attachments/assets/52c3249d-9686-4206-b3a1-8faffbe12c70)


**RESULTS**

Thus, the JK Flip-Flop is designed, and its functionality is validated using the truth table
and timing diagrams
