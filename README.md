# Real_time-Face-Mask Detector
Real time face-mask detection using Deep Learning and OpenCV

## About Project
This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. The CNN manages to get 
an accuracy of **98.37% on the training set** and **96.8% on the test set**. Then the stored weights of this CNN are used to classify as mask or no mask, in real time, using OpenCV.
With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between
wearing/removing mask and display of prediction.

#### The model is capable of predicting multiple faces with or without masks at the same time

## Working 

### With Mask

![image](mask.png)

## Dataset

The data used can be downloaded through this [link](https://www.kaggle.com/omkargurav/face-mask-dataset/) or can be downloaded from this repository as well (folders 'test' and 
'train'). There are 3725 images with mask and 3828 images without mask.

## How to Use

To use this project on your system, follow these steps:

1.Clone this repository onto your system by typing the following command on your Command Prompt:

```
git clone https://github.com/MuntahaShams/real-time-mask-detection.git
```
followed by:

```
cd real-time-mask-detection
```

2. Download all libaries using::
```
pip install -r requirements.txt
```

3. Open jupyter notebook using cmd
```
jupyter notebook 
```

4. Go to realtime.ipnyb:
```
run all cells 
```
## You should have tensorflow=2.4.1 to this project
#### The Project is now ready to use !!

