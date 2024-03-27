# Crop-disease-detection_using-TL
Makerere Fall Armyworm Crop: disease detection using Transfer Learning  
## CROP DISEASE : Machine Learning Model to determine from a photo if corn plant is affected by armyworm.

### Table of Contents

1. [Project Purpose](#projet)
2. [Installation](#install)
3. [Files Descriptions](#files)
4. [Authors and motivations](#authors)



### What is the project ? <a name="projet"></a>

The objective of this project is to design a machine learning model that can use a photo of a leaf on a corn plant to determine whether the plant is affected by armyworm.

The model will be based on the image classification method, a domain of the Computer Vision.

We will use a specific deep learning technique called **Transfer Learning** , where a pre-trained model is used as a basis and then adapted to successfully perform a new task (in ourcase classifying the image of a maize plant).

Then, on top of Transfer Learning, **Fine-tuning** is an approach where the model output is changed to fit the new task and train only the output model. While Transfer Learning involves freezing the pre-trained model’s weights and only training the new layers, Fine-tuning takes it a step further by allowing the pre-trained layers to be updated. 

The images come from the Makerere Fall Armyworm Crop Challenge data on Zindi. https://zindi.africa/competitions/makerere-fall-armyworm-crop-challenge/data

### Installation <a name="install"></a>

To explore this project download the 'images.zip' file containing the images dataset and the two csv file 'Train.csv' and 'Test.csv'. All these files can be loaded in the web site or on the github repos.

The Machine Learning model notebook *Crop_disease_TF_1_2c.ipynb* can be loaded on the github repos. 

All dependencies to install are listed in requirements.txt file.

### Files Descriptions <a name="files"></a>

 * images.zip : contains 2699 images showing photos of leaves of contaminated and uncontaminated maize plants. Images are in jpg format
    
 * Train.csv and Test.csv : 
    'Image_id' : the number of the image attached to the Train of Test dataset
    'Label' : Only for the Train.csv file ; O = no infection and 1 = infected 

 * *Crop_disease_TF_1_2c.ipynb* : 
        This notebook conducts data analysis and model training using Tensor Flow platform and Keras API.

### Authors & Motivations <a name="authors"></a>

This project was carried out as part of the certification for the Applied Master of Science in Data Science & AI at the Data ScienceTech Institute (Nice).

The members of the project group are :
 - Deena ZAMZAM - Data scientist
 - Saïd HAMDI - Data scientist
 - Guillaume NONY - Data scientist

### How to run the project : 
Open *Crop_disease_TF_1_2c.ipynb*  in your favorite IDE. Google Collab can be a good alternative as it offers free access to computing resources, including GPUs and TPUs.
