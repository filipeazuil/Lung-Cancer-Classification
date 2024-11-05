# Lung Nodule Classification 
### Project Overview
In this project our goal is to develop a Data Science-based solution to solve the problem of Lung Cancer Classification using Computerized Tomography (CT) Data. Lung cancer remains one of the most critical health challenges, and early, accurate detection plays a key role in improving patient outcomes. By leveraging machine learning models, this project aims to differentiate between benign and malignant lung nodules based on CT data.

### Data
The dataset consists of CT scan images from 1,010 patients. Each scan image includes detailed visual information that enables us to identify patterns associated with malignancy. Using feature extraction methods, we transform these images into a structured dataset, allowing for efficient analysis and model training.

# Project Roadmap
### 1. Feature Extraction
Notebook: FeatureExtraction - CNN3D.ipynb

Description: This notebook focuses on extracting features from CT scan images using a 3D Convolutional Neural Network (3D CNN). The 3D CNN processes the spatial structure of CT scan volumes, allowing us to capture detailed spatial features that are critical for distinguishing between benign and malignant nodules.

### 2. Data Cleaning and Feature Selection
Notebook: LungCancerClassification.ipynb

Description: After feature extraction, this step involves cleaning the dataset to handle missing values, outliers, and other inconsistencies. We also use feature selection techniques like PCA and t-tests to identify the most relevant features for classification.

### 3. Model Implementation and Evaluation
Notebook: LungCancerClassification.ipynb

Description: This notebook includes the implementation of machine learning models, including SVM, Random Forest, and an ensemble model. Hyperparameter tuning with Grid Search and model evaluation are also performed here, prioritizing sensitivity for accurate detection of malignant cases.

### 4. Results
Notebook: LungCancerClassification.ipynb

Description: The final results are analyzed and visualized, with a focus on metrics like AUC, sensitivity, and specificity. This step highlights the model’s effectiveness in distinguishing between benign and malignant nodules.

# Requirements
To install the requirements run:
pip install -r requirements.txt



