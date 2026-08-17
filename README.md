# Catacombs_Visual-Inertial_Data
This dataset contains visual inertial data for an experiment at the Catacombs section of an underwater cave in Devil's Eye Cave System, FL, USA.

The data are located at: 
``` 
https://huggingface.co/datasets/afrl-uw/Catacombs_Visual-Inertial_Data
```

The Software Pipeline described at:
``` 
https://github.com/AutonomousFieldRoboticsLab/Catacombs_SW_Pipeline
```

One dive was performed at the Catacombs section of the  Devil's Eye Cave System with durations of 55 (2024), while data were recorded for 39 minutes.
Calibration targets (4-by-2 and 5-by-4) were deployed in two different locations and stayed fixed for the duration of the dive.

The directory structure is as follows:

- Configurations\
--  april_3x5_10x10cm.yaml \
--  april_4x5_4x4cm.yaml\
--  GoProCamIMU.yaml
- Ros2Bags\
--  2024_Center/\
--  2024_Left/\
--  2024_Right/
- COLMAP_SVIn2_MNemo_Trajectories\
--  2024_Center_Colmap.txt \
--  2024_Left_Colmap.txt \
--  2024_Right_Colmap.txt \
--  2024_Center_SVIn2.txt \
--  2024_Left_SVIn2.txt \
--  2024_Right_SVIn2.txt  \
--  CatacombsLC.txt
- Videos\
--  2024_Center/\
--  2024_Left/\
--  2024_Right/
- WaterDepthProfiles\
--  2024_Perdix.csv/
   
### Citation
If find this dataset useful, please cite:
