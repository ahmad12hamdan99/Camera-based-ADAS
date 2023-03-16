# Camera-based-ADAS
This project is a part of Computer Vision course at Innopolis University - Spring 23
---
## Idea: 
ADAS (Advanced Driver Assistance Systems) are passive and active safety systems designed to remove the human error component when operating vehicles of many types. 
In this project I am focusing on the following tasks: 
1. **Advanced lane finding :** classical approach will be used, it might be a good idea to explore a learning based approach to avoid the problems that comes from camera calibration and positioning.
The output result of the first step is expected to be as follows: 
![alt text](https://github.com/ahmad12hamdan99/Camera-based-ADAS/blob/main/figs/lane_1.jpg) 
2. **Detecting other vehicles :** YOLO will be used for this task, no modification will be made as it already trained on class cars. There might be a possibility to train on new classes like Yandex rover in case of pratical testing in Innopolis city.

3. **Tracking other vehicles:** for this task [Deep Sort](https://github.com/nwojke/deep_sort) will be used which is based on [Simple Online and Realtime Tracking with a Deep Association Metric](https://arxiv.org/abs/1703.07402)

4. **Front collision warning:** The possibilty of calculating the distance to other cars will be interesting to study in order to implement a front-collision warning.
---
## Time:




