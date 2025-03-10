pattern recognition for XOR Problem

overview:

This project demonstrates the use of quantum machine learning algorithms to solve the XOR problem using the VQC (Variational Quantum Classifier) model from the Qiskit framework. The model is trained using different quantum optimizers , and its performance is compared with a classical model (Logistic Regression) on the XOR dataset.


Features:
1. Dataset Creation**: A simple XOR dataset is created and normalized using MinMaxScaler.
2. Feature Map & Ansatz**: A ZZFeatureMap is used as the feature map, and an EfficientSU2 ansatz is employed.
3. Quantum Classifiers: Two optimizers, COBYLA and SPSA, are used to train the quantum classifier.
4. Classical Model: A classical Logistic Regression model is also trained for comparison.
5. erformance Evaluation: The models are evaluated based on their accuracy, and decision boundaries are plotted for visualization.

Requirements:
Python 3.x
Qiskit
Qiskit Machine Learning
scikit-learn
matplotlib
numpy

usage:
Clone the repository: Clone the repository to your local machine:

bash
Copy
git clone https://github.com/your-username/quantum-classifier-xor.git
cd quantum-classifier-xor
Run the script: The script is designed to train quantum classifiers and compare them to a classical model. To run the script, simply execute:

bash
Copy
python quantum_classifier_xor.py
Output: The script will:

Train quantum classifiers using COBYLA and SPSA optimizers.
Compare their test accuracy with a classical Logistic Regression model.
Plot decision boundaries for the best-performing model.

contributors:
Manasi Sabnis
Likhitha Marella
Shubhaditya