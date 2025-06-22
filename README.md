# MNIST Digit Classifier

This project is a simple neural network built with TensorFlow and Keras that classifies handwritten digits (0–9) from the MNIST dataset.

## Project Structure

- `mnist_model.ipynb` — Jupyter Notebook containing all model code, preprocessing, training, and evaluation.
- `requirements.txt` — List of required libraries to run the notebook.
- `README.md` — Project description and setup instructions.

## What It Does

- Loads and preprocesses the MNIST dataset.
- Applies one-hot encoding and normalization.
- Builds a feedforward neural network using Keras.
- Trains the model and evaluates accuracy.
- Plots accuracy and loss across epochs.

## Results

The model reaches over **98% accuracy** after a few epochs using a simple architecture.

## Requirements

- Python 3.10 or 3.11
- TensorFlow
- NumPy
- scikit-learn
- Matplotlib

To install all requirements:

```bash
pip install -r requirements.txt
