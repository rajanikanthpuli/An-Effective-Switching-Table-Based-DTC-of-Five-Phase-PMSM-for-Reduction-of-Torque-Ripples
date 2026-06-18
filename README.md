
TITLE: An-Effective-Switching-Table-Based-DTC-of-Five-Phase-PMSM-for-Reduction-of-Torque-Ripples

Authors:
Puli Rajanikanth, Student Member, IEEE and Vinay Kumar Thippiripati, Senior Member, IEEE

About Repository:
This repository contains the MATLAB simulation file used and MATLAB CODE in our paper titled "An-Effective-Switching-Table-Based-DTC-of-Five-Phase-PMSM-for-Reduction-of-Torque-Ripples".

ABSTRACT:
Higher torque and flux ripples exist in conventional direct torque control (DTC) of five-phase permanent magnet synchronous motor (5-ϕ PMSM) drive due to application of single voltage vector over entire control period. Duty-cycle based DTC techniques are proposed for 5-ϕ PMSM recently to achieve superior steady-state responses. However, most of the duty cycle-based schemes are complex. To suppress the ripples in flux and torque, an effective switching table-operated DTC is proposed in which selection of active voltage vector (AVV) for decoupled torque and flux control is introduced for 5-ϕ PMSM. Secondly, the selected AVVs for torque and flux control are applied along with a null vector in two consecutive samples, respectively based on effective duty control scheme. The duty cycles of selected AVVs are determined to meet the reference flux and torques in respective control intervals, which ensures reduced flux and torque ripples. When voltage vector for torque control is applied, the effect on flux is negligible and vice versa, which achieves a decoupled flux and torque control. The proposed DTC is verified experimentally and compared with conventional DTC, conventional model predictive current control (MPCC) scheme, and a duty-cycle control based MPCC for 5-ϕ PMSM. The proposed DTC achieves significant reduction in torque and flux ripples while maintaining comparable dynamic response and computational burden.

Software Requirements:
MATLAB R2023b or later.

Simulation file Design Specifications:
Lamda_PM=0.5
Rs=1.45
Ls=0.022
Lls=0.0022
P=4
J=0.004
Mod_Lamda_s_ref=0.5
Ts=140e-6




