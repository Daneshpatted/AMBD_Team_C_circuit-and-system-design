# DC MOTOR SPEED CONTROL
Design the dc motor model with equations and control the speed and torque of the dc motor by varying the voltage.
# Requirements
# High Level Requirements
# To control the speed,torque  of dc motor
|ID|DESCRIPTION|
|---|---|
|HLR1|To analyze circuit equation|
|HLR2|To model the motor using analyzed equation|
|HLR3|To control the speed torque of the motor|

# Low level Requirements
|ID | DESCRIPTION|
|---|---|
|LLR1|To understand electric circuit diagram and equation  using basic components|
|LLR2| To model the parameters in simulink and test the result|
|LLR3| control parameter of motor using varying voltage|

## SWOT Analysis

![swotanalysis](https://user-images.githubusercontent.com/89115879/160097410-1357c70b-a3b8-4579-b692-ef1964fbe303.PNG)

## 4 w & 1H
# What
* To design a dc motor model 
# Why
* to control speed and torque by varying it's voltage.
# How
* To solve the mathematical equation and model according to equation.
# When
* It is used in the application whenever any dc motor controlled items required to control its speed torque
# where
* In automobile and machinery which need dc motor 

# Observation
Here we use few formulas to calculate speed and torque.
# Fomula
* Va = Raia + La +Kaфꙍ
* Kaфia = J + Bꙍ +T1
* Using these formulas, we get Torque and speed values which is later compared with the MATLAB simulation graph.
Later we take a graph to see how the current is varying with the change in torque. 

# Motor parameter
Motor parameters with the parameters: 
* Rated power = 2 kW Rated
* armature voltage = 125 V 
* Rated armature current = 16 
* A Rated speed = 1750
* vrpm Ra = 0.24 Ω, La = 18 mH, Kaφ = 0.6699, J = 0.5 kgm2, Tl = 0.01 + 3.189× 10−4 × ω2 m. 

* Obtain the speed and torque waveforms.

Version 1 dc motor

* Version 1 is modelled using basic dc motor which is in website of the paramters given by them
# Dc motor 
![dc motor basic version1](https://user-images.githubusercontent.com/89115879/160168952-3e6ccfa3-8923-4da0-9d21-db5642e508b1.PNG)
# Dc motor basic subsystem
![dc motor subsystem](https://user-images.githubusercontent.com/89115879/160169092-9d853192-7e63-4b0b-82e2-3a2f03836121.PNG)
# waveform
![waveform](https://user-images.githubusercontent.com/89115879/160169131-d4200eb9-6a46-455d-9a68-2a2a29dfc0c6.PNG)

# Reference for the model
 
simulinkmodelonine.slx is modelled by referring https://ctms.engin.umich.edu/CTMS/index.php?example=MotorSpeed&section=SimulinkModeling