## 🖋️ MNIST Handwritten Digit Classification

Welcome to the **MNIST Handwritten Digit Classifier** project! 🎉 Here, we’ll train a simple ANN (Artificial Neural Network) to recognize handwritten digits (0-9). Who knew teaching a machine to read numbers could be so cool? 😎

### 📚 Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [License](#license)

---

### 🧐 Project Overview
This project aims to solve the problem of classifying handwritten digits from the famous **MNIST** dataset. The dataset contains **28x28 grayscale images** of handwritten numbers. Our job is to train an ANN to guess what number is in each image! ✍️

We’ll be using a simple architecture (just a couple of hidden layers, nothing too fancy). The goal? Achieve some solid accuracy while keeping the model light and understandable.

### ⚙️ Installation
Make sure you’ve got Python and the necessary libraries installed. Here’s how to get started:

1. Clone the repo:
   ```bash
   git clone https://github.com/your-repo/mnist-classifier.git
   ```
2. Install the dependencies:

    ```bash
      pip install -r requirements.txt
    ```
### 🧠 Model Architecture
We’re using a simple ANN with the following layers:
- **Input Layer**: 784 neurons (because, 28x28 pixels = 784)
- **Hidden Layer 1**: 64 neurons, ReLU activation
- **Hidden Layer 2**: 32 neurons, ReLU activation
- **Dropout Layer**:  50% dropout for regularization
- **Output Layer**: 10 neurons, Softmax activation (to classify digits 0-9)

Even though it’s a straightforward model, it packs a punch for this dataset! 💥

### 📊 Results
The model achieves an accuracy of around **89%** on the test data. Not too shabby, right? 📈


### 📄 License
This project is open-source under the **MIT License**. Steal it, tweak it, make it your own!

---

And that’s it! Time to teach those machines to read. 🤖📚

---
