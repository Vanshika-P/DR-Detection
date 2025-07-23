# DR-Detection

Diabetic Retinopathy Classification
Diabetic Retinopathy (DR) is an eye condition caused by complications of diabetes, which can lead to the formation of retinal lesions and, in severe cases, complete vision loss. To make the diagnostic process more reliable and less prone to human error, Computer-Aided Diagnosis (CAD) systems play a crucial role in assisting medical practitioners.

In this project, I have implemented and compared various deep learning models for DR classification, including:

A basic Convolutional Neural Network (CNN)

Pre-trained models: VGG16, VGG19, ResNet50, and MobileNetV2

The highest accuracy was achieved using MobileNetV2.

For this work, I used the IDRiD (Indian Diabetic Retinopathy Image Dataset) published in 2015, which contains high-resolution retinal fundus images labeled for different DR severity levels. 

Link: https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid 

Colab Notebooks

- [CNN on IDRiD](Colab%20Notebooks/CNNonIDRiD.ipynb)
  
- [New MobileNetV2](Colab%20Notebooks/New_MobileNetV2.ipynb)
  
- [ResNet50 on IDRiD](Colab%20Notebooks/Rsnet50_on_IDRiD.ipynb)
  
- [VGG16 on IDRiD](Colab%20Notebooks/VGG16onIDRiD.ipynb)
  
- [VGG19 with Preprocessing](Colab%20Notebooks/VGG19_with_preprocessing.ipynb)

