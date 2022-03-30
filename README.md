# Dataset Overview
HIT-SM bearing datasets are provided by the sensing and measurement laboratory at School of Mechatronics Engineering, Harbin Institute of Technology, Harbin, PR.China.
This repository contains bearing datasets used in the paper "Multisource cross-domain fault diagnosis of rolling bearing based on subdomain adaptation network".
All the data are the original vibration signals acquired by sensors.
HIT-SM bearing datasets contain failure data of rolling bearings collected under two different test rigs, corresponding to SpectraQuest MFS dataset and  Self-built test rig dataset respectively.
The datasets are publicly available and can be used by anyone for the task of classifying the fault status of rolling bearings.
# SpectraQuest MFS dataset
The experimental data for this dataset was collected through the MFS, a mechanical fault comprehensive simulation test rig developed by SpectraQuest. The diagram below illustrates the specific construction of the MFS test rig, which has a 1hp motor with a maximum speed of 6000r/min. The motor and drive shaft are connected by a flexible coupling to reduce torsional shaft vibration, and the drive shaft and load are supported by two 6205 deep groove ball bearings, with the defective bearing being mounted on the non-driven end of the drive shaft. An SQI608A11-3F/8 accelerometer is mounted on the top of each of the two bearing bases to pick up the vertical vibration signals of the two bearings in this position. In this experiment, the bearings were cantilever loaded with 5kg and vibration signals were collected at a sampling frequency of 51.2kHz.
The dataset contains vibration data at three driving speeds, 600 rpm, 900 rmp and 1200 rmp. Each condition contains seven types of health status: normal (N), slight fault of inner raceway (IR2), moderate fault of inner raceway (IR5), severe fault of inner raceway (IR8), slight fault of outer raceway (OR2), moderate fault of outer raceway (OR5), severe fault of outer raceway (OR8).

![image](https://user-images.githubusercontent.com/102653700/160838078-caf0baa8-8c5c-4a13-8a13-7f56a12a3f94.png)
![image](https://user-images.githubusercontent.com/102653700/160838322-5707e1b0-d14f-4644-acc4-27b78b494b5c.png)



# Self-built test rig dataset
The data for the self-built test bench dataset was collected in the test rig shown in the figure below. Compared to the SpectraQuest MFS bench, this bench uses a more powerful motor and has been loaded with an electric cylinder, which is more flexible and allows for higher radial forces to be applied to the bearings. As a result, the machine structure, operating environment and measurement environment of this test rig are different from those of the SpectraQuest MFS test rig, which has a sampling frequency of 51.2 kHz.
The dataset contains vibration data at three driving speeds, 600 rpm, 900 rmp and 1200 rmp. Each condition contains seven types of health status: normal (N), slight fault of inner raceway (IR2), moderate fault of inner raceway (IR5), severe fault of inner raceway (IR8), slight fault of outer raceway (OR2), moderate fault of outer raceway (OR5), severe fault of outer raceway (OR8).

![image](https://user-images.githubusercontent.com/102653700/160838155-6c361437-3ee4-472e-8eb1-5b8d8ffb519c.png)

# Introduction to data files
For the names of the data files, for example 'IR2_600', the first letter represents fault position, next number represents the size of the circular angle corresponding to the circular part occupied by the fault area in the bearing raceway (2, 5, 8 degree) and the last number represents driving speeds(600,900,1200 rpm). 
