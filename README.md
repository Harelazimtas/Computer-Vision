# Computer-Vision
The project deals with  augmentations, learning neuronal networks, Kaggle competition.


<h3>Part I</h3>
The first part talks about an introduction to libraries for neural networks.
In the introduction, I presented the image in various formats (gray, BGR, RBG).
And implementation method: convolve2d.

Implementaion of different augmentations, as well as creating a dataset of numbers from numbers 1-10, 
creating a large data of numbers from 1-100 and then using augmentations to increase the dataset.

<h3>Part II</h3>
<ul>
  <li>Face_Recognition</li>
  The program is about recognizing a person's face.
  I created a DataLoader that gives me back a person's name (number) and the image in order to train the model.
  I created a VGG16 model (class) that is made up of layers: Conv2d, BatchNorm2d, MaxPool2d, fully connected layer, relu.
  I showed the convergence and percentage accuracy of the model in the graphs, and presented the confusion matrix.
  Finally I used 5 models:resnet18,resnext,googlenet,densenet, mobilenet. and then used Ensemble to get a more accurate prediction result
  
  <li>Intel-Cancer-kaggle</li>
  Participation in the Kaggle Late Competition A type classification  competition.
  In the competition I also used ensemble to get a better result.
</ul>

<h2>Object Detection- Kaggle Competition</h2>
<p>You can see in the following examples some of the pictures i implements, also you can see the real picture without boxes</p>
<div>
  <img src="/Object Detection- Kaggle Competition/Images_Kaggle_Wheat/HorizontalFlip.png" alt="HorizontalFlip" width="400" height="400">
  <img src="/Object Detection- Kaggle Competition/Images_Kaggle_Wheat/HueSaturatuinVal.png" alt="HueSaturatuinVal" width="200" height="200">
  <img src="/Object Detection- Kaggle Competition/Images_Kaggle_Wheat/RandomBrightness.png" alt="RandomBrightness" width="200" height="200">
  <img src="/Object Detection- Kaggle Competition/Images_Kaggle_Wheat/Rotate90.png" alt="Rotate90" width="200" height="200">
  <img src="/Object Detection- Kaggle Competition/Images_Kaggle_Wheat/Transpose.png" alt="Transpose" width="200" height="200">

<div>
All images remained same size.
<br>
I used training in taking different examples every 15 epoch.
And in the test prediction, I used the ensemble in different models of FasterCNN with TTA(Rotate90, HorizontalFlip,VerticalFlip).

