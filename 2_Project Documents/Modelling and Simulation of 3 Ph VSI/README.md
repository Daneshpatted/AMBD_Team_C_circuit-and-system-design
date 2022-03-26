# " Modelling And Simulation Of 3Ph Voltage Source Inverter "

##  Description

Power electronics and electrical machines nowadays offer an extremely wide range of industrial applications. Their modeling and simulation are also a great interest
to engineers and scientists. In some simulation applications, nonlinear of the power electronic devices is neglected due to its simplicity. Therefore,the performance of the control system obtained is not the same as experimental results. In this paper, a model of two-level three-phase voltage source inverter having its voltage drops is proposed. The proposed inverter was tested with RL load using space vector pulse width modulation and direct torque control of three-phase induction motors.

## Features

Controlling strategies of the three-phase voltage-source inverter (VSI) are divided into two; 
voltage control and current control. The voltage controlled VSI uses the phase angle between the inverter’s output voltage and the grid voltage to control the flow of the power. Current controlled VSI uses the active and reactive components of the injected current into the grid and use the pulse width modulation (PWM) techniques to control them. Voltage controllers are more sensitive to the small phase errors but if the grid voltage is distorted large harmonic currents may appear. Current controllers have faster response and less sensitivity to the distortion in the grid voltage.

## Objectives
  *  To review model of an ideal  three-phase voltage source inverter.
  *  To propose model of three-phase voltage source inverter including the pole voltage,phase Voltage,phase Current.
  *  To verify the effectiveness of the proposed work by applications for RL load.

  
## Working of 3 ph VSI

  * The voltage source inverter is defined as the inverter which takes a variable frequency from a DC supply. 
  * The input voltage of the voltage source inverter remains constant, and their output voltage is independent of the load.The magnitude of the load current depends on     the nature of the load impedance.
  * The voltage source inverter use self-commutated device like MOSFET, IGBT, GTO, etc. It is operated as a stepped-wave inverter or apulse width modulation. When the     voltage source inverter is operated as a stepped-wave inverter, then the transistor is switched in the sequence of their number with a time difference of T/6.
  * The each of the transistors is kept on for the duration of T/2, where T is the period for one cycle. The waveform of the line voltage is shown in the figure below.
  * The frequency of the inverter is varied by varying T, and the output voltage of the inverter is varied by varying DC input voltage.When the supply is DC, then the     variable DC input is obtained by connecting a chopper between DC supply and inverter.
  * When the supply is AC, then the DC input voltage is obtained by connecting the controlled rectifier between the AC supply and inverter shown in the figure             below.The capacitor C filter out the harmonics in DC link voltage.  
  
## Resources 
  IEEE papers/
  
##  5W's And 1H

  ## What  
    * A voltage source inverter or VSI is a device that converts unidirectional voltage waveform into a bidirectional voltage waveform.
    * It is a converter that converts its voltage from DC form to AC form. An ideal voltage source inverter keeps the voltage constant through-out the process.
   
  ## Where
    * A three-phase square wave inverter is used in a UPS circuit and a low-cost solid-state frequency charger circuit.
    
  ## When 
     * A three-phase square wave inverter is used in a UPS circuit and a low-cost solid-state frequency charger circuit.
  
  ## Who  
     * in UPS, induction heating, HVDC transmission lines, adjustable speed ac drives, etc.  
     * The power can be transmitted across the network with the help of three different currents which are out of phase with each other.
     
  ## How   
     * A voltage source inverter or VSI is a device that converts unidirectional voltage waveform into a bidirectional voltage waveform,and it is a converter that    converts its voltage from DC form to AC form. An ideal voltage source inverter keeps the voltage constant through-out the process.
     
## SWOT Analysis

![image](https://user-images.githubusercontent.com/98837660/160236574-85736a89-4332-4e59-8817-fe5f47badca0.png)

  1. Strengths.
 
   * It converts a DC i/p into an AC output. It includes three arms which are usually delayed through 120° of an angle to produce a 3 phase AC supply.
   * The power can be transmitted across the network with the help of three different currents which are out of phase with each other.
   * More than one motor can be operated with a single voltage source inverter.
   * Occupies less area, the output voltage is independent of the load that is used.

 2. Weakness.
 
   * Less speed and the input power factor is less i,e 1s.
   * The low internal impedance of a DC source.
   * Short circuit protection is not possible.
   *	Low output impedance.
 
 3. Opportunity.
 
   * These have enormous applications such as in UPS, induction heating, HVDC transmission lines, adjustable speed ac drives, etc. 
   * It performs the inverse operation of ac to dc converter.
   * Uninterruptable power supply & AC speed drivers.
   * These inverters are utilized in variable frequency drive applications Used in high-power applications like HVDC power transmission.

   
 4. Threats.
   * Not safe, when a short circuit occurs.
   * No inherent protection is available.
   * less reliable than current source inverter.
  
## Requirements 
 ##  High Level Requirements 
 1. The model shuld give the pole Voltages from the switching functions .
 2. The model should give the Phase voltage from Pole voltages using different functions.
 3. Getting the Three phase voltages and line voltages from the phase voltage and given function.
 4. Getting the three phase current by feeding RL lode with an output frequency of 50 HZ.
 5. Building the model  by using the equations.
   
 ##  Low Level Requirements
 1. Getting Switching functions for the inputs of different frequncy and Aplitudes.
 2. finding the Dc link current from the Switching functions.


## Applications  

1. Power conversion circuit can simplified into output and input variables.
2. Converter topologies can be derived easily by transfer function approach.
3. The strategy to implement gating pulses will become much simpler.
4. Various parameters like current and voltage, load current can be calculated easily
5. For a power conversion circuits there is no need of forming real power electronic models and state equations.

