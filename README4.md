LAB EXERCISE 4
Transfer Learning Using Pre-Trained Vision Models
Student Details
Name: Johiya Sri
Roll No: 24BAD050
Course: Deep Learning
Platform: Google Colab

Aim

To implement transfer learning using pre-trained vision models for image recognition and evaluate their performance on a real-world image dataset.

Software Requirements

Python
TensorFlow/Keras
Google Colab
Hugging Face Transformers
Kaggle Dataset
Matplotlib
NumPy
PIL
GitHub

Objectives

Understand the concept of transfer learning in deep learning.
Apply pre-trained vision models for image classification.
Implement transfer learning using the ResNet50 model.
Freeze pre-trained feature extraction layers.
Fine-tune the pre-trained model for a specific classification task.
Evaluate the performance of the transfer learning model.
Utilize Kaggle datasets and Hugging Face pre-trained vision models.
Compare predictions from the transfer learning model and Hugging Face model.
Dataset

The Cats and Dogs Image Classification dataset was used for this experiment.

The dataset was obtained from Kaggle and contains images belonging to two classes.

Classes
Cat
Dog

The dataset was divided into:

70% Training Dataset
15% Validation Dataset
15% Testing Dataset

The images were resized to 224 × 224 pixels and normalized before being used for model training.

Tasks Performed

Task A – Dataset Preparation

The Cats and Dogs dataset was:

Downloaded from Kaggle.
Extracted and organized into Cat and Dog folders.
Divided into training, validation, and testing datasets.
Resized to 224 × 224 pixels.
Normalized to scale pixel values between 0 and 1.
Visualized using sample images with their corresponding class labels.

Task B – Transfer Learning Model Implementation

The ResNet50 pre-trained model was used for transfer learning.

The following steps were performed:

Loaded ResNet50 with pre-trained ImageNet weights.
Removed the original classification layer.
Added new classification layers for Cat and Dog classes.
Froze the pre-trained feature extraction layers.
Added Global Average Pooling and Dense layers.
Compiled the model using the Adam optimizer.
Fine-tuned the final layers of the model.

Task C – Model Training and Evaluation

The transfer learning model was trained using the training dataset and validated using the validation dataset.

The following measures were recorded:

Training Accuracy
Validation Accuracy
Training Loss
Validation Loss
Testing Accuracy
Fine-Tuned Testing Accuracy

Graphs were plotted for:

Accuracy vs Epoch
Loss vs Epoch

Task D – Using Hugging Face Pre-Trained Models

A pre-trained ResNet50 model from Hugging Face was used for image classification.

The following operations were performed:

Loaded the microsoft/resnet-50 model.
Selected sample images from the test dataset.
Performed image classification.
Recorded predicted labels and confidence scores.
Compared Hugging Face predictions with the transfer learning model.
Analyzed the differences between the two model predictions.

Transfer Learning Architecture

Input Image
    ↓
Pre-trained ResNet50
    ↓
Frozen Feature Extraction Layers
    ↓
Global Average Pooling
    ↓
Dense Layer (128 Neurons)
    ↓
ReLU Activation
    ↓
Output Layer (2 Classes)
    ↓
Softmax
    ↓
Cat / Dog

Technologies Used

Technology	Purpose
Python	Programming
TensorFlow/Keras	Transfer learning implementation and model training
ResNet50	Pre-trained vision model
Hugging Face Transformers	Pre-trained vision model experimentation
Google Colab	Cloud-based execution
Kaggle	Image dataset
Matplotlib	Visualization
NumPy	Numerical processing
PIL	Image processing
GitHub	Version control and documentation

Results

The ResNet50 transfer learning model was successfully trained on the Cats and Dogs dataset.

The model performance was evaluated using training accuracy, validation accuracy, training loss, validation loss, and testing accuracy. Accuracy and loss graphs were generated to analyze the learning behavior of the model.

Fine-tuning was performed by unfreezing the final layers of the pre-trained ResNet50 model and training them with a smaller learning rate.

A pre-trained ResNet50 model from Hugging Face was also used to classify sample images, and its predictions were compared with the task-specific transfer learning model.

Training Accuracy: Add your obtained accuracy here.
Validation Accuracy: Add your obtained accuracy here.
Test Accuracy: Add your obtained accuracy here.
Fine-Tuned Test Accuracy: Add your obtained accuracy here.

Conclusion

Transfer learning was successfully implemented using the pre-trained ResNet50 model for Cat and Dog image classification. The experiment demonstrated how previously learned features can be reused for a new image classification task, reducing training time and computational requirements. The model was trained, evaluated, and fine-tuned using the target dataset.

A pre-trained ResNet50 model from Hugging Face was also used for image classification, and its predictions were compared with the task-specific transfer learning model. Overall, transfer learning provides an efficient and effective approach for developing image classification models using pre-trained deep learning architectures.
