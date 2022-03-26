# PMSM Sensorless control

# Abstract
The aim of this project is to find the rotor position speed and torque without the use of sensors. Initially taking optimum parameters into consideration and feeding these values in the inverter model that we have designed we obtain the line voltages. With the Clark and Park transformation we transform these values in d-q reference frame. Further rearranging the terms, we solve for currents flowing through the motor i.e., id and I-q currents.




# REQUIREMENTS

## Three phase inverter modelling

High Level Requirements
| ID | Descriptions
|----|-------------|
|HLR_1|To convert direct dc voltage to three phase ac voltage|
|HLR_2|To come up with the simulink model and thereby verify the result |

Low Level Requirements
| ID | Description |
|----|-------------|
|LLR_1.1|To come up with the required circuit diagram|
|LLR_1.2|To analyse the circuit and writeup thr required equations|
|LLR_2.1|Various simulink blocks are to be used and thereby modelling is done according to the equation|





## Transmission from a,b,c(stationary) to d-q(rotational)axis

High Level Requirements
|ID|Description|
|-----|------|
|HLR_1|To move from stationary axis to rotational axis|
|HLR_2|Come up with equations required to build the model and building the equations model in simulink|


Low Level Requirements
|ID|Description|
|-----|-----|
|LLR_1.1|To make use of clark transform to move from abc axis to alpha and theta axis|
|LLR_1.2|To make use of park transform to move from alpha and theta axis to d-q axis|
|LLR_2.1|Makeing blocks use of basics blocks available to implement it|
|LLR_2.2|Analysing the output from the block|



## Calaculation of speed ,theta,current parameters by modelling


High Level Requirements

|Id|Description|
|--|------------|
|HLR1 |To come up with equivalent circuit equations of motor|
|HLR2 |   To model the motor using various equations obtained from circuit diagram|



Low Level Requirements
|Id|Description|
|--|------------|
|LLR1.1 |To understand the equivalent circuit diagram using basic components|
|LLR1.2  |    To come up with equivalent circuit equations using electrical laws|
|LLR2.1|To find various parameters like speed ,torque,current and thereby estimate the position of the rotor.|
 |LLR2.2 |   To model all these parameters in simulink further verify the results.|
 
 ---------------------------------------------
 
# SWOT ANALYSIS
 ![swot analysis](https://user-images.githubusercontent.com/98873064/160094517-04328b0e-fade-42ab-83be-143130addfd8.png)
 
 --------------------
 
 
# 5W's & 1H

## Where:
While designing the Permanent Synchronous Motor.

## Why:
To reduce the cost of position sensor.

## What:
To sensor the position of rotor without using the sensor.

## Who:
Circuit design engineer.

## When:
When there is a need to reduce the cost of sensor. 

## How:
By transforming a,b,c to dq axis and thereby finding the parameters.

-------------------------------

 # Block Diagram
 ![Block_diagram](https://user-images.githubusercontent.com/98873064/160232275-b481eb84-29c3-42f9-951a-b9a1bbc7868f.png)
 
 --------------------------


 # FLOWCHART
 ![Flow-chart-of-implementing-FOC-forPMSM](https://user-images.githubusercontent.com/98882146/160226447-0f520a37-c15a-4e8b-92f9-e20a579dd457.jpg)
 
----------------------

# EQUATIONS
 
## Inverter

* Vao=Van+Vno
* Vbo=Vbn+Vno
* Vco=Vcn+Vno
* Van=Vdc/3(2Vao-Vbo-Vco)
* Vbn=Vdc/3(2Vbo-Vco-Vao)
* Vcn=Vdc/3(2Vco-Vao-Vbo)

## Clark and Park Transformation
![Clark and park transform](https://user-images.githubusercontent.com/98873064/160111518-3b7fbe1b-1bcc-4ef4-8d00-5e8cb0dbeaf9.png)

 ## Motor Modelling
 ![image](https://user-images.githubusercontent.com/98873064/160110148-a39cbb56-cc90-4d20-af6c-c23e220b5ac1.png)
 
 ------------

 
 # Output
 
 # VSI OUTPUT
 
 ![VSI_Output](https://user-images.githubusercontent.com/98873064/160233486-3545ef90-df8a-4c9f-805e-057761bdf914.png)
 
 
 # Id_Iq OUTPUT
 
 ![id_iq_Output](https://user-images.githubusercontent.com/98873064/160233511-c6a06f26-8fae-454a-a63b-096b97a88758.png)


# SPEED OUTPUT

![Rotor_speed_output](https://user-images.githubusercontent.com/98873064/160233548-0e71d95c-3125-4089-9534-508558a9d71a.png)


# Rotor position output

![rotor_position_output](https://user-images.githubusercontent.com/98873064/160233646-fbdf8e25-34f1-4301-b07b-c437a7b9f35d.png)



 
 
