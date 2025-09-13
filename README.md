# Deep Learning from First Principles: A NumPy Implementation Journey

> "What I cannot create, I do not understand." – Richard Feynman

This repository serves as a central hub for a series of projects dedicated to implementing core deep learning architectures **entirely from scratch using only NumPy**. This collection is a testament to the belief that true mastery comes from building from the ground up, moving beyond high-level frameworks to understand the fundamental mathematics and mechanics that power modern AI.

Each project deconstructs a key architecture, manually implementing everything from forward and backward propagation to optimizers and loss functions. This journey is about transforming theory into tangible, working code.

---

## 🏛️ The Architectures

This collection covers three foundational pillars of deep learning: Deep Neural Networks (DNNs), Convolutional Neural Networks (CNNs), and Recurrent Neural Networks (RNNs).

### 🧠 I. Deep Neural Network (DNN)

This project lays the groundwork, featuring a fully-featured, modular feedforward neural network. It's an exhaustive exploration of the components that make deep learning models tick, with extensive experimentation and visualization.

<p align="center">
  <img src="https://raw.githubusercontent.com/nabeelshan78/deep-nn-from-scratch/main/images/optimizers_comp.png" alt="Optimizer Comparison" width="600"/>
  <em><br>Comparing the convergence of from-scratch optimizers (GD, Momentum, RMSProp, Adam).</em>
</p>

**Key Features Implemented:**
-   **Core:** Multi-layer forward and backward propagation.
-   **Activations:** Sigmoid, ReLU.
-   **Optimizers:** Gradient Descent, Momentum, RMSProp, and Adam.
-   **Regularization:** Dropout and L2 Regularization.
-   **Initializations:** Random, Xavier, and He initializations.

**[➡️ View the Full DNN Project & Code](https://github.com/nabeelshan78/deep-nn-from-scratch)**

---

### 🖼️ II. Convolutional Neural Network (CNN)

This project tackles the domain of computer vision by building a CNN from scratch to classify sign language digits. It focuses on implementing the specialized layers—Convolution and Pooling—that allow networks to understand spatial hierarchies in images.

<p align="center">
  <img src="https://raw.githubusercontent.com/nabeelshan78/cnn-from-scratch-sign-digits/main/images/Convolution_schematic.gif" alt="Convolution Operation" width="700"/>
  <em><br>Visualizing the from-scratch 2D convolution operation.</em>
</p>

**Key Features Implemented:**
-   **Core Layers:** `Conv2D`, `MaxPooling`, `Flatten`, and `Dense`.
-   **Data Flow:** End-to-end management of 3D tensor shapes through the network.
-   **Application:** Trained and validated on a real-world image classification task.
-   **Backpropagation:** Custom gradient calculations for every layer, including convolutional and pooling layers.

**[➡️ View the Full CNN Project & Code](https://github.com/nabeelshan78/cnn-from-scratch-sign-digits)**

---

### ✍️ III. Recurrent Neural Network (RNN)

This section explores sequence modeling by implementing a character-level RNN. It demonstrates how to process sequential data, maintain state through a hidden vector, and implement the Backpropagation Through Time (BPTT) algorithm. This concept is showcased through two distinct applications.

<p align="center">
  <img src="https://raw.githubusercontent.com/nabeelshan78/char-rnn-dino-name-generator/main/images/rnn-forward-pass-unrolled.png" alt="Unrolled RNN" width="800"/>
  <em><br>The unrolled data flow of an RNN over multiple time steps.</em>
</p>

#### Project 1: Vanilla RNN for Text Generation
A foundational implementation that learns to generate text one character at a time based on a training corpus.

- **[➡️ View the Vanilla RNN Project](https://github.com/nabeelshan78/vanilla-rnn-from-scratch)**

#### Project 2: 🦖 Dinosaur Name Generator
A fun, applied version of the character-level RNN, trained on a dataset of dinosaur names to generate new, unique names. This project includes key improvements like gradient clipping to prevent the exploding gradients problem common in RNNs.

| Start Character | Generated Name    |
| :-------------: | ----------------- |
|        C        | Chuanosaurus      |
|        V        | Veratos           |
|        J        | Juranosaurus      |
|        T        | Tanlosaurus       |
|        Y        | Yropatos          |

- **[➡️ View the Dino Name Generator Project](https://github.com/nabeelshan78/char-rnn-dino-name-generator)**

---

## Core Concepts Mastered Across All Projects

* **100% NumPy:** No TensorFlow, PyTorch, or Keras. Every calculation is explicit.
* **Forward & Backward Propagation:** Manually coded gradient calculations using the chain rule for all architectures.
* **Gradient Descent & Optimizers:** Implementation and comparison of various optimization algorithms.
* **Loss Functions:** From-scratch implementation of Binary and Categorical Cross-Entropy.
* **Data Handling:** Vectorized operations for efficient processing of batches and sequences.
* **Deep Intuition:** A practical, code-first understanding of the internal mechanics of deep learning.

---

## 👨‍💻 About Me

**Nabeel Shan** Undergraduate Software Engineering Student - NUST Islamabad  
Aspiring AI Researcher & Machine Learning Engineer

I am passionate about deconstructing complex systems to their first principles. This collection of projects represents my hands-on approach to mastering deep learning. I am actively seeking research and collaboration opportunities in AI/ML.

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/nabeelshan)
[<img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" />](https://github.com/nabeelshan78)

---

## ⭐ Support This Work

If you find this collection of projects insightful or educational, please consider starring this hub repository and the individual project repositories. Your support helps others discover this work and encourages future open-source contributions.
