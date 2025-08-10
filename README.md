# MNIST Neural Network From Scratch

This project implements a simple neural network from scratch in Python (using only NumPy and Pandas) to classify handwritten digits from the MNIST dataset.

## Features

- Loads and preprocesses the MNIST dataset from CSV.
- Implements a two-layer neural network with ReLU and softmax activations.
- Trains the network using gradient descent.
- Evaluates accuracy and visualizes predictions.

## Requirements

- Python 3.6+
- NumPy
- Pandas
- Matplotlib

## Usage

1. Place the `train.csv` file from the [Kaggle Digit Recognizer competition](https://www.kaggle.com/c/digit-recognizer/data) in the appropriate directory (e.g., `/kaggle/input/digit-recognizer/train.csv`).
2. Open and run the notebook `minst-from-scratch.ipynb` cell by cell.
3. The notebook will train the model and show predictions on sample images.

## File Structure

- `minst-from-scratch.ipynb` — Main Jupyter notebook containing all code.

## Example

After training, the notebook will display predictions and the corresponding digit images.

---

**Note:** This implementation is for educational purposes and does not use any deep
