# Permanent magnet synchronus generator Based on windenergy conversion system.

# Abstract:
The presented work proposes a suitable power converter design for a Wind Energy Conversion System (WECS) connected to a constant speed Permanent Magnet Synchronous Generator (PMSG) for MPPT. In the present work energy is derived from WECS and fed to the PMSG. The output of the generator is rectified using an uncontrolled three phase diode-rectifier and a constant value is achieved using a open loop DC-DC converter. In order to enhance the efficiency of a wind energy conversion system (WECS), the maximum power point tracking (MPPT)simulation algorithm is usually employed. This paper presents an optimal algorithm to extract the maximum available power under a constant wind speed , which is applied in a permanent magnet synchronous generator (PMSG)-based WECS.The algorithm that is used in this project is Perturb and Observer. Here we are open loop control because we are considering wind speed as constant.Simulation of proposed scheme is presented by MATLAB-Simulink model and the results demonstrate the validity of the developed modelThe whole system is simulated using MATLAB/ Simulink and the results are presented to demonstrate the veracity of the developed control scheme.

# Introduction:
Nowadays, PMSGs are most popular for power-generation, as they have high efficiency. For instance, the electrical efficiency of PMSGs is higher than the synchronous-generators (SG’s) in the moderate-size power marine diesel generator-sets. As PMSG don’t comprise excitation control, voltage-regulation is island-operation is challenging. The flux-density of permanent magnet (PM) reduces with the rise in temperature, so voltage-control become complicates. Some of the difficulties of PMs are high cost and handling while manufacturing. The variable-speed operation of the WECS is essential for extracting maximum wind power.But here we are doing for constant speed for MPPT. A modern control based tracking of power or torque helps to achieve best utilization of wind-energy. Control strategies are developed based on wind-velocity to acquire required shaft speed. These schemes involve high cost and reduced reliability for a small scale WECS. For standalone operation, load-side converter voltage needs to be controlled in terms of amplitude and frequency. Grid connected PMSG based WECS are also proposed and implemented. Probability to attain less pole-pitch permits the machine to run at low speed and removes the gearbox or allows using single-stage gear for more compact design. This project reviews various PMSG techniques with the aim of maximum power
generation.
Wind energy conversion systems have been attracting wide attention as a renewable energy source due to depleting fossil fuel reserves and environmental concerns as a direct consequence of using fossil fuel and nuclear energy sources. Wind energy, even though abundant, varies continually as wind speed changes throughout the day. The amount of power output from a wind energy conversion system (WECS) depends upon the accuracy with which the peak power points are tracked by the maximum power point tracking (MPPT) controller of the WECS control system irrespective of the type of generator used. This study provides a review of past and present MPPT controllers used for extracting maximum power from the WECS using permanent magnet synchronous generators (PMSG), squirrel cage induction generators (SCIG) and doubly fed induction generator (DFIG). It is direct driven permanent magnet synchronous generator.

# Objective:

Main objective of this thesis is to design a suitable permanent magnet synchronous generator working with a vertical axis wind turbine.

# Benifits:

1)reliability

2)compact size

3)loss reduction

4)higher power density 

5)finally optimal efficiency

# 4W'S & 1H:

# why:

Synchronous generators are commonly used for variable speed wind-turbine applications, due to their low rotational synchronous speeds that produce the voltage at grid frequency. Synchronous generators can be an appropriate selection for variable speed operation of wind turbines.

# What:

The growing trends in wind energy technology are motivating the researchers to work in this area with the aim towards the optimization of the energy extraction from the wind and the injection of the quality power into the grid.

# When:

whenever the power required then it is connected with the grid system.

# Where:
It is used where ever the turbines gets connected to the wind system.

# How:
This stator magnetic field or "stator field" appears as a steady rotating field and spins at the same frequency as the rotor when the rotor contains a single dipole magnetic field. The two fields move in "synchronicity" and maintain a fixed position relative to each other as they spin.

# SWOT Analysis:

![pp](https://user-images.githubusercontent.com/93932674/160075246-f4aa72a8-0eec-4213-900a-717d5171124d.jpg)

# Requirements:
# High Level Requirements:

| RID | DESCRIPTION | STATUS |
|:--:|:--------:|:----:|
|HLR1|wind turbine|implimented|
|HLR2| generator|implimented|
|HLR3| interconnection apparatus|implimented|
|HLR4|control systems|implimented|


# Low level Requirements:

| RID | DESCRIPTION | STATUS |
|:--:|:--------:|:----:|
|LLR1|voltage|implimented|
|LLR2|current|implimented|
|LLR3|wind speed|implimented|
|LLR4|volatage across dc load|implimented|









