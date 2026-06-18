
TITLE: An-Effective-Switching-Table-Based-DTC-of-Five-Phase-PMSM-for-Reduction-of-Torque-Ripples

Paper ID: 10348

Authors:

Name: Puli Rajanikanth   

Affiliation: National Institute of Technology Warangal, Warangal, Telangana.

Name: Vinay Kumar Thippiripati  

Affiliation: National Institute of Technology Warangal, Warangal, Telangana.

About Repository:

This repository contains the MATLAB simulation files which can be used to reproduce the results presented in our paper titled "An-Effective-Switching-Table-Based-DTC-of-Five-Phase-PMSM-for-Reduction-of-Torque-Ripples".

ABSTRACT:

Higher torque and flux ripples exist in conventional direct torque control (DTC) of five-phase permanent magnet synchronous motor (5-ϕ PMSM) drive due to application of single voltage vector over entire control period. Duty-cycle based DTC techniques are proposed for 5-ϕ PMSM recently to achieve superior steady-state responses. However, most of the duty cycle-based schemes are complex. To suppress the ripples in flux and torque, an effective switching table-operated DTC is proposed in which selection of active voltage vector (AVV) for decoupled torque and flux control is introduced for 5-ϕ PMSM. Secondly, the selected AVVs for torque and flux control are applied along with a null vector in two consecutive samples, respectively based on effective duty control scheme. The duty cycles of selected AVVs are determined to meet the reference flux and torques in respective control intervals, which ensures reduced flux and torque ripples. When voltage vector for torque control is applied, the effect on flux is negligible and vice versa, which achieves a decoupled flux and torque control. The proposed DTC is verified experimentally and compared with conventional DTC, conventional model predictive current control (MPCC) scheme, and a duty-cycle control based MPCC for 5-ϕ PMSM. The proposed DTC achieves significant reduction in torque and flux ripples while maintaining comparable dynamic response and computational burden.

Description of all the files:

Four different schemes are compared in this research work. The four schemes used in this paper are

1) Conventional DTC scheme with the file name Conventional DTC.slx
2) Conventional MPCC scheme with the file name Conventional MPCC.slx
3) Duty based MPCC scheme with the file name DBMPCC.slx
4) the proposed DTC scheme with the file name Propsed DTC.slx

These files can be used to reproduce all the results presented in the research article effectively.

Software Requirements:

MATLAB R2022a or later.

Hardware Requirements:

dSPACE1104 controller, five-phase PMSM, five-phase two-level inverter 

Specifications:

Lamda_PM=0.5

Rs=1.45

Ls=0.022

Lls=0.0022

P=4

J=0.004

Mod_Lamda_s_ref=0.5

Ts=140e-6




