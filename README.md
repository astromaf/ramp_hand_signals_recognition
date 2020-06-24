# Real-time visual recognition of "aircraft ramp hand-signals" applied to UAVs into airport ground operations.

Unmanned aerial vehicles are a reality today. The next great technological and operational challenge, that the sector must face is the simultaneous coexistence of manned and unmanned platforms in existing spaces. One of the biggest challenges comes in ground operations, originally designed for human-to-human interaction.
The main objective of this undertaking is the design and validation of a visual recognition and identification software in real time, of a limited number of  "airport ramp signals" that ground personnel carry out through the specific movement of their arms, focused for use in UAVs.
With this purpose in mind, techniques based on pre-trained neural networks for the sequential prediction of human pose and additional ensemble methods for the classification of gestures, will be employed.

**Keywords:** Real-time, Gesture Recongition, Convolutional Pose Machines, Aircraft Marshalling Signals, UAVs, Jetson Nano.
<p align="center">
  
![CONOPS](Figures/1_2.png?raw=true "System Overview")


*Fig1. System Overview*



![Setup](Figures/4_1.jpg?raw=true "Main HW architecture")


*Fig2. Main HW architecture*



![GUI](Figures/4_2.png?raw=true "Best Architecture")


*Fig3. Best Modelo Architecture: CPM+ANN/RF*



![GUI](Figures/5_1.jpg?raw=true "Graphical Interface")


*Fig4. Graphical Interface Developed*
</p>



## Videos:
- Video Nº1. Real-time execution architecture based on: CPM+ANN. https://www.youtube.com/watch?v=gknhEQl33qg 
- Video Nº2. Real-time execution architecture based on: CPM+RF. https://www.youtube.com/watch?v=VEt8DadGwLU&feature=youtu.be
- Video Nº3. Real-time execution architecture based on: CCN (Night Operation). https://youtu.be/aJ8TJzfSGjs

## Main References:
- TensorRT Pose Estimation: https://github.com/NVIDIA-AI-IOT/trt_pose
- NVIDIA Getting Started With Jetson Nano Developer Kit https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit
## License:
GPU v3.0: https://github.com/astromaf/ramp_hand_signals_recognition/blob/master/LICENSE



