# Skin Cancer Detection Project TinyML
#### BAAZIZ ELMEHDI & OUICH JALALEDDINE & FALL OUSMANE

# 1. Introduction :
The goal of this project is to perform an image classification for skin cancer detection using the Arduino Nano 33 Sense BLE card and a camera module.
# 2. Data acquisition : 

the most crucial aspect of the project is creating the dataset. The images for cancer were obtained from the Kaggle website (https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic), specifically for the skin cancer called "melanoma". The dataset contains two classes labeled as "safe_skin" and "cancer_skin".

# 3. Model's choice : 
Choosing a model is crucial for our project. We need to bear in mind the amount of RAM that is accessible while using Arduino Nano ble 33.
![](capture1.jpg)
the choice will be  MobileNet model family.

# 5. Training : 
We will train the model with 2 different methods : 
# 5.1 Method 1 : Edge Impulse 
# 5.1.1 Step 1 : Data Acquisition 
![](CAP4.PNG)
Here i loaded 340 photos splitted : 
 80% (272 photos) for trainning.
 20% (68 photos) for test.
# 5.1.2 Step 2: Create Impulse
![](cap3.PNG)
