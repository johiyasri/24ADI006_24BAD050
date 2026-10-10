# Deep Learning Lab Exercise 6 – LSTM Sentiment Analysis

## Sentiment Analysis of Movie Reviews Using Long Short-Term Memory (LSTM)

### Student Details

* **Name:** Johiya Sri S
* **Roll No:** 24BAD050
* **Course:** Deep Learning
* **Platform:** Google Colab

---

## Aim

To implement an LSTM-based deep learning model for sentiment analysis of movie reviews and classify textual data into positive and negative sentiments. To evaluate the model using suitable performance metrics and visualize its training performance.

## Software Requirements

* Python
* TensorFlow
* Google Colab
* NumPy
* Matplotlib
* Scikit-learn
* Seaborn
* GitHub

## Objectives

* Understand the working of LSTM networks for sequential data.
* Load and explore the IMDB movie review dataset.
* Perform text preprocessing and sequence padding.
* Convert text reviews into numerical sequences.
* Build an LSTM model for binary sentiment classification.
* Train and validate the model using the prepared dataset.
* Evaluate model performance using accuracy, precision, recall, and F1-score.
* Generate a confusion matrix and visualize accuracy and loss.
* Predict sentiments for new movie reviews.
* Document the experiment using GitHub.

---

## Tasks Performed

### Task A – Dataset Preparation

The IMDB movie review dataset was loaded and prepared for sentiment analysis.

The following operations were performed:

* Loaded the IMDB dataset.
* Examined sample reviews and sentiment labels.
* Identified positive and negative sentiment classes.
* Used the dataset vocabulary to represent words as integers.
* Converted reviews into numerical sequences.
* Applied sequence padding to obtain equal-length inputs.
* Split the training data into training and validation datasets.

### Task B – Implementing the LSTM Model

An LSTM model was created using TensorFlow and Keras.

The model consists of:

* **Embedding Layer:** Converts word indices into dense vector representations.
* **LSTM Layer:** Learns sequential patterns and long-term dependencies in reviews.
* **Dense Output Layer:** Uses the Sigmoid activation function to predict sentiment probability.

The model was compiled using the Adam optimizer, binary cross-entropy loss function, and accuracy metric.

### Task C – Model Training and Performance Evaluation

The LSTM model was trained using the prepared training dataset and validated using the validation dataset.

The following performance measures were recorded:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Test Accuracy
* Test Loss
* Precision
* Recall
* F1-score

A confusion matrix was generated to analyze the classification results. Accuracy versus epoch and loss versus epoch graphs were plotted to visualize the model's learning performance.

### Task D – Sentiment Prediction and Experiment Management

The trained LSTM model was used to predict the sentiment of new movie reviews.

The following operations were performed:

* Provided new movie reviews as input.
* Converted the reviews into numerical sequences using the dataset vocabulary.
* Applied sequence padding.
* Predicted positive or negative sentiment using the model.
* Compared predicted sentiments with expected sentiments.
* Examined the correctness of the predictions.
* Documented the experiment using GitHub.

---

## Dataset

**Dataset:** IMDB Movie Reviews Dataset

The IMDB dataset contains movie reviews labeled as positive or negative. It is widely used for binary sentiment classification and natural language processing tasks.

The dataset provided by Keras contains 25,000 training reviews and 25,000 testing reviews. In this experiment, the training data was further divided into training and validation sets.

---

## Technologies Used

| **Technology** | **Purpose**                             |
| -------------- | --------------------------------------- |
| Python         | Programming                             |
| TensorFlow     | Building and training the LSTM model    |
| Keras          | Creating neural network layers          |
| Google Colab   | Cloud-based code execution              |
| NumPy          | Numerical operations                    |
| Matplotlib     | Visualizing accuracy and loss           |
| Scikit-learn   | Evaluation metrics and confusion matrix |
| Seaborn        | Confusion matrix visualization          |
| GitHub         | Version control and documentation       |

---

## Model Architecture

The LSTM sentiment classification model consists of the following layers:

1. **Embedding Layer:** Converts integer-encoded words into 64-dimensional vectors.
2. **LSTM Layer:** Contains 64 units to learn sequential information.
3. **Dense Layer:** Uses one output neuron with Sigmoid activation for binary classification.

**Optimizer:** Adam

**Loss Function:** Binary Cross-Entropy

**Evaluation Metric:** Accuracy

**Maximum Vocabulary Size:** 10,000 words

**Maximum Sequence Length:** 200 words

**Training Epochs:** 5

---

## Key Observations

* LSTM can learn sequential patterns and long-term dependencies in textual data.
* The embedding layer converts numerical word indices into dense vector representations.
* The Sigmoid activation function produces a probability for positive sentiment.
* Binary cross-entropy is suitable for positive and negative sentiment classification.
* Accuracy, precision, recall, and F1-score help evaluate classification performance.
* The confusion matrix shows correct and incorrect predictions for both sentiment classes.
* Accuracy and loss graphs help analyze model learning and generalization.
* Prediction performance depends on the quality of the dataset, preprocessing, and model training.

---

## Conclusion

The experiment demonstrated the implementation of an LSTM-based sentiment analysis model using the IMDB movie review dataset. The model was trained to classify reviews as positive or negative using an embedding layer, an LSTM layer, and a Sigmoid output layer. Its performance was evaluated using accuracy, precision, recall, F1-score, a confusion matrix, and training graphs. The experiment also demonstrated how a trained model can predict the sentiment of new movie reviews. Google Colab and GitHub were used for executing, documenting, and managing the experiment.
