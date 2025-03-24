# Data-Science-and-Machine-Learning-CNN

**Student Name: Qadeer Hussain**

**Student ID: C00270632**

**Lecture: Greg Doyle**

**Lecture: Convolutional Neural Networks (CNN)**

# Project Description
The purpose of this project is to predict a persons facial expression using a Convolutional Neural Network (CNN).

# Data Source
The dataset that was used for this project can be downloaded from https://www.kaggle.com/datasets/msambare/fer2013/data

# Processing
After downloading this dataset a print was conducted to view structure of the dataset. The dataset is divided into train and test folders, each containing subfolders for the seven emotion classes: angry, disgust, fear, happy, neutral, sad, and surprise. After this, The data was explored visually by displaying random grayscale images from each emotion category. Using matplot library the distrubaiton of the classes was visualsized by graphs. After exploring the dataset, TensorFlow’s image loader was used to import the images, resize them to 48x48 pixels, and normalize pixel values between 0 and 1. Labels were automatically assigned based on the folder names corresponding to the seven emotion categories. Data augmentation was applied to the training set using random flips, rotations, and zooms to improve generalization and reduce overfitting. After this the model was built. The model was trained over 40 epochs. During training, both the accuracy and loss were tracked and visualized using matplot library. During training, both the accuracy and loss were tracked and visualized using the Matplotlib library. Finally, the model was tested by generating predictions on a batch test images and were compared with their actual labels to assess the models performance.

# Data Understanding and Visualisation 
After the data was processed these were the following results:

1. Training & Validation loss:  The loss graph shows a steady decrease, indicating the model is learning effectively over each epoch.

   ![image](https://github.com/user-attachments/assets/72957e8f-d10d-4f64-afd4-96d1b75f6674)

2. Training & Validation Accuracy: The accuracy graph shows consistent improvement, reaching around 52% accuracy by the final epoch.

   ![image](https://github.com/user-attachments/assets/5f25f1ae-e75f-44c5-855c-9f95084e81a6)

3. Model in use: The trained model was tested on unseen images, and its predictions were compared to actual labels for visual verification.

   ![image](https://github.com/user-attachments/assets/549d6a49-8cd5-4a2d-b018-5205aba0c168)

# Algorithims:
Convolutional Neural Networks: CNN is a deep learning models designed for image data. They use layers of filters to automatically detect patterns like edges and shapes. In this project, CNN were used to classify facial expressions based images

# Online Sources:
1. Trekhleb (2025) Trekhleb/machine-learning-experiments: 🤖 interactive machine learning experiments: 🏋️models training + 🎨models demo, GitHub. Available at: https://github.com/trekhleb/machine-learning-experiments (Accessed: March 2025). 
2. User guide# (2025) User Guide - pandas 2.2.3 documentation. Available at: https://pandas.pydata.org/docs/user_guide/index.html (Accessed: March 2025).
3. Matplotlib 3.9.2 documentation# (2025) Matplotlib documentation - Matplotlib 3.9.2 documentation. Available at: https://matplotlib.org/stable/ (Accessed: March 2025).
4. Tensorflow (2025) TensorFlow. Available at: https://www.tensorflow.org/ (Accessed: March 2025). 

# Tools and Tech Used: 
1. Convolutional Neural Netwworks
2. Jupter Notebook
3. Pandas Library - Loading the data and analysing it
4. Matplotlib - Plotting and Visualising the graph 
5. Tensorflow
6. Numpy
