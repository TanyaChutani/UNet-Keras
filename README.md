# Unet
Data-science-bowl-2018-Unet


## Data
The original dataset is data science bowl 2k18 - dataset (automating nucleus detection), 
and I've downloaded it, done the pre-processing and resizing all of the images to 128,128.
Dataset link - https://www.kaggle.com/c/data-science-bowl-2018/data

## Model
- Unet, deep neural network is implemented with Keras functional API.
- Output from the network is a 128*128 which represents mask that should be learned.
- The model was trained for 20 iterations with lr=0.001.
- Metric for the training is basically just a mean IOU.

## Results
You can download the pretrained weights from here 
https://drive.google.com/open?id=10-A8XTgkr_xlDhsS1iclGCCjy_5Xs6xg

1. <br />
![](https://github.com/TanyaChutani/Unet/blob/master/unet 1.png)<br />
2. <br />
![](https://github.com/TanyaChutani/Unet/blob/master/unet 2.png)<br />
