# Semantic-Segmentation-on-Saigon-Aerial-dataset

**Introduce Saigon Aerial dataset:** 
+ You can find and download the dataset here: https://www.kaggle.com/datasets/trungnguyenbui/saigon-aerial-dataset.
+ Saigon Aerial dataset is a segmentation dataset, capturing traffic scenes in To Ky street and An Suong overpass. The Saigon Aerial dataset consist of 114 images and labels in 4K (3840 x 2160) resolution, distribution unequally in 6 folders.
+ There are 5 classes in this dataset, colored by following RGBs:

    motorbike : 192 0 192
    car : 64 0 128
    road : 128 64 128
    background : 0 0 0
    
** Method used in this repository**
+ In this repo, I used 2 models: DeeplabV3+ and Unet with different backbone to evaluate the efficiency of 2 models on predicting pixel-wise labels.
+ In all of my proposal solutions, so far I specify that Unet + Inception model yield the most acceptable result, you can check my works in 2 following images 

![](https://github.com/nguyenbui45/Semantic-Segmentation-on-Saigon-Aerial-dataset/blob/master/output.PNG)
_Result of Unet + Inception_

![](https://github.com/nguyenbui45/Semantic-Segmentation-on-Saigon-Aerial-dataset/blob/master/miou.PNG)
_Mean Interception Over Union for all models_
