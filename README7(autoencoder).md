# EXPERIMENT 7 – AUTOENCODER FOR DIMENSIONALITY REDUCTION AND FEATURE LEARNING

## STUDENT DETAILS

- **Name:** JOHIYA SRI S
- **Roll Number:** 24BAD050
- **Department:** Artificial Intelligence and Data Science
- **Year:** III Year
- **Experiment No.:** 7
- **Experiment Name:** Implementation of Autoencoder for Dimensionality Reduction and Feature Learning

## AIM

To implement and train a simple Autoencoder for dimensionality reduction and feature learning by compressing input data into a lower-dimensional representation and reconstructing the original data from the learned features.

## SOFTWARE REQUIREMENTS

- Python
- TensorFlow
- Keras
- Google Colab
- GitHub
- NumPy
- Matplotlib
- Pandas
- Scikit-learn

## OBJECTIVES

1. To understand the architecture and working of an Autoencoder.
2. To identify the functions of the Encoder, Bottleneck, and Decoder.
3. To prepare and normalize input data for Autoencoder training.
4. To build and train an Autoencoder using a suitable dataset.
5. To perform dimensionality reduction through latent-space representations.
6. To evaluate reconstruction performance using suitable loss metrics.
7. To visualize reconstructed data and analyze learned features.
8. To document the experiment and manage the notebook using GitHub.

## DATASET USED

**MNIST Handwritten Digit Dataset**

- Contains 60,000 training images and 10,000 testing images.
- Each image has a dimension of 28 × 28 pixels.
- Contains handwritten digits from 0 to 9.
- Pixel values are normalized between 0 and 1.
- Each image is reshaped into a one-dimensional vector of 784 features.

## PROCEDURE

### PART A – Dataset Preparation

- Load the MNIST handwritten digit dataset.
- Display sample input images.
- Examine image dimensions and data types.
- Normalize pixel values between 0 and 1.
- Reshape images into one-dimensional vectors.
- Split the dataset into training and testing data.
- Use original input data as target output.

### PART B – Implementing the Autoencoder Model

- Define the input layer with 784 neurons.
- Build an Encoder using Dense layers.
- Introduce a Bottleneck layer with 32 neurons.
- Build a Decoder to reconstruct the original input.
- Use ReLU and Sigmoid activation functions.
- Combine the Encoder and Decoder to create the Autoencoder.
- Compile the model using Adam optimizer and Mean Squared Error (MSE) loss.
- Display model summaries.

### PART C – Model Training and Performance Evaluation

- Train the Autoencoder using the MNIST training dataset.
- Use original images as target outputs.
- Validate the model using testing data.
- Record training and validation losses.
- Calculate reconstruction Mean Squared Error.
- Plot training and validation loss graphs.
- Compare original images with reconstructed images.

### PART D – Dimensionality Reduction, Feature Visualization and Experiment Management

- Extract latent-space representations using the trained Encoder.
- Compare original and compressed data dimensions.
- Apply Principal Component Analysis (PCA).
- Visualize latent representations using a scatter plot.
- Reconstruct selected test images using the Decoder.
- Compare original and reconstructed images.
- Analyze dimensionality reduction and reconstruction quality.

## MODEL ARCHITECTURE

**Encoder:**
- Input Layer: 784 neurons
- Hidden Layer: 128 neurons with ReLU activation
- Bottleneck Layer: 32 neurons with ReLU activation

**Decoder:**
- Input Layer: 32 neurons
- Hidden Layer: 128 neurons with ReLU activation
- Output Layer: 784 neurons with Sigmoid activation

**Optimizer:** Adam

**Loss Function:** Mean Squared Error (MSE)

**Training Epochs:** 5

## EXPECTED OUTPUTS

1. Sample MNIST handwritten digit images.
2. Encoder, Decoder and Autoencoder model summaries.
3. Training and validation loss values.
4. Reconstruction MSE value.
5. Training and validation loss graph.
6. Original and reconstructed image comparison.
7. Latent-space feature visualization using PCA.
8. Compressed representation of input images.

## RESULT

Thus, a simple Autoencoder was successfully implemented and trained using the MNIST handwritten digit dataset. Dimensionality reduction was performed using the Encoder, and the Decoder reconstructed the original images from the compressed representations. The reconstruction performance was evaluated using Mean Squared Error.

## CONCLUSION

The experiment helped in understanding the working of Autoencoders, including the Encoder, Bottleneck and Decoder. It demonstrated how Autoencoders learn important features, reduce data dimensions and reconstruct input images with minimum reconstruction error.

---

**Submitted by:** JOHIYA SRI S  
**Roll Number:** 24BAD050  
**Experiment No.:** 7 – Autoencoder
