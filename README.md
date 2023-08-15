# Acoustic-VINS
Acoustic-VINS: Tightly Coupled Acoustic-Visual-Inertial Navigation System for Autonomous Underwater Vehicles


In this work, we present an acoustic-visual-inertial
navigation system (Acoustic-VINS) for underwater robot localization. Specifically, we address the problem of the global
position of underwater visual-inertial navigation systems being
inappreciable by tightly coupling the long baseline (LBL) system
into an optimization-based visual-inertial SLAM. 

Additionally, for wider application, we extend the sensor data of the real-world AQUALOC dataset to obtain the LBL-AQUALOC dataset


System overview of the proposed Acoustic-VINS. The system is divided into four modules: sensors, pre-processing, initialization, and optimization.
First, the measurements of the sensors are pre-processed. Then, in the initialization phase, Visual-Inertial-initialization is completed by aligning the inertial
information and the results of vision-only Structure from Motion (SfM); Acoustic-Inertial-initialization is completed by aligning the inertial information and
acoustic information. After the final initialization is successful, states will be optimized within the sliding window![system3](https://github.com/JiangboSong251/Acoustic-VINS/assets/74598384/11b817a4-e2f0-457d-beb6-a127fa5b4f38)
