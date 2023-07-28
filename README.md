# Code Descriptions of the manuscripts "Onshore Intensification of Subtropical Western Boundary Currents in a Warming Climate"

This document provides the code employed in the research manuscript titled "Onshore Intensification of Subtropical Western Boundary Currents in a Warming Climate." For any inquiries or clarifications, please do not hesitate to reach out to Dr. Haihong Guo, a Postdoctoral Researcher at Laoshan Laboratory (Email: ghh@stu.ouc.edu.cn).

The Python (.py) codes were executed using Python 3.10.8 and necessitated additional packages downloaded from conda-forge, which are listed within the codes.  Moreover, the "mitgcm" directory incorporates configurations tailored for the idealized model runs.

The data utilized in the code can be downloaded from Google Drive [https://drive.google.com/drive/folders/1GzvjD_nw_LnyTIyMu57cYJruGkv9uuO9?usp=sharing].

Code Descriptions:

1. trend_in_obs.py: Calculates the observed onshore intensification of global subtropical Western Boundary Currents (WBCs).
2. trend_in_model.py: Calculates the simulated onshore intensification of subtropical WBCs under global warming.
3. cal_wsc_temp_kc.py: Computes changes in surface wind and oceanic stratification under global warming in the North Pacific.
4. cal_wsc_temp_allwbcs.py: Computes changes in surface wind and oceanic stratification under global warming for other WBC runs.
5. cal_mitgcm_input.py: Calculates the input files required for running MITgcm.
6. read_mitgcm.py: Reads and processes the output generated from the MITgcm run.
7. cal_mitgcm_v_integrate.py: Calculates the vertical integrated meridional velocity from MITgcm output.
8. read_mitgcm_narrow_topo.py: Reads the MITgcm output with a narrow topography slope.

If you require any further clarifications or assistance, please do not hesitate to reach out to Dr. Haihong Guo.
