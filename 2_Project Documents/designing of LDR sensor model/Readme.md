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
