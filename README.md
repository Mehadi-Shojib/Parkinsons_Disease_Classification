# Parkinsons_Disease_Classification by Artificial Neural Networks (ANN),K-Nearest Neighbors (KNN),Support Vector Machines (SVM),Naive Bayes(Nb),Logistic Regression (LR),Decision Trees (DT).

Library Used of Python:	pandas,matplotlib,seaborn,sklearn,keras

In this project I tried 5 traditiona machine learning algorithm and 1 deep learning algorithm. KNN performed better 92% accuracy , ANN performed 90%, as following DT 79%, LR 76% , SVM 87%.

Dataset Information: This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voices recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD. The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around six recordings per patient, the name of the patient is identified in the first column. So, the dataset contains 194 entries and 24 attribute. 23 attributes are features and 1 (status column) is target.

Link: https://archive-beta.ics.uci.edu/dataset/174/parkinsons


Firstly i loaded the dataset then applied pre-processing then performed EDA to explore feature.Then I select 11 feature from 23 features by dropping the highly correlated columns except one using Correlation matrix. I applied standard scaller from sklearn on selected feature. After applying I use PCA for feature extraction. After that I splitted the dataset 80% training 20%testing. Lastly applied 6 models and generated confusion matrix, Classification Report,Learning Curve.
