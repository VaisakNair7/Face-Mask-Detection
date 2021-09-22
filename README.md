# Face Mask Detection using OpenCV and Transfer Learning

## Dataset link - https://www.kaggle.com/omkargurav/face-mask-dataset

## Demo Screenshots
![1](https://user-images.githubusercontent.com/37840005/124636780-8c9d7980-dea6-11eb-9649-9537c6c4df09.PNG)
![2](https://user-images.githubusercontent.com/37840005/124636800-91622d80-dea6-11eb-93f0-2c6755c0e8ec.PNG)


The model used here is MobileNetV2 which is trained on the kaggle dataset, split into train and test test and detects face mask with the help of OpenCV. A training accuracy of 98.9% was achieved. The model predcits face mask on each and every frame of live video feed provided by OpenCV. The front end is build using Flask web framework.

## How to run it.

1. Install the libraries present in requirements.txt (pip install - r requirements.txt)
2. Run app.py in terminal and click on the link which will lead you to the website hosted on your local machine.



