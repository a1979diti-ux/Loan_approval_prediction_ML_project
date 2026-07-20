<b>ML PROJECT</b><br>
<b>LOAN APPROVAL PREDICTION USING MACHINE LEARNING</b><br>
Objective of this project is to build a machine learning model for predicting loan approvals. <br>
This project focuses on improving model’s performance by incorporating different ML algorithms and finding out the best among these. <br>
Model involves Hyperparameter Tuning,implemented using GridSearchCV, to improve performance of different algorithms.<br>
Stratified K Fold technique is used to evaluate model performance on training data.<br>
KNN algorithm was trained with two different ‘weights’ (uniform & distance) and their prediction metrics were compared.<br>
<b>Dataset source-</b>Mendeley Data<br>
Dataset link- https://data.mendeley.com/datasets/k9wszywskf/2/files/c3127c80-56ac-43c2-82f0-cdc8040e343f<br>
Dataset file has been renamed from 'loan_approval_dataset_clean.csv' to 'project_dataset.csv' for project purposes.<br>
<b>Machine Learning Models Implemented</b><br>
1-Decision Tree<br>
2-Random Forest<br>
3-Logistic Regression <br>
4-K Nearest Neighbors (KNN)<br>
5-Support Vector Machine (SVM)<br>
<b>Best Model Selected- DECISION TREE</b><br>
Performance Metrics Achieved<br>
Accuracy- 98.4<br>
Precision- 98.7<br>
Recall- 97.1<br>
F1-97.9<br>
AUC score-99.2<br>
Confusion Matrix (Positive is approved)-<br>
True Positives=532/854<br>
True Negatives=309/854<br>
False Positives=9/854<br>
False Negatives=4/854<br>
In KNN, with weights='uniform', the model showed good generalization but with weights='distance',there is overfitting in the model.
Since the difference between the testing accuracies of both models is less, model with good generalization(weights='uniform')is chosen.
