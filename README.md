# Intelligent Culpability Detection System Using Computer Vision
This project aims to automate the process of determining who is responsible for a car accident in order to reduce traffic congestion. Using computer vision, we analyze the pictures 🎑 and determine if there is any damage and how deep it is. In addition, the vehicle's position is determined. Furthermore, using a fault recognition decision-making system, we determine which vehicle is responsible for the accident🚘, as well as the mistake percentage of each vehicle.
![](Images/Damage.png)

## Table of Contents

- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Examples](#examples)
- [Results](#results)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)


## Data Preparation

- The damage detection model is trained on [Roboflow car damage](https://example.com/paper.pdf](https://app.roboflow.com/khadijah-baouthman-tvhkx/culpability-detection-system/2)https://app.roboflow.com/khadijah-baouthman-tvhkx/culpability-detection-system/2) dataset. Then, it anotated manually.
  
- The damage depth predection model trained on [Fast, Furious and Insured](https://www.kaggle.com/datasets/infernape/fast-furious-and-insured) dataset.
![](Images/Damage.png)
![](Images/notDamage.png)
  


## Model Training
The first model is a pre-trained model called You Only Look Once (YOLO). We focused on a [YOLOv8](https://github.com/ultralytics/ultralytics) for damage detection. For the second model, a convolutional neural network (CNN) is created from scratch to determine the depth of the damage as shown below. ![](Images/CNN.png).



## Evaluation

## Examples

## Results

## Acknowledgments
Thanks are due to the supervisor [Achref Rebai](Achref Rebai github) for his guidance.
You can download the paper [here](https://example.com/paper.pdf).


## Contact
Feel free to contact us with any questions or feedback:

- Hebah Soleman: Hebah.Omer@gmail.com
- Ehab Abu-Alqumboz: Ehab.qmbz@gmail.com
- Khadijah Baothman: KhadijahBaothman@gmail.com
- Rand Barnawi: Rand.A.Barnawi@gmail.com








