# Deep Learning Lab Exercise 2

## Activation Functions, Optimization Algorithms and Experiment Management

### Student Details

* **Name:** Johiya Sri
* **Roll No:** 24BAD050
* **Course:** Deep Learning
* **Platform:** Google Colab

---

## Aim

To analyze the impact of different activation functions and optimization algorithms on the performance of Artificial Neural Networks (ANNs) and to learn best practices for managing deep learning experiments using cloud-based tools and version control.

## Software Requirements

* Python
* TensorFlow
* Google Colab
* Google Drive
* GitHub
* Matplotlib
* Pandas
* NumPy

## Objectives

* Understand the role of activation functions in neural networks.
* Visualize and compare Sigmoid, Tanh, and ReLU activation functions.
* Evaluate the performance of different activation functions in ANN models.
* Analyze different gradient-based optimization algorithms.
* Compare optimizer convergence and model accuracy.
* Learn experiment management using Google Colab, Google Drive, and GitHub.
* Maintain reproducible experiments using version control.

---

## Tasks Performed

### Task A – Visualization of Activation Functions

The following activation functions were implemented and visualized:

* Sigmoid
* Tanh
* ReLU

Their output ranges, saturation behavior, gradient characteristics, computational efficiency, and typical applications were compared.

### Task B – Performance Comparison of Activation Functions

An identical ANN architecture was trained using:

* Sigmoid
* Tanh
* ReLU

The following performance measures were compared:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Number of Epochs

### Task C – Comparison of Optimization Algorithms

The same ANN architecture was trained using:

* SGD
* Momentum
* RMSProp
* Adam

Training and validation loss and accuracy were compared using graphs to analyze convergence behavior and generalization.

### Task D – Deep Learning Experiment Management

The experiment was managed using:

* Google Colab for coding and execution.
* Google Drive for storing models and experiment files.
* GitHub for version control and collaboration.
* README.md for documenting the experiment.

---

## Dataset

**Dataset:** MNIST Handwritten Digit Dataset

The MNIST dataset contains images of handwritten digits from 0 to 9 and is commonly used for image classification experiments.

---

## Technologies Used

| Technology   | Purpose                           |
| ------------ | --------------------------------- |
| Python       | Programming                       |
| TensorFlow   | Building and training ANN models  |
| Google Colab | Cloud-based experiment execution  |
| Google Drive | Storage and backup                |
| GitHub       | Version control and collaboration |
| Matplotlib   | Visualization                     |
| Pandas       | Result analysis                   |
| NumPy        | Numerical operations              |

---

## Key Observations

* **ReLU** generally provided faster training and good validation performance compared with Sigmoid and Tanh.
* **Sigmoid** can suffer from the vanishing gradient problem, which may slow training.
* **Momentum** improves upon basic SGD by reducing oscillations during optimization.
* **RMSProp** provides adaptive learning rates and generally converges faster than basic SGD.
* **Adam** generally provides fast and stable convergence and good validation performance.

---

## Conclusion

The experiment demonstrated the importance of selecting suitable activation functions and optimization algorithms for neural networks. ReLU was observed to be effective for hidden layers because of its computational efficiency and better gradient behavior. Among the optimizers, Adam generally provided faster and more stable convergence. Google Colab, Google Drive, and GitHub helped in executing, storing, documenting, and managing the deep learning experiments in a reproducible manner.

