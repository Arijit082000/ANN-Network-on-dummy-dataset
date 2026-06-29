#  ANN Basic - Binary Classification using TensorFlow/Keras

##  Project Overview
This project demonstrates how to build a basic Artificial Neural Network (ANN) for a binary classification problem using TensorFlow/Keras. A synthetic dataset is generated with Scikit-learn, preprocessed using StandardScaler, and then used to train a simple feedforward neural network.

##  Features
- Generate a binary classification dataset
- Split data into training and testing sets
- Standardize features using StandardScaler
- Build an ANN using TensorFlow/Keras
- Train the model with validation data
- Evaluate model accuracy on the test dataset

##  Project Workflow
1. Import required libraries
2. Generate a synthetic dataset
3. Split the dataset into train and test sets
4. Scale the features
5. Build the ANN model
6. Compile the model
7. Train the model
8. Evaluate model performance

##  Technologies Used
- Python
- NumPy
- Scikit-learn
- TensorFlow / Keras

##  Libraries
```python
numpy
scikit-learn
tensorflow
```

Install dependencies:

```bash
pip install numpy scikit-learn tensorflow
```

##  Model Architecture

| Layer | Neurons | Activation |
|--------|--------:|------------|
| Input Layer | 10 Features | - |
| Hidden Layer 1 | 16 | ReLU |
| Hidden Layer 2 | 8 | ReLU |
| Output Layer | 1 | Sigmoid |

##  Model Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Metric: Accuracy
- Epochs: 20
- Batch Size: 32
- Validation Split: 20%

##  Evaluation
The trained model is evaluated on the test dataset, and the final test accuracy is displayed.

##  File
- `ANN Basic.ipynb` – Complete Jupyter Notebook implementation

##  Learning Objectives
- Understand the basics of Artificial Neural Networks
- Learn binary classification using Keras
- Practice preprocessing with StandardScaler
- Build and evaluate a neural network model

##  Author
**Arijit Dasgupta**
