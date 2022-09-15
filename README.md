# Leaf_Disease_Detection_instance_Segmentation
This project focuses on performing leaf disease detection through instance segmentation using Mask R-CNN
For performing leaf disease detection plant village dataset has been utilised and it has been annotated using VGG annotator tool and for this project only 6 classes are used:
1) Apple_healthy
2) Apple_Black_rot
3) Grape_healthy
4)Grape_Black_rot
5) Potato_healthy
6) Potato_Late_Blight

Additional folders:
Dataset3: This folder contains both training and validation dataset with json files.
without_background:This folder contains images from same dataset except that it doesnt have any background(white background).
images from online sources: These images are collected randomly from internet and it is an optional data that is just used to see how well our trained model works against real dataset.

Performance metrics:
The model has produced an highest mAP(mean Average Precision) of 70% for 400 epochs
