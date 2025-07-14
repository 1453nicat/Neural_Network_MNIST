# Neural_Network_MNIST

This project implements a neural network for classifying handwritten digits from the MNIST dataset using TensorFlow and Keras. The model includes multiple hidden layers with ReLU activation and dropout for regularization, achieving approximately 98% test accuracy. The training process is visualized through accuracy and loss curves, saved as history.png.

# Model Architecture

- Input Layer: Flattened 28x28 images (784 features).
- Hidden Layers:
1. Dense layer (512 units, ReLU activation) with 30% dropout.
2. Dense layer (256 units, ReLU activation) with 30% dropout.
3. Dense layer (128 units, ReLU activation).
- Output Layer: Dense layer (10 units, softmax activation), Optimizer: Adam, Loss Function: Categorical crossentropy, Metrics: Accuracy.

# Training

- Epochs: 20
- Batch Size: 128
- Validation Split: 20%

# Output

- Console output includes the model summary, training progress, and final test accuracy/loss.
- A plot (training_history.png) visualizes training and validation accuracy/loss over epochs.

# Results

The model demonstrates stable convergence with minimal overfitting, as shown in the accuracy and loss curves. The high test accuracy indicates effective learning and generalization for the MNIST digit classification task.

MIT License 
Copyright (c) 2025 *1453nicat*
