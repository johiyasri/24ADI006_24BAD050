# Recurrent Neural Network (RNN) for Text Generation

## Student Details

| Field           | Details                   |
| --------------- | ------------------------- |
| **Roll Number** | 24BAD050                  |
| **Name**        | Johiya Sri S              |
| **Experiment**  | RNN-Based Text Generation |
| **Dataset**     | Tiny Shakespeare          |
| **Platform**    | Google Colab              |

---

## Aim

To implement a Recurrent Neural Network (RNN) for text generation and evaluate its ability to generate meaningful text by predicting the next word in a sequence.

---

## Software Requirements

* Python
* TensorFlow / Keras
* Google Colab
* GitHub
* NumPy
* Matplotlib

---

## Dataset

The **Tiny Shakespeare** dataset contains text from Shakespeare's works. It is used to train the RNN to learn word sequences and predict the next word based on the given context.

---

## Tasks Performed

### Task A: Dataset Preparation

* Loaded the Tiny Shakespeare dataset.
* Explored the text samples.
* Converted the text into lowercase.
* Tokenized the text into individual words.
* Built a vocabulary and assigned integer indices to words.
* Generated input sequences for next-word prediction.
* Applied sequence padding.
* Split the data into training and validation datasets.

### Task B: Implementing the RNN Model

* Created an Embedding layer for word representations.
* Added a Simple RNN layer to learn sequential dependencies.
* Added a Dense output layer with Softmax activation.
* Compiled the model using the Adam optimizer and sparse categorical cross-entropy loss.
* Displayed the model architecture and summary.

### Task C: RNN Model Training and Performance Evaluation

* Trained the RNN model using the prepared dataset.
* Validated the model using validation data.
* Recorded training and validation accuracy.
* Recorded training and validation loss.
* Plotted accuracy versus epochs.
* Plotted loss versus epochs.

### Task D: Deep Learning Experiment Management

* Provided seed words or sentences as input.
* Generated text by repeatedly predicting the next word.
* Produced multiple text samples using different seed inputs.
* Compared the generated text for coherence and contextual relevance.

---

## Model Architecture

| Layer               | Description                                              |
| ------------------- | -------------------------------------------------------- |
| **Embedding**       | Converts word indices into dense vector representations. |
| **Simple RNN**      | Learns sequential dependencies between words.            |
| **Dense + Softmax** | Predicts the probability of the next word.               |

---

## Training Configuration

| Parameter               | Value                            |
| ----------------------- | -------------------------------- |
| **Optimizer**           | Adam                             |
| **Loss Function**       | Sparse Categorical Cross-Entropy |
| **Metric**              | Accuracy                         |
| **Epochs**              | 5                                |
| **Batch Size**          | 64                               |
| **Vocabulary Size**     | 2,000                            |
| **RNN Units**           | 64                               |
| **Embedding Dimension** | 32                               |

---

## Performance Evaluation

The model was evaluated using training and validation accuracy and loss.

| Metric                  | Value                   |
| ----------------------- | ----------------------- |
| **Training Accuracy**   | Enter your output value |
| **Validation Accuracy** | Enter your output value |
| **Training Loss**       | Enter your output value |
| **Validation Loss**     | Enter your output value |

### Graphs

* Accuracy vs. Epoch
* Loss vs. Epoch

---

## Text Generation

The trained RNN generates text by predicting the next word repeatedly based on the given seed input.

### Sample Seed Inputs

* `shall i compare thee`
* `the king`
* `to be or not to be`
* `love is`
* `what is`

### Sample Output

Enter the generated text obtained from your experiment here.

---

## Conclusion

The Recurrent Neural Network was successfully implemented for next-word prediction and text generation using the Tiny Shakespeare dataset. The model learned sequential word patterns and generated text based on different seed inputs. The training and validation results helped evaluate the model's performance.

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab
* GitHub
