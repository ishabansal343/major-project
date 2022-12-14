# Cotton Plant Disease Classification Web Application :herb:
This repository is about an end to end implemetation of deep learning cotton plant disease classification web application using flask. 

## Dataset
The dataset is downloaded from [Kaggle](https://www.kaggle.com/janmejaybhoi/cotton-disease-dataset). and total size is 152 MB. The dataset contains 3 folders with 1951 train images, 106 test images and 253 validation images. Each folder is divided into four classes: diseased cotton plant (Fusarium Wilt), diseased cotton leaf (Leaf Curl Disease), fresh cotton plant (Healthy Plant) and fresh cotton leaf (Healthy Leaf). Each image has a size of 694x694 pixels in JPG format.
Here are the sample images of the dataset...  

<img src="https://github.com/myatmyintzuthin/Cotton-Plant-Disease-Classification-Web-Application/blob/main/assets/SampleImagesfromDataset.png" width=50% height=50%>

## DenseNet Model
Pretrained DenseNet121 model on ImageNet dataset is used. With the help of transfer learning, the last 8 layers of the model are tuned to solve the problem. The model is trained for 20 epoches and the accuracy is 97% on test data. 

<img src="https://i.imgur.com/O8ntGzS.png">

## Training Accuracy and Loss
<img src="https://github.com/myatmyintzuthin/Cotton-Plant-Disease-Classification-Web-Application/blob/main/assets/DenseNet121_plot.png">

## Confusion Matrix
<img src="https://github.com/myatmyintzuthin/Cotton-Plant-Disease-Classification-Web-Application/blob/main/assets/DenseNetConfusionMatrix.png" width=50% height=50%>

## Credits
Thanks.
