# Multi Class Cataract Prediction

In this project, multiclass cataract classification was performed by using a diversified dataset, i.e Ocular Disease Intelligent Recognition, consisting of data from around 5000 patients, which includes colour fundus photographs from left and right eyes and doctors' diagnostic keywords. At the end of this project, our model will be able to classify different types of eye problems, including cataract, glaucoma, etc. with satisfiable accuracy given a colour fundus photograph.

## Data Source
Ocular Disease Intelligent Recognition (ODIR) is a structured ophthalmic database of 5,000 patients with age, colour fundus photographs from left and right eyes and doctors' diagnostic keywords from doctors. This dataset is meant to represent a ‘‘real-life’’ set of patient information collected from different hospitals/medical centres in China. In these institutions, fundus images are captured by various cameras in varied image resolutions. These dataset images have been labelled and annotated by trained human professionals. The classes are: Normal, Diabetes, Glaucoma, Cataract, Age related Macular Degeneration, Hypertension, Pathological Myopia, Other diseases/abnormalities.

Data Source Link: [https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k)

## VGG-19
VGG stands for Visual Geometry Group; it is a standard deep Convolutional Neural Network (CNN) architecture with multiple layers. The “deep” refers to the number of layers with VGG-16 or VGG-19 consisting of 16 and 19 convolutional layers. The VGG architecture is the basis of ground-breaking object recognition models. Developed as a deep neural network, the VGGNet also surpasses baselines on many tasks and datasets beyond ImageNet. Moreover, it is now still one of the most popular image recognition architectures.

## Results
**Confusion Matrix**
![Confusion Matrix](https://github.com/Rajat1206/Multi-Class-Cataract-Prediction/blob/main/Images/confusionmatrix.png)

**Predictions**
![Predictions](https://github.com/Rajat1206/Multi-Class-Cataract-Prediction/blob/main/Images/results.png)

In this study, we applied the VGG19 architecture for the multi-class classification of colour fundus photographs of the left and right eye, into one of the eight classes - Normal, Cataract, Diabetes, Glaucoma, Hypertension, Myopia, Age Issues and Others. This has been done by the use of the Convolutional Neural Network model - VGG19, which is a 19 layer deep pre-trained model. This model has been pre-trained on over a million images in the ImageNet database. By applying the VGG19 model for feature extraction and employing our own output layers, we were able to successfully classify eye images with an accuracy of about 78%.
