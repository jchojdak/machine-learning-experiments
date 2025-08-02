# 📁 Machine Learning Experiments

* [About](#-about)
* [Experiments](#-experiments)

## 📌 About
The goal of this project is to test and explore different algorithms and data processing methods in the context of ML.

## 🧪 Experiments
### 1. Handwritten digit recognition experiment using the kNN Classification Algorithm
The first experiment involves using the K-Nearest Neighbors (KNN) algorithm for digit recognition. The model is trained on the `sklearn.datasets.load_digits` dataset and is used to classify images representing digits (0-9).

Jupyter Notebook:
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

---

### 2. Develop and compare multiple machine learning models to predict anemia based on blood test parameters
This experiment demonstrates a complete end-to-end machine learning pipeline for predicting anemia based on blood test results. Multiple datasets are cleaned, merged, and explored, followed by training and comparing the performance of various supervised learning algorithms.

Jupyter Notebook:
```
https://github.com/jchojdak/machine-learning-experiments/blob/master/detect-anemia-by-blood-all-models/detect-anemia-by-blood-all-models.ipynb
```

### Steps:
1. Load and merge `https://www.kaggle.com/datasets/biswaranjanrao/anemia-dataset`, `https://www.kaggle.com/datasets/ragishehab/anemia-data-set` datasets.
2. Remove duplications, clean data in Python pipeline
3. Implement `Logistic Regression`, `Random Forest`, `Gradient Boosting`, `Support Vector Machine`, `K-Nearest Neighbors`, `Decision Tree`, `Naive Bayes` algorithms from `sklearn` kit.
4. Visualize the results and compare multiple machine learning models.

### Cleaning data
<img width="418" height="144" alt="image" src="https://github.com/user-attachments/assets/7677ba35-7824-43e8-9acf-309651e3cfbc" />

### Dataset overview
<img width="438" height="451" alt="image" src="https://github.com/user-attachments/assets/0fdcab63-38f5-4a1c-ac5e-c30de9fd2949" />

### Class distribution
<img width="1313" height="674" alt="image" src="https://github.com/user-attachments/assets/c2e9fe25-34d7-4e06-826c-3425fe3e4b93" />

### Feature analysis
<img width="592" height="536" alt="image" src="https://github.com/user-attachments/assets/746a22b1-ddff-4da7-8244-ab03b4bf058e" />
<img width="936" height="626" alt="image" src="https://github.com/user-attachments/assets/9ef64421-6cc9-4f6b-b9f3-7cb0d7d007ec" />

### Machine learning models performance comparison
<img width="1156" height="799" alt="image" src="https://github.com/user-attachments/assets/936a1d95-c5a0-482f-b2ed-a082c2372811" />
