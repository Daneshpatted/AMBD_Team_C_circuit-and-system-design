# PMSM Sensorless control
# Requirements

## Three phase inverter modelling

High Level Requirements
| ID | Description |
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
|HLR_1|to move from stationary axis to rotational axis|
|HLR_2|come up with equations required to build the model and building the equations model in simulink|


Low Level Requirements
|ID|Description|
|-----|-----|
|LLR_1.1|to make use of clark transform to move from abc axis to alpha and bheta axis|
|LLR_1.2|to make use of park transform to move from alpha and bheta axis to d-q axis|
|LLR_2.1|makeing blocks use of basics blocks available to implement it|
|LLR_2.2|analysing the output from the block|



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


 
 ## Equations 
 
# INVERTER
Van=Vdc/3(2Vao-Vbo-Vco)
Vbn=Vdc/3(2Vbo-Vco-Vao)
Vcn=Vdc/3(2Vco-Vao-Vbo)

 
 
 
 
 
 
 
