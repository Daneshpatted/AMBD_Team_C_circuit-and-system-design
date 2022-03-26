# " modelling of standalone single axis active solar tracker "
# " Designing of LDR Sensor model"
## Description
* An LDR or light dependent resistor is also known as photo resistor, photocell, photoconductor. It is a one type of resistor whose resistance varies depending on the amount of light falling on its surface. When the light falls on the resistor, then the resistance changes. These resistors are often used in many circuits where it is required to sense the presence of light. These resistors have a variety of functions and resistance. For instance, when the LDR is in darkness, then it can be used to turn ON a light or to turn OFF a light when it is in the light. A typical light dependent resistor has a resistance in the darkness of 1MOhm, and in the brightness a resistance of a couple of KOhm
# Resource
* IEEE papers\
# Working of LDR sensor model
* The LDR sensor has a variable resistor that changes according to the intensity of incident ray illuminated onto it. as the intensity of sunlight changes,the resistance and the volatage of LDR sensor changes .
* the output voltage across the resistor is converted into digital signal at the input of the microcontroller .
* based on the TTL input, the servo motor rotates clockwise or anticlockwise  .
* in the LDR sensor the difference between the panel angle and the assumed sun position is calculated. 
* The angles are limited to +-90 degrees
* when 90 degree is reached the LDR sensor outputs a zero irradiance that corresponds to a certain voltage 
# Objectives
* To design a LDR sensor Model
* to make the LDR sensor compatible with other sensors
* to check whether the LDR sensor outputs the correct voltages when the panel angle reaches 90 degree
* to make the servo motor rotate clockwise(cw) or anticlockwise(ccw).
# Requirements 
## High Level Requirements
* HLR1_1 to have a variable resistor that changes the intensity of incident ray illuminated on to it.
* HLR1_2 to convert the output voltage across the resistor into digital signal 
* To Rotate the motor clockwise or anticlockwise
* to have the LDR sensor output a zero irradiance that corresponds to a certain voltage when panel reaches 90 degrees
## Low Level Requirements
* to give TTL input
* to calculate the difference between the panel angle and the assumed sun position
* to limit the panel angles to +-90 degrees
# 4W's and 1H
## What
* to design a LDR sensor Model
## WHY
* To convert the output voltage across the resistor into digital signal and send it to the microcontroller
## When
* when the panel reaches 90 degrees
* when the intensity of the light changes
# Where
* used in smart tracker photo-voltaic (PV) Model
# How
* the LDR sensor contains a variable resistor whose resistance and the voltage changes according to the intensity of sunlight. the output voltage is converted into digital signal and sent as the input to the microcontroller
# SWOT Analysis
## Strengths
* the LDR sensor converts the voltage across the resistor into digital signal
## Weaknesses
* if both the LDR sensors are placed in parallel with the photo-voltaic model than the effective irradiance is similar as a result the smart tracker is unable to perform the proposed sun tracking algorithm
## Oppurtunities
* The LDR sensor can be used in  smart photo- voltaic(PV) panel which is used to solve the proposed sun tracking algorithm
## Threats
* when LDR sensors are placed in parallel with each other than the smart tracker is unable to perform the proposed sun tracking algorithm thus jeopardizing the pv panel thus jeoparadizing the whole system

