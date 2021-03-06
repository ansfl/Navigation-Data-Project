# Introduction

This repository describes the datasets associated with our paper "The Autonomous Platform Inertial Dataset".\
**Paper**: https://ieeexplore.ieee.org/document/9684368 \
**Datasets**: https://drive.google.com/drive/folders/1sbuDlklDdCfcQ0Y6brWcfGyv2iaIlCSU \
**AUV Video**: https://youtu.be/eYm7hBtCGOQ \
**Quadrotor Video**: https://youtu.be/aHmR-gwL3R4 \
**MGV Video**: https://youtu.be/EU95BGAZU_o 

# The Autonomous Platform Inertial Dataset
One of the critical tasks required for fully autonomous functionality is the ability to achieve an accurate navigation solution; that is, to determine the platform position, velocity, and orientation. Various sensors, depending on the vehicle environment (air, sea, or land), are employed to achieve this goal. In parallel to the development of novel navigation and sensor fusion algorithms, machine-learning based algorithms are penetrating into the navigation and sensor fusion fields. An excellent example for this trend is pedestrian dead reckoning, used for indoor navigation, where both classical and machine learning approaches are used to improve the navigation accuracy. To facilitate machine learning algorithms’ derivation and validation for autonomous platforms, a huge quantity of recorded sensor data is needed.
Unfortunately, in many situations, such datasets are not easy to collect or are not publicly available.\
To advance the development of accurate autonomous navigation, we presents the autonomous platforms inertial dataset. It contains inertial sensor raw data and corresponding ground truth trajectories. The dataset was collected using a variety of platforms including a quadrotor, two autonomous underwater vehicles, a land vehicle, a remote controlled electric car, and a boat. A total of 805.5 minutes of recordings were made using different types of inertial sensors, global navigation satellite system receivers, and Doppler
velocity logs. 

# Our Platforms
![Picture1](https://user-images.githubusercontent.com/93155156/143598729-49d08d5b-3712-4dd3-bdfe-7eb3508fc83c.png)
Snapir - autonomous underwater vehicle\
Alice - autonomous underwater vehicle\
Suzuki Jimny\
Shikmona  - marine vessel\
DJI Matrice 300 RTK \
Electric 4WD climbing car

# Summary of Collected Datasets
![Picture2](https://user-images.githubusercontent.com/93155156/143601562-b0227f60-d739-456d-86ae-efa66caabbdd.png)


# The Autonomous Navigation and Sensor Fusion Lab
The Autonomous Navigation and Sensor Fusion Lab (ANSFL) researches questions and challenges in the fields of autonomous navigation, inertial navigation systems, and estimation theory, as well as in related fields. Our research goals are to derive innovative inertial and sensor fusion algorithms, to develop novel inertial navigation system architectures, and to pioneer deep-learning-based navigation approaches.\
**Lab website**:  http://marsci.haifa.ac.il/labs/ansfl/ 
![Picture1](https://user-images.githubusercontent.com/93155156/143600162-787b7824-a863-46e2-ac19-ad6292a7c006.png)

# License
All datasets on this page are published under the [Creative Commons Attribution Version 4 License](https://creativecommons.org/licenses/by/4.0/legalcode)

# Cite Us

@ARTICLE{9684368,
  author={Shurin, Artur and Saraev, Alex and Yona, Mor and Gutnik, Yivgeni and Faber, Sharon and Etzion, Aviad and Klein, Itzik}, \
  journal={IEEE Access}, \
  title={The Autonomous Platforms Inertial Dataset}, \
  year={2022}, \
  doi={10.1109/ACCESS.2022.3144076}}
  

# Papers
**Quadrotor Dataset**: 
1. Or B., Bobrovsky B.-Z. and Klein I., Kalman Filtering with Adaptive Step Size Using a Covariance based Criterion , IEEE Transactions on Instrumentation and Measurement, Vol. 70, pp. 1-10,  2021. [Link](https://ieeexplore.ieee.org/document/9366835) 
2. Shurin A. and Klein I., QDR: A Quadrotor Dead Reckoning Framework, in IEEE Access, vol. 8, pp. 204433-204440, 2020. [Link](https://ieeexplore.ieee.org/abstract/document/9256293) 

**Alice Dataset**: 
1. Klein I. and Lipman Y., Continuous INS/DVL Fusion in Situations of DVL Outages, IEEE OES AUV2020, 2020. [Link](https://ieeexplore.ieee.org/abstract/document/9267945) 

**Snapir Dataset**: 
1. Yona M. and Klein I.,  Compensating for Partial Doppler Velocity Log Outages by using Deep-Learning Approaches, IEEE International Symposium on Robotic and Sensors Environments (ROSE 2021), October 28-29, 2021. [Link](https://ieeexplore.ieee.org/document/9611779) 
