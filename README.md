# disease_detections
We know the future is all about AI so here is my idea of bringing 7 disease detections under one platform using the power of AI. 
7 disease detections:
Covid-19 detection
Brain Tumour detection
Breast Cancer detection
Alzheimer detection
Diabetes detection
Pneumonia detection
Heart disease detection

Convolutional Neural Networks…
![image](https://user-images.githubusercontent.com/77886713/156567144-09b427a8-cc58-4b7d-a137-078e9ff766fa.png)


A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm that can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image, and be able to differentiate one from the other.
The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics.
The architecture of a ConvNet is analogous to that of the connectivity pattern of Neurons in the Human Brain and was inspired by the organization of the Visual Cortex.
A ConvNet is able to successfully capture the Spatial and Temporal dependencies in an image through the application of relevant filters.
The role of the ConvNet is to reduce the images into a form that is easier to process, without losing features that are critical for getting a good prediction.


1. Covid-19 detection:
Used custom made CNN architecture for this detection.
Accuracy achieved was around 93%.

2. Brain Tumour detection:
Used VGG-16 for feature extraction.
Used custom-made CNN ahead of CNN.
The accuracy achieved was around 100%(just tested on 10 images :( ).

3. Breast Cancer detection:
Used Random Forest for this use case.
The accuracy achieved was around 91.81%.

4. Alzheimer detection:
Used Random Forest for this use case.
The accuracy achieved was around 73.54%.

5. Diabetes detection:
Used Random Forest for this use case.
The accuracy achieved was around 66.8%.

6. Pneumonia detection:
Used custom CNN architecture for this use case.
The accuracy achieved was around 83.17%.

7. Heart disease detection:
Used XGBoost for this use case.
The accuracy achieved was around 86.96%.


................................

Create a conda environment and install required libraries
conda create -n health python=3.9
conda activate health
pip install opencv-python numpy tensorflow sklearn imutils flask xgboost

..............................

When you have successfully created the environment, installed the required libraries, and activated it, simply run the following command in the terminal.
flask run
.................................






















