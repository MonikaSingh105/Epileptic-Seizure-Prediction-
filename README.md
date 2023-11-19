# Epileptic-Seizure-Prediction-
 ## Overview
This project aims to predict epileptic seizures using machine learning techniques applied to EEG (Electroencephalogram) data. The model analyzes various features extracted from EEG signals to classify instances as either seizure or non-seizure events.
## Dataset
Epilepsy Datasets in General:

EEG Recordings: Epilepsy datasets often consist of Electroencephalogram (EEG) recordings. EEG is a test that measures electrical activity in the brain, and it's commonly used in the diagnosis and study of epilepsy.

Patient Information: Datasets typically include information about the patients, such as age, gender, medical history, and any relevant clinical information.

Seizure Annotations: For datasets related to epilepsy, there will usually be annotations indicating the occurrence of seizures. Each EEG recording may be labeled with the corresponding time points of seizures.

Control or Non-Seizure Data: Alongside seizure events, the dataset may include segments of EEG data without seizure activity. This helps in training machine learning models to distinguish between seizure and non-seizure patterns.

Metadata: Datasets often come with metadata, providing details about the recording conditions, equipment used, and any preprocessing steps applied to the data.

## Feature Extraction

Feature extraction for EEG data, such as Seina scalp data, is a critical step in building machine learning models for epilepsy prediction. EEG signals are time-series data, and extracting relevant features can help capture patterns indicative of seizure activity. 
Steps:
(1) EEG data is loaded using MNE.
(2) Segmentation into epochs is performed.
(3) Frequency domain features (average power spectral density in different frequency bands) and statistical features (mean, variance, skewness, kurtosis) are extracted for each epoch.
(4) Features are stored in a DataFrame, and labels are added based on seizure/non-seizure events.
(5) The extracted features are saved to a CSV file.


## Machine Learning Model
(1) Classifying EEG signals using KNN, decision tree, random forest, XGBoost 
(2) Cross validation and hyperparameter search

## Requirements
List the software and library dependencies required to run the project.

(1) Python 3.x
(2) NumPy
(3) pandas
(4) scikit-learn
(5) Keras
(6) Tensorflow
