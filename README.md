# Gender and Age Classification using Convolutional Neural Networks (CNN)

This project implements a gender and age classification model using a Convolutional Neural Network (CNN). The model is trained on a dataset containing approximately 23,000 images obtained from Kaggle. The goal is to predict the gender and approximate age of individuals based on facial images.

## Dataset

The dataset used in this project is a collection of facial images. It includes images of individuals with annotations for gender (binary classification: male or female) and approximate age.\
Link:https://www.kaggle.com/datasets/jangedoo/utkface-new

## Model Architecture

The model consists of convolutional layers followed by max-pooling layers for feature extraction. Then, it has fully connected layers for classification. The model is compiled with binary cross-entropy loss for gender classification and mean absolute error (MAE) for age regression.

## Training
During training, the model's performance is monitored using metrics such as accuracy for gender classification. Validation accuracy is crucial to assess how well the model generalizes to new data.\
<img width="320" alt="image" src="https://github.com/Anujpratap9997/Gender-and-Age-prediction/assets/86520878/4a706230-1414-4d85-bfe1-c90e39f14056">
<img width="301" alt="image" src="https://github.com/Anujpratap9997/Gender-and-Age-prediction/assets/86520878/aa4ad1cf-2cac-4eb8-b142-2bc331731802">/

## Output
Output for one of the images from my dataset is shown here:\
![image](https://github.com/Anujpratap9997/Gender-and-Age-prediction/assets/86520878/792d2ca8-91bb-4f9a-901c-38457a25b6b4)


## Conclusion

This project demonstrates how to create a CNN model for gender and age classification using facial images. It highlights the importance of data preprocessing, model architecture, and evaluation metrics for successful model development.



