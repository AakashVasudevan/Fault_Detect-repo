# Fault_Detect-repo
## Kaggle Project - Electrical Fault Detection

Fault detection on a transmission system modelled in MATLAB. 

Training Dataset:
This file contains the dataset to classify the types of fault.
Inputs - [Ia,Ib,Ic,Va,Vb,Vc]
Outputs - [G C B A]
Examples :
[0 0 0 0] - No Fault
[1 0 0 1] - LG fault (Between Phase A and Gnd)
[0 0 1 1] - LL fault (Between Phase A and Phase B)
[1 0 1 1] - LLG Fault (Between Phases A,B and ground)
[0 1 1 1] - LLL Fault(Between all three phases)
[1 1 1 1] - LLLG fault( Three phase symmetrical fault)

Test Dataset:
The file contains the dataset to detect faults in a power system.
Inputs - [Ia,Ib,Ic,Va,Vb,Vc]
Outputs - 0 (No-fault) or 1(Fault is present)
