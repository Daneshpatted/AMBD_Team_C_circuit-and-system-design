# STATE OF CHARGE CONTROL OF LITHIUM ION BATTERY
## REQUIREMENTS

## ABSTRACT
   In this paper, a new approach to modeling the  phenomenon of the open circuit voltage (OCV) of lithium-ion batteries and estimating the battery state of charge (SoC) is presented. A characterization procedure is proposed to identify the battery model parameters, in particular, those related to the hysteresis phenomenon and the transition between charging and discharging conditions. A linearization method is used to obtain a suitable trade-off between the model accuracy and a low computational cost, in order to allow the implementation of SoC estimation on common hardware platforms. The proposed characterization procedure and the model effectiveness for SoC estimation are experimentally verified using a real grid-connected storage system. A mixed algorithm is adopted for SoC estimation, which takes into account both the traditional Coulomb counting method and the developed model. The experimental comparison with the traditional approach and the obtained results show the feasibility of the proposed approach for accurate SoC estimation, even in the presence of low-accuracy measurement transducers.
   
## INTRODUCTION
   The estimation of battery state of charge (SoC) has been a topic of high interest in recent literature because it allows the available energy in the batteries and that which can still be stored to be identified. Therefore, it is the main indicator of the system state and its knowledge allows the system security level to be increased (avoiding overcharge and over-discharge situations) and the success rate of optimization algorithms oriented to the maximum performance exploitation to be improved  SoC estimation methods are classified in [4] as direct methods (such as open circuit voltage estimation, Coulomb counting, and electrochemical impedance methods) and indirect methods (such as those based on artificial intelligence, adaptive filters, and models . The advantages and disadvantages of the different methods and the related open issues are also analyzed. Among them, the main problems are related to the estimation algorithm’s computational cost and not zero-mean error noises, due, for example, to measurement sensors drifting or non-correct modeling of the  phenomenon.
   
## HIGHER LEVEL REQUIREMENTS
|HLR_ID|HIGHER LEVEL REQUIREMENTS|
|--|--|
|HLR01| It shall have a DC voltage source|
|HLR02|It shall have a battery|
|HLR03|It shall have a ideal switch|
|HLR04|It shall have a bus|
|HLR05|It shall have a NOT gate|

## LOWER LEVEL REQUIREMENTS
|LLR_ID|COMONENTS|DESCRITION|
|--|--|--|
|LLR01|DC Voltage source|Converts the electrical energy|
|LLR02|Battery|prevents current and voltage from over charging and discharging|
|LLR03|Ideal switch|used for charging and discharging|
|LLR04|Bus||
|LLR05|NOT Gate||
   
  


