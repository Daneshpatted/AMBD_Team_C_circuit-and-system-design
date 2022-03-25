# Performance Evaluation of Cascaded H Bridge Multilevel Inverter using Multicarrier PWM Techniques

# Abstract
Various multicarrier pulse width modulation (PWM) techniques suitable for high power converter and capable of generating multilevel output voltage waveforms are discussed. Several interesting characteristics of the multicarrier PWM techniques are revealed. A multicarrier PWM technique combining the disposition and the phase shifted concepts is considered. The performance of the various techniques with respect to the total harmonic distortion (THD) of the output line voltage in the linear and using PMSM motor load is reported. Two distortion factors associated with PWM technique and PMSM Motor load and output filtering and for different amplitude modulation indices are presented and used as a measure of comparison for the techniques under consideration.	

# Introduction
- The main function of the inverter is to convert DC input voltage to a AC output voltage of the desired magnitude. The output voltage waveforms of the ideal inverters should be sinusoidal, however the waveform of the particle inverters are non sinusoidal and contains different harmonics.
- By using high speed power semiconductor devices and by using different switching techniques we can reduce the harmonic content in output voltage.
- The inverters generally use pulse width modulation control signals to provide an AC output signal.
- PWM is commonly used in applications like motor speed control, converters audio amplifiers etc. And also PWM is used to adjust voltage applied to the motor.
- There is no single PWM method which can suite for all applications. As per the advanced technology in solid state power electronic devices and microprocessors, various pulse width modulation techniques have been developed for different industrial application.

# Objectives
- To control the inverter output voltage by using PWM technique.
- To reduce the harmonics content in the output voltage by using different PWM techniques. 
- Analyze the THD in multilevel inverters using multicarrier PWM technique, through MATLAB simulations. 
- Analysis of Inverter fed PMSM motor (motor torque, speed and torque ripple).
- THD analysis of inverter fed PMSM motor. 


# High Level Requirments
| Id          |  High Level Requirements  |    status  |
| :--        | :--          |   :--     |
| HLR1        | The model should control the inverter output voltage by using PWM technique   | Implemented |
| HLR2        | The model should reduce the harmonics content in the output voltage |  Implemented|
| HLR3        | The model should give the analysis of H bridge cascaded multilevel inverter fed induction motor (motor torque, speed and torque ripple) | Implemented |

# Low Level Requirements
| Id          |  Low Level Requirements  |    status  |
| :--        | :--          |   :--     |
| LLR1        | The pwm techniques such as PD,POD and APOD are to control the inverter output  | Implemented |
| LLR2        | As we increase the level of the inverter the value of the THD decreases  | Implemented |
| LLR3       | When motor connected as step load and constant load the motor torque,speed and torque ripple will varies  | Implemented |

# Swot Analysis
![swot](https://user-images.githubusercontent.com/98802184/160176719-cbbf9f5d-830e-4e89-a219-7e74a085f881.PNG)
