# NN

#### Model created that can predict / correct image orientation. Images were taken from cifar10 dataset

## Usage

### **1. Creating the model** (optional)
The model is already uploaded, but if you wish to create it yourself, you need to open **model_create.py** and change the **pathT** variable to your local folder containing the **train.truth.csv** file and a **train** folder containing the training images

### **2. Correcting images**
To run the image correction feature, open the **imageCorrect.py** file and change the model variable to the model created on step 1, the **path** variable to your folder containing the images you want to correct and the **pathS** variable to the folder where you want to save the new corrected images


## **General info**
**keras_cifar10_trained_model.h5** is the model that can be downloaded or created by running the **model.py** file
