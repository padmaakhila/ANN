Artificial Neural Network (ANN) – Churn Prediction

This project implements an Artificial Neural Network (ANN) to predict customer churn using the Churn_Modelling.csv dataset.
The ANN model includes full preprocessing (encoding, scaling), model training, performance visualization, and evaluation using accuracy and confusion matrix.

🔹 What this project does

Loads and preprocesses customer data

Encodes categorical columns (Geography, Gender)

Applies Standard Scaling

Builds ANN using Keras Sequential API

Trains model with validation

Plots training accuracy & loss

Predicts churn on test set

Evaluates accuracy using confusion matrix

🔹 Technologies Used

Python

NumPy, Pandas

Scikit-learn

Keras / TensorFlow

Matplotlib

🔹 Model Architecture

Hidden Layer 1 → 6 neurons, ReLU

Hidden Layer 2 → 6 neurons, ReLU

Output Layer → 1 neuron, Sigmoid

Optimizer → Adamax

Loss → Binary Crossentropy