# CHARGING AND DISCHARGING OF THE BATTERY

# Abstract
At any given time, discharging or charging is taking place inside a battery. Charged ions composed of sulphate and hydrogen make up the electrolyte solution.
The hydrogen ions have a positive charge, while the sulphate ions have a negative charge. When an electrical load (starting motor, headlight, etc.) is applied to a battery's terminals, the sulphuric acid breaks down, and the resulting sulphate ions move to the negative plates, where they react with the active material, releasing their negative charge by ionisation. The battery will either discharge or produce electrical energy as a result of this.DC current is created by an excess electron flow from the negative side of the battery, through the electrical device, and back to the positive side of the battery. The electrons travel back through the cells and re-attach themselves to the positive plates once they reach the positive battery terminal. The discharge process continues until the battery is completely depleted and chemical energy is no longer available.
    The chemical process that occurred during discharge is reversed when a battery is charged. The electrical energy that is utilised to charge a battery is transformed to chemical energy and stored within the battery. The voltage produced by battery chargers, such as alternators and generators, is higher 
than the battery's open circuit voltage.The battery may overheat if the charging current exceeds the normal absorption rate, causing the electrolyte solution to bubble and release dangerous hydrogen gas. 

# Objectives 
- To analyse the charging and discharging circuits seperately
- To integrate both the models to obtain the graphs for voltage, current, SOC for the circuit.

# High Level Requirments
| Id          |  High Level Requirements  |    status  |
| :--        | :--          |   :--     |
| HLR1        | To analyse and build the circuit | Implemented |
| HLR2        | Provide external source for charging circuit |  Implemented |
| HLR3        | Integration of charging and discharging circuits | Implemented |

# Low Level Requirements
| Id          |  Low Level Requirements  |    status  |
| :--        | :--          |   :--     |
| LLR1        | To give the required gate pulse to the mosfet | Implemented |
| LLR2        |The SOC should decrease during discharging period and increase during charging period | Implemented |
| LLR3       | To obtain required graph for SOC, current and voltage  | Implemented |

# SWOT analysis
 ## Strength:
 - Demonstrates the process of battery loosing voltage and gaining voltage / energy.
 - It is used in automotive applications and home applications to keep a track on battery charge and discharge.
 - - Efficiency of the battery can be increased by analysing.
 ## Weakness:
 - Complexity in circuit.
 ## Opportunities:
 - It is used in automotive applications and home applications to keep a track on battery charge and discharge.
 ## Threat:
 - Malfuunctioning of one single component can ruin the whole circutry.
# 4W's and 1H
 ## What: 
 A circuit that demonstrates the variation of voltage , current and SOC during charging and discharging of the battery
 ## When:
 To track the voltage, SOC and current of a battery during charge and discharge period. 
 ## Who:
 Reasearchers, Automotive industrialists.
 ## Where:
 Automotive sector, Industries, for students to understand the logic of battery charge and discharge 
 ## How:
 Using Matlab-Simulink
# Circuit diagram for charging circuit
![charge](https://user-images.githubusercontent.com/98872514/160190926-087dcda9-610e-4db6-8348-68be883587f1.jpeg)


# Circuit diagram for discharging circuit
![discharge](https://user-images.githubusercontent.com/98872514/160190970-91f4ae1f-3fb7-43a3-a829-307c39685bdb.jpeg)




 


