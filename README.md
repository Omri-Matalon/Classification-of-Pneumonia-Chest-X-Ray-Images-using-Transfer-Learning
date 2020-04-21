# Classification-of-Pneumonia-Chest-X-Ray-Images-using-Transfer-Learning

## **Introduction**
Pneumonia is an infectious disease that inflames the air sacs in one or both lungs that can range from a mild to life-threatening severity. A variety of organisms can cause Pneumonia, including bacteria, viruses and fungi, and early diagnosis of the disease is crucial for preventing deterioration of patients' medical condition. 

##**Dataset and Classification algorithm** 
In the current project, a data set of chest X-ray images (obtained from Kaggle) is used to predict pneumonia by classifying images to either normal or pneumonia category. 
The dataset contains total of 5,863 X-Ray images (JPEG), organized into 3 folders (train, test, val), in which each folder is divided into two category subfolders (Pneumonia/Normal). 

These images were used for training CNN models in an approach know as Transfer Learning. In this project two pre-trained CNN models were used, including the VGG-16 and VGG-19, following minor modification to fit the models to the specific binary classification problem at hand. Importantly, the preprocessing template presented in this notebook can be used for implementing additional state-of-the-art pre-trained CNN models available by tf.keras, including Xception, ResNet, ResNetV2, NASNet, and more.

## **Project Goal**
The main goal of this project (as defined in the Kaggle competition) is to classify X-Ray images into Normal or Pneumonia Categories. 
However, since the treatment of bacterial pneumonia differ significantly from a viral pneumonia, at the second part of the project images of pneumonia patients were divided into two additional categories ("Bacteria"/"Virus") to predict the type of infection causing the disease. While bacterial infections can be treated using antibiotics, viral infection cannot. Therefore, predicting the source of infection can assist determine the appropriate route of treatment in these medical conditions.   

## **Working Environment**
This project was conducted in Google Colaboratory (Colab), providing a free GPU resources, in integration with Google Drive for storing the image dataset and trained models. From this point of view, the current project provide an example for an integrated workflow with Colab, Google Drive, and Kaggle.    
