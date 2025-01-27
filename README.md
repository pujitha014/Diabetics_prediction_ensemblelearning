**Diabetes Prediction using SVM, Neural Network, and Bagging Ensemble Method**
This project focuses on building and evaluating machine learning models for diabetes prediction using various approaches such as Support Vector Machines (SVM), Artificial Neural Networks (ANN), and a Bagging Ensemble Method. The code demonstrates preprocessing, model training, evaluation, and ensembling to enhance prediction accuracy.

**Features and Workflow:**
1.Data Preprocessing:
Standardized features using StandardScaler.
Separated features (x) and target (y) from the dataset.
2.SVM Model:
Trained with an RBF kernel to establish a baseline accuracy.
Predictions integrated into the dataset for ensemble learning.
3.Custom Neural Network:
Lightweight ANN with one hidden layer and ReLU activation.
Includes gradient clipping and bounded updates for stable training.
4.Bagging Ensemble:
Combines predictions from multiple ANN models trained on bootstrap samples.
Improves robustness and accuracy.

**Results:**
SVM Accuracy: Serves as the baseline.
ANN Accuracy: Performance varies based on hyperparameters.
Ensemble Accuracy: Aggregates multiple models to achieve higher consistency and accuracy.

**Usage:**
Clone the repository.
Place the diabetes.csv dataset in the project directory.
Run the code to train the SVM, ANN, and Bagging Ensemble models.
View accuracy metrics for individual and ensemble predictions.


