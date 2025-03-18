# Neural Network using NumPy only

This project implements a simple neural network using only NumPy, without external deep learning libraries. The training loop and evaluation functions are included, but the network is not structured as an explicit class.

## 📌 Features
- Implements a training loop for updating weights.
- Uses NumPy for numerical operations.
- Includes an evaluation function to measure model performance.
- No explicit object-oriented class structure; computations occur in the training loop.

## 🚀 Getting Started

### **Requirements**
- Python 3.x
- Matplotlib
- NumPy
- Jupyter Notebook (optional, for running `neural_network.ipynb`)

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neural-network.git
   cd neural-network
   ```
2. Install dependencies:
   ```bash
   pip install numpy
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook neural_network.ipynb
   ```

## 📖 Usage
- The training loop iterates over epochs to adjust weights.
- Forward propagation and backpropagation computations occur inside the loop.
- The model is evaluated using an accuracy function.

## 📝 Notes
- This implementation does not use an explicit `NeuralNetwork` class.
- Forward propagation and weight updates occur directly inside the training loop.
- You can modify hyperparameters (epochs, learning rate) directly in the notebook.

## 🔧 Possible Improvements
- Convert the model into an object-oriented class (`NeuralNetwork`).
- Implement activation functions and layer flexibility.
- Optimize performance with vectorized NumPy operations.
