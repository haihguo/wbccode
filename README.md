# wbccode
Code Descriptions of the manuscripts "Onshore Intensification of Subtropical Western Boundary Currents in a Warming Climate"

This document provides a detailed description of the code used in the manuscript titled "Onshore Intensification of Subtropical Western Boundary Currents in a Warming Climate." If you have any questions or encounter any uncertainties, please feel free to contact Dr. Haihong Guo, a Postdoctoral Researcher at Laoshan Laboratory (Email: ghh@stu.ouc.edu.cn).

The Python (.py) codes were executed using Python 3.10.8 and required additional packages downloaded from conda-forge (listed in the codes). The code utilized data located in the "data" directory, which includes all the input data necessary for the execution. Additionally, the "mitgcm" directory contains configurations for the idealized model runs.

Code Descriptions:

trend_in_obs.py: Calculates the observed onshore intensification of global subtropical Western Boundary Currents (WBCs).
trend_in_model.py: Calculates the simulated onshore intensification of subtropical WBCs under global warming.
cal_wsc_temp_kc.py: Computes changes in surface wind and oceanic stratification under global warming in the North Pacific.
cal_wsc_temp_allwbcs.py: Computes changes in surface wind and oceanic stratification under global warming for other WBC runs.
cal_mitgcm_input.py: Calculates the input files required for running MITgcm.
read_mitgcm.py: Reads and processes the output generated from the MITgcm run.
cal_mitgcm_v_integrate.py: Calculates the vertical integrated meridional velocity from MITgcm output.
read_mitgcm_narrow_topo.py: Reads the MITgcm output with a narrow topography slope.

If you require any further clarifications or assistance, please do not hesitate to reach out to Dr. Haihong Guo.
