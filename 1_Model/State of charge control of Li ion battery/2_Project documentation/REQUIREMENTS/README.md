# STATE OF CHARGE CONTROL OF LITHIUM ION BATTERY
## REQUIREMENTS

## ABSTRACT
  To propose a solution for the control of the state-of-charge of a lithium-ion (Li-ion) battery cell. The aim is to design a control scheme able to charge the battery in a fast way and without violating the battery safety constraints on the different electrochemical parameters of the electrochemical model (ECheM) of the battery. The proposed solution is based on a computationally efficient formulation of the reference governor (RG) which has been designed on the basis of a reduced equivalent-hydraulic model (EHM) of the ECheM. Using appropriate suitable safety margins, the satisfaction of the constraints on the EHM ensures the satisfaction of the constraints of the ECheM. Simulation results obtained on an accurate simulator show that the proposed method, if compared with classical charge strategies, is able to considerably increase the charge performance while ensuring the satisfaction of the constraint	.

## INTRODUCTION
   In recent years, both academia and industry have devoteda considerable amount of efforts to obtain batteries withbetter performance and lifetime. The research on batteriesincludes several aspects, ranging from the synthesis ofnew materials to the development of battery-managemen systems (BMSs) which improve performance. In particular, it is expected that advanced BMSs will play a keyrole in the future of lithium-ion (Li-ion) batteries. Thestarting point of this research line consists in the useof electrochemical  to describe the battery internal state as opposedto the classical use of equivalent electric circuits. Theseelectrochemical states provide physical insight on the processes that may limit the battery performance and lifetime.Consequently, controlling these states has the potentialto considerably increase the battery performances (e.g.capacity and time of recharge) while keeping safe operation conditions throughout the battery life .
   
## HIGHER LEVEL REQUIREMENTS
|HLR_ID|HIGHER LEVEL REQUIREMENTS|
|--|--|
|HLR01| It shall have a DC voltage source|
|HLR02|It shall have a battery|
|HLR03|It shall have a ideal switch|
|HLR04|It shall have a bus|
|HLR05|It shall have a NOT gate|

## LOWER LEVEL REQUIREMENTS
|LLR_ID|COMPONENTS|DESCRITION|
|--|--|--|
|LLR01|DC Voltage source|Converts the electrical energy|
|LLR02|Battery|prevents current and voltage from over charging and discharging|
|LLR03|Ideal switch|used for charging and discharging|
|LLR04|Bus|The bus selector block output the elements u select from the input bus|
|LLR05|NOT Gate|used to check the conditions|

## SWOT ANALYSIS

![sandhya](https://user-images.githubusercontent.com/99087988/160098631-656fae52-7c5e-48d0-a5e2-ec5ab1579c7b.png)

# 4W"S AND 1H
# WHAT
  It is used to converts the some other energy into electrical energy
# WHEN
  It is used when overcharging and discharging
# WHERE
  Applied in all the electrical equipments
# WHY
  To prevents the power from over charging and over discharging
# HOW
  It will shows the charging power

  

   
  




