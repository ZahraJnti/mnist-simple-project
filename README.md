# mnist-simple-project

This project implements a simple digit classifier using the MNIST dataset of handwritten digits. It uses a neural network model to recognize digits (0–9) from 28x28 grayscale images. The goal is to demonstrate a minimal working example of building, training, and evaluating a machine learning model on a classic dataset.

---

## 📁 Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)


---

## Overview

The project is built in a single Jupyter Notebook and covers:

- Loading the MNIST dataset
- Preprocessing input data
- Building a simple neural network model
- Training the model on the training set
- Evaluating the model on the test set
- Visualizing some sample predictions

---

## Technologies Used

- Python 3.x
- Jupyter Notebook
- TensorFlow / Keras (for model building and training)
- NumPy
- Matplotlib (for plotting predictions and results)

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mnist_simple_project.git
cd mnist_simple_project
```
2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```


3. Install the required packages:

```bash
pip install numpy matplotlib tensorflow
```

## Usage
You can run the notebook step by step in Jupyter:

```bash
jupyter notebook mnist_simple_project.ipynb
```

## Results
-  Model Accuracy: ~98% on the test set (depending on architecture and epochs)

-  Loss and accuracy plots included

-  Visual examples of correct and incorrect predictions

