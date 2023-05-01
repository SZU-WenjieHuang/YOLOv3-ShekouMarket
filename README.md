### HUAWEI Cloud AI Competition: Recording disappearing cultural heritage using YOLO_v3 (2020.10-2020.12)
![image](https://user-images.githubusercontent.com/82434538/235476675-01f44a94-cbbd-4176-9113-4fd9eb0627bd.png)\
  ***Repository:*** [YOLOv3-Shekou-FishingMarket](https://github.com/SZU-WenjieHuang/YOLOv3-ShekouMarket)\
  ***Data:*** [Video in Shekou Fishing Market](https://github.com/SZU-WenjieHuang/YOLOv3-ShekouMarket/tree/main/imgs)\
  ***Description:*** Shekou Fishing Market will be demolished by the end of November 2020. With the HiLens Kit by HUAWEI Cloud, we built an installation in the sea world culture and arts center(SWCAC) to continue Shekou people's memory of Shekou fishing Market. We collect video in market using HiLens Kit's camera, and use YOLO_v3 algorithm to carry out human shape detextion in real time. Through stepping motors and other devices, we convey the same sense of crowding to exhibitors as in Shekou market. And the sense of crowding will also be preserved in the form of data.
  
- #### Overview
  ***Date Collecting*** We deployed three cameras in the soon-to-be-demolished Shekou old market to capture the bustling crowds on the last day of its operation.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235477141-e6117feb-7690-4058-a565-47ba75927737.png)\
  ***Data Processing*** The Shekou fishing market is 12km away from the museum where our exhibition is held. How can we make museum visitors feel the same crowdedness as in the market? We utilized the YOLO_V3 algorithm, with only data input modifications but no model changes, for real-time person recognition. Our own algorithm detected the distance between the center point of the person's rectangular box and the distance to the two sides of the booth. The distance data obtained was translated by a stepper motor, allowing museum visitors to feel the crowdedness of the market.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235477535-5a2b8d89-c204-4125-8930-aa185c5a1a57.png)

- #### YOLO_V3
  ***Date Sample*** One example of the captured video from one of the cameras is presented here, comprising 15 frames.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235478815-0c810fc0-5c1a-4a31-af29-fa6d49faa9d7.png)
  ***YOLO_v3*** YOLO_v3 uses a single neural network to predict bounding boxes and class probabilities for all objects in an image. The algorithm divides the image into a grid and predicts a set of bounding boxes and their confidence scores for each grid cell. It then applies non-maximum suppression to eliminate overlapping detections. To detect people, the algorithm is trained on a large dataset of annotated images, and learns to recognize characteristic features of the human body such as head, torso, arms, and legs.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235478545-3e4e2acd-ceeb-430d-b7b6-478c16b9c2e6.png)

- #### Data Transduction
  ***Structure*** We customized a pair of 2m-high steel structures, with appropriate connections in the middle to provide installation positions for the stepper motor, which drives the retraction on both sides. The structures were covered with white silk to simulate the feeling of pedestrian congestion. We achieved a device structure that can visualize data in real-time within a limited cost (£ 3000).</p>
  ![image](https://user-images.githubusercontent.com/82434538/235479883-4d0f4ed7-fcae-4b19-b500-a0f5155aa69e.png)
  ***Stepper motor*** The PLC(Programmable Logic Controller) provides the stepper motor driver with a sequence of pulse signals to control the motor's motion. The driver then converts the pulse signals into electrical current that drives the stepper motor's coils, causing it to rotate in small, precise increments.The number of pulses sent to the stepper motor driver determines how far the motor rotates, and the frequency of the pulses determines the speed of the motor. By controlling the number and frequency of the pulses, the PLC can precisely control the position and speed of the stepper motor.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235479942-96834195-273d-47cd-a8a8-a36bd7bb1060.png)
  
- #### Exhibition！
  Our exhibition was a great success and this digital memory will permanently preserve the bustling atmosphere of the Shenzhen fishing market, even though it has been demolished. This project has made me realize my strong interest in AI.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235480028-c2471a38-bb97-4f3e-a1b1-ee377577c096.png)

