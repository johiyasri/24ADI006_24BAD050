# LAB EXERCISE 3

## Convolutional Neural Network for Image Classification

### Student Details

* **Name:** Johiya Sri
* **Roll No:** 24BAD050
* **Course:** Deep Learning
* **Platform:** Google Colab

---

## Aim

To design, implement, and evaluate a Convolutional Neural Network (CNN) for image classification using a benchmark image dataset.

## Software Requirements

* Python
* TensorFlow/Keras
* Google Colab
* Matplotlib
* NumPy
* CIFAR-10 Dataset

## Objectives

* Understand the architecture of Convolutional Neural Networks.
* Implement a CNN model for image classification.
* Train and evaluate a CNN using a benchmark image dataset.
* Visualize training and validation performance.
* Analyze the effectiveness of CNNs for image recognition tasks.

---

## Dataset

The **CIFAR-10 dataset** was used for this experiment.

CIFAR-10 contains **60,000 color images** belonging to **10 different classes**. The images have a size of **32 × 32 pixels**.

### Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

The dataset was loaded directly using TensorFlow/Keras and the images were normalized to values between **0 and 1**.

---

## Tasks Performed

### Task A – Dataset Preparation

The CIFAR-10 dataset was:

* Downloaded and loaded using TensorFlow.
* Normalized by scaling pixel values from 0–255 to 0–1.
* Divided into training, validation, and testing datasets.
* Sample images were visualized along with their class labels.

### Task B – CNN Model Implementation

A CNN model was designed using:

* Convolutional layers
* ReLU activation
* Max Pooling layers
* Flatten layer
* Fully Connected Dense layer
* Softmax output layer

The model was compiled using:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Cross-Entropy
* **Evaluation Metric:** Accuracy

### Task C – Model Training and Evaluation

The CNN model was trained using the CIFAR-10 training dataset.

The following measures were recorded:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Testing Accuracy
* Testing Loss

Graphs were plotted for:

* Accuracy vs Epoch
* Loss vs Epoch

### Task D – Performance Analysis

The trained model was analyzed using:

* Classification accuracy
* Confusion matrix
* Sample predictions
* Misclassified images

The strengths and limitations of CNNs for image classification were also studied.

---

## CNN Architecture

```text
Input Image
    ↓
Convolution Layer (32 Filters)
    ↓
ReLU Activation
    ↓
Max Pooling
    ↓
Convolution Layer (64 Filters)
    ↓
ReLU Activation
    ↓
Max Pooling
    ↓
Convolution Layer (128 Filters)
    ↓
ReLU Activation
    ↓
Flatten
    ↓
Dense Layer (128 Neurons)
    ↓
ReLU Activation
    ↓
Output Layer (10 Classes)
    ↓
Softmax
```

---

## Technologies Used

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| Python           | Programming                     |
| TensorFlow/Keras | CNN implementation and training |
| Google Colab     | Cloud-based execution           |
| CIFAR-10         | Image classification dataset    |
| Matplotlib       | Visualization                   |
| NumPy            | Numerical processing            |

---

## Results

The CNN model was successfully trained on the CIFAR-10 dataset.

The model performance was evaluated using training accuracy, validation accuracy, loss, and testing accuracy. Accuracy and loss graphs were used to observe the learning behavior of the model.

The confusion matrix and sample predictions were used to analyze the classification performance of individual classes.

**Testing Accuracy:** Add your obtained accuracy here.

---

## Observations

* Convolution layers effectively extracted important visual features from the images.
* ReLU activation helped the network learn non-linear patterns efficiently.
* Max Pooling reduced the spatial dimensions and computational requirements.
* Adam optimizer provided effective model convergence.
* Some classes with visually similar features were more difficult for the CNN to classify correctly.

---

## Strengths of CNN

* Automatically learns important image features.
* Effective for image classification and recognition.
* Requires fewer parameters than fully connected networks for image data.
* Preserves spatial relationships between image features.

## Limitations of CNN

* Requires considerable computational resources for complex models.
* Training can take significant time.
* May suffer from overfitting when training data is insufficient.
* Performance depends on suitable architecture and hyperparameter selection.

---

## Conclusion

A Convolutional Neural Network was successfully implemented for image classification using the CIFAR-10 dataset. The experiment demonstrated how convolution, ReLU activation, max pooling, and fully connected layers work together to extract features and classify images. The model was trained and evaluated using accuracy and loss metrics, and its performance was further analyzed using a confusion matrix and sample predictions. Overall, CNNs are highly effective for image classification tasks.


