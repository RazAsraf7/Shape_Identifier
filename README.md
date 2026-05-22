# Custom ANN Shape Classifier (Built From Scratch)

A multiclass classification machine learning model designed to recognize and classify geometric shapes from images using a custom Artificial Neural Network (ANN) algorithm built completely from scratch.

## 🚀 Project Overview
This project demonstrates the complete process of building, training, and evaluating a Artificial Neural Network (ANN) without relying on high-level machine learning frameworks (like PyTorch or TensorFlow's Keras layers) for the network model itself. Every mathematical calculation, forward propagation, and backward propagation step was manually calculated and implemented in pure Python/NumPy.

The model is designed to classify images into one of **8 distinct geometric shapes**:
* 🔺 Triangle
* ⬠ Trapezoid
* ◼️ Square
* 🔶 Rhombus
* █ Rectangle
* ▱ Parallelogram
* 🪁 Kite
* ⚪ Circle

## 🧠 Core Implementation Details & Math
Since the algorithm was constructed from the ground up, the project contains raw implementations of:
- **Matrix Calculations & Gradients:** Manual formulation of weight updates and biases.
- **Activation Functions:** Custom implementations of hidden layer and output layer activation functions (e.g., ReLU/Sigmoid, Softmax) along with their derivatives for backpropagation.
- **Optimization:** Pure algorithmic calculation of loss function and learning rate updates.

## 📊 Dataset Structure
The image pipeline is managed via a structured dynamic catalog (`.csv`) containing the following metadata:
- **File Path:** Relative path mapping each image in the dataset.
- **Label:** The target ground-truth classification (one of the 8 shapes).
- **Dataset Split:** Categorization for proper data partitioning into `train`, `validation`, and `test` sets.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Core Math:** NumPy, Pandas
- **Image Processing:** PIL (Pillow)
- **Data Visualization:** Matplotlib, Seaborn

## 🤖 AI Assistance Disclaimer
In the spirit of transparency, AI tools were utilized during the development of this project for:
1. Gaining a deeper theoretical understanding of the ANN architecture and backpropagation mechanics.
2. Reviewing the correctness of complex mathematical equations and grammar in the documentation.
3. Code optimization, "cleanup", and enhancing data visualizations/plots.

---
*Created as a Final Project by:*
* Raz Asraf
* Tal Leibovitz
* Adir Beitbabu