# EXPERIMENT 8 – GENERATIVE ADVERSARIAL NETWORK (GAN)

## Student Details

- **Name:** JOHIYA SRI S
- **Roll Number:** 24BAD050
- **Department:** Artificial Intelligence and Data Science
- **Year:** III Year
- **Experiment No.:** 8
- **Experiment Name:** Implementation of Generative Adversarial Network (GAN) for Synthetic Image Generation

## AIM

To implement and train a Generative Adversarial Network (GAN) to generate synthetic images by training a Generator and a Discriminator in an adversarial learning framework.

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

1. To understand the architecture and working of Generative Adversarial Networks.
2. To identify the functions of the Generator and Discriminator.
3. To prepare image datasets for GAN training.
4. To generate random noise vectors as inputs to the Generator.
5. To build and train a simple GAN using the MNIST dataset.
6. To understand adversarial training and associated loss functions.
7. To generate synthetic images and visualize the results.
8. To evaluate the quality and diversity of generated images.
9. To manage the experiment notebook using GitHub.

## DATASET USED

**MNIST Handwritten Digit Dataset**

- Contains 60,000 training images and 10,000 testing images.
- Each image has a dimension of 28 × 28 pixels.
- Images represent handwritten digits from 0 to 9.
- Pixel values are normalized from 0–255 to -1 to 1.

## PROCEDURE

### PART A – Dataset Preparation

- Load the MNIST dataset.
- Display sample handwritten digit images.
- Explore image dimensions and pixel-value ranges.
- Normalize and reshape the images.
- Prepare batches of real images for training.

### PART B – Implementing the Generator and Discriminator

- Build a Generator to create synthetic images from random noise.
- Build a Discriminator to classify images as real or fake.
- Select suitable layers, activation functions, optimizer, and loss function.
- Combine both models to construct the GAN.
- Display model summaries.

### PART C – GAN Training and Performance Monitoring

- Train the Discriminator using real and generated images.
- Train the Generator to produce realistic images.
- Alternate the training of both models.
- Record Generator and Discriminator losses.
- Plot the training loss graph.
- Display generated images during training.

### PART D – Dimensionality Reduction, Feature Visualization and Experiment Management

- Generate synthetic images using the trained Generator.
- Extract features using the Discriminator.
- Apply Principal Component Analysis (PCA) for dimensionality reduction.
- Compare original and generated images.
- Visualize real and generated image features.
- Observe image quality, diversity, and recognizability.

## EXPECTED OUTPUTS

1. Sample MNIST handwritten digit images.
2. Generator, Discriminator, and GAN model summaries.
3. Generated synthetic handwritten digit images.
4. Generator and Discriminator loss graph.
5. Comparison of original and generated images.
6. PCA feature visualization of real and generated images.

## RESULT

Thus, a Generative Adversarial Network (GAN) was successfully implemented and trained using the MNIST dataset. Synthetic handwritten digit images were generated using the Generator, and the quality of generated images was analyzed through visual comparison and PCA feature visualization.

## CONCLUSION

The experiment helped in understanding the working of GANs, the roles of Generator and Discriminator, adversarial training, and loss functions. It also demonstrated how GANs can generate synthetic images from random noise.

---
**Submitted by:** JOHIYA SRI S  
**Roll Number:** 24BAD050  
**Experiment:** 8 – Generative Adversarial Network (GAN)
