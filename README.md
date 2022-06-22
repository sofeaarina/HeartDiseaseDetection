# HeartDiseaseDetection
## 1. Summary
The aim of this project is to create a accurate deep learning model to predict the presence of Heart Disease. The model is trained with [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

## 2. IDE and Framework
This project is created using Google Colab as the main IDE. The main frameworks used in this project are Pandas, Scikit-learn and TensorFlow Keras.

## 3. Methodology
### 3.1. Data Pipeline
The data is directly loaded from Kaggle to Google Colab and preprocessed. There are no missing values in the data and label is encoded in one-hot format. Then the data is split into train-validation-test sets, with a ratio of 60:20:20.

### 3.2. Model Pipeline
A feedforward neural network is constructed that is catered for classification problem. The structure of the model is fairly simple. Figure below shows the structure of the model.

![image](https://user-images.githubusercontent.com/63838426/174961189-b844a342-4581-4a97-a628-a670ae56ae5f.png)

The model is trained with a batch size of 32 and for 20 epochs. The two figures below show the graph of the training process.

![image](https://user-images.githubusercontent.com/63838426/174960813-d69055c6-5190-4d5a-9940-606af71d6837.png)

![image](https://user-images.githubusercontent.com/63838426/174960940-a2e2fdfb-1ad6-41f2-a031-085687adca24.png)
## 4. Results
Since the data is quite simple, the model manage to predict with 100% accuracy.
