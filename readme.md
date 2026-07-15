# Handwritten Digit Recognition using Deep Neural Networks

Implementation and comparative analysis of shallow, medium, and deep fully-connected neural networks for handwritten digit classification using the MNIST dataset.

---

## Overview

This project investigates how neural network depth influences classification performance on the MNIST handwritten digit dataset.

Three architectures were implemented using TensorFlow/Keras and evaluated using identical training settings.

The project was completed as part of an undergraduate Deep Learning course and demonstrates the complete deep learning workflow, including

- data preprocessing
- model development
- training
- validation
- performance evaluation
- model deployment
- inference on unseen handwritten images

---

## Dataset

- Dataset: MNIST
- Training images: 60,000
- Test images: 10,000
- Image size: 28×28 grayscale
- Classes: 10

---

## Models

| Model | Architecture |
|--------|--------------|
| Shallow | 128 |
| Medium | 256 → 128 |
| Deep | 512 → 256 → 128 |

All models use

- ReLU activation
- Adam optimizer
- Sparse Categorical Crossentropy
- Softmax output layer

---

## Results

| Model | Test Accuracy |
|--------|--------------:|
| Shallow | 97.61% |
| Medium | 97.90% |
| Deep | 98.17% |

The deeper architecture achieved the highest classification accuracy while requiring additional computational cost.

---

## Repository Structure

```
train.py
inference.py
models/
figures/
notebooks/
```

---

## Example Results

(Add your training curve here)

(Add confusion matrix)

(Add prediction examples)

---

## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## Future Improvements

- CNN implementation
- Data augmentation
- Batch Normalization
- Residual Networks
- Model quantization
- ONNX deployment

---

## Author

Mamun Or Rashid

Department of Mechatronics Engineering

Rajshahi University of Engineering & Technology

