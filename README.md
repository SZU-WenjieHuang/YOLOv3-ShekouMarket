### HUAWEI Cloud AI Competition: Recording disappearing cultural heritage using YOLO_v3 (2020.10-2020.12)
![image](https://user-images.githubusercontent.com/82434538/235476675-01f44a94-cbbd-4176-9113-4fd9eb0627bd.png)\
  ***Repository:*** [YOLOv3-Shekou-FishingMarket](https://github.com/SZU-WenjieHuang/YOLOv3-ShekouMarket)\
  ***Data:*** Video in Shekou Fishing Market\
  ***Description:*** Shekou Fishing Market will be demolished by the end of November 2020. With the HiLens Kit by HUAWEI Cloud, we built an installation in the sea world culture and arts center(SWCAC) to continue Shekou people's memory of Shekou fishing Market. We collect video in market using HiLens Kit's camera, and use YOLO_v3 algorithm to carry out human shape detextion in real time. Through stepping motors and other devices, we convey the same sense of crowding to exhibitors as in Shekou market. And the sense of crowding will also be preserved in the form of data.
  
- #### Overview
  ***Date Collecting*** Collect data from Amap API, Lianjia official website, and ArcGIS using Python.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235477141-e6117feb-7690-4058-a565-47ba75927737.png)\
  ***Data Processing*** After performing exploratory data analysis (EDA) on different types of POI data, the data is visualized on a single JPG image with a resolution of 8000*8000. Similarly, the HouseHeat data (a measure of the popularity of second-hand houses obtained from a defined company) is also visualized and represented on an 8000*8000 JPG image. These POI and HouseHeat JPG images are then segmented into 225 512*512 images to create a dataset. Our objective is to establish a mapping from the POI images to the HouseHeat images.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235477535-5a2b8d89-c204-4125-8930-aa185c5a1a57.png)
  ***Model Training*** We trained a GAN to learn a mapping between two images stes, also known as an image-to-image translation.</p>

- #### YOLO_V3
  ***Date*** Collect data from Amap API, Lianjia official website, and ArcGIS using Python.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235478815-0c810fc0-5c1a-4a31-af29-fa6d49faa9d7.png)
  ***Date*** Collect data from Amap API, Lianjia official website, and ArcGIS using Python.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235478545-3e4e2acd-ceeb-430d-b7b6-478c16b9c2e6.png)

- #### Data Transduction
  ***Date*** Collect data from Amap API, Lianjia official website, and ArcGIS using Python.</p>
  ![image](https://user-images.githubusercontent.com/82434538/235479883-4d0f4ed7-fcae-4b19-b500-a0f5155aa69e.png)
  ![image](https://user-images.githubusercontent.com/82434538/235479942-96834195-273d-47cd-a8a8-a36bd7bb1060.png)
  ![image](https://user-images.githubusercontent.com/82434538/235480028-c2471a38-bb97-4f3e-a1b1-ee377577c096.png)

