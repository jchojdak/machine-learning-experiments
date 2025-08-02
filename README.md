# 📁 Machine Learning Experiments

* [About](#-about)
* [Experiments](#-experiments)

## 📌 About
The goal of this project is to test and explore different algorithms and data processing methods in the context of ML.

## 🧪 Experiments
### 1. Handwritten digit recognition experiment using the kNN Classification Algorithm
The first experiment involves using the K-Nearest Neighbors (KNN) algorithm for digit recognition. The model is trained on the `sklearn.datasets.load_digits` dataset and is used to classify images representing digits (0-9).
```
https://github.com/jchojdak/machine-learning-experiments/blob/master/ml-knn-digit-recognition/machine_learning_knn_digit_recognition.ipynb
```

### Steps:
1. Load the `sklearn.datasets.load_digits` dataset
2. Data preprocessing (normalization, splitting into training and test sets)
3. Implement the KNN classifier
4. Evaluate the model performance

### First 20 digits from datasets (total 1797):

![image](https://github.com/user-attachments/assets/060f51e1-8037-4a7b-bb1a-d4da30712ee9)

### Loaded image:

![1](https://github.com/user-attachments/assets/6a18f49d-c25b-418d-a5c6-4fb494a40806)

### Resized and normalized image:
![image](https://github.com/user-attachments/assets/9d92a131-5c0c-4e70-bd02-e0465b23b8bc)


### Result:

![image](https://github.com/user-attachments/assets/c9653d77-5e7d-4a79-8c6d-80d6da2baad5)

### 2. Develop and compare multiple machine learning models to predict anemia based on blood test parameters
```
https://github.com/jchojdak/machine-learning-experiments/blob/master/detect-anemia-by-blood-all-models/detect-anemia-by-blood-all-models.ipynb
```

### Steps:
1. Load and merge `https://www.kaggle.com/datasets/biswaranjanrao/anemia-dataset`, `https://www.kaggle.com/datasets/ragishehab/anemia-data-set` datasets.
2. Remove duplications, clean data in Python pipeline
3. Implement `Logistic Regression`, `Random Forest`, `Gradient Boosting`, `Support Vector Machine`, `K-Nearest Neighbors`, `Decision Tree`, `Naive Bayes` models from `sklearn` kit.
4. Visualize the results and compare multiple machine learning models.