## IIT_P_Project_Assignment_Regularized_Neural_Network_for_Fraud_Detection
### 🔐 Fraud Detection with Neural Networks & Regularization Techniques
Course Assignment 04 – M.Tech AI & Data Science | IIT Patna
Author: Kumar Pancham Prasar | Roll No: 2303RES23

### This project focuses on applying deep learning-based fraud detection techniques on a real-world transaction dataset using various regularization methods like L2, Dropout, and Early Stopping to prevent overfitting and improve generalization.

#### 🎯 Objective:
To classify fraudulent transactions using a neural network model with improved stability and accuracy through regularization techniques.

#### 📊 Dataset:
Source: Credit card transaction dataset (fraudTrain.csv & fraudTest.csv)

Target Variable: is_fraud (0 = Genuine, 1 = Fraudulent)

#### 🛠️ Techniques Implemented:
✅ L2 Regularization: Adds penalty to weights to reduce overfitting

✅ Dropout: Randomly disables neurons during training to improve generalization

✅ L2 + Dropout Combined: Hybrid regularization strategy

✅ Early Stopping: Stops training when validation loss increases, preventing over-training

#### 🧰 Tech Stack:
Python, Pandas, Scikit-learn

TensorFlow/Keras (Dense layers, callbacks, dropout)

StandardScaler for feature normalization

#### 📈 Evaluation:
Binary classification metrics:

Accuracy

Confusion Matrix

Fraud detection performance

#### 📁 How to Run:
Upload the dataset files (fraudTrain.csv, fraudTest.csv) to your working directory

Run the notebook sequentially

Modify model architecture and hyperparameters to explore effects on performance

#### 🎓 Learning Outcome:
Understand practical uses of regularization in deep learning

Improve model performance for imbalanced classification problems

Work with real-world transaction data for fraud analytics
