# Deep Learning Lab Experiment 7

## Text Preprocessing and Word Embeddings Using Word2Vec

### Student Details

* **Name:** Johiya Sri S
* **Roll No:** 24BAD050
* **Course:** Deep Learning
* **Platform:** Google Colab

---

## Aim

To perform text preprocessing using NLTK and generate word embeddings using Gensim Word2Vec to analyze semantic relationships between words.

## Software Requirements

* Python
* NLTK
* Gensim
* NumPy
* Google Colab
* GitHub

## Objectives

* Understand text preprocessing techniques in Natural Language Processing.
* Load and explore the Brown Corpus using NLTK.
* Perform lowercase conversion, tokenization, stop-word removal, and lemmatization.
* Generate a vocabulary from preprocessed text.
* Analyze word frequencies using NLTK's FreqDist.
* Train a Word2Vec model using the Skip-gram architecture.
* Generate dense word embedding vectors.
* Identify similar words using the trained model.
* Calculate cosine similarity between selected word pairs.
* Analyze semantic relationships using word embeddings.

---

## Tasks Performed

### Task A – Dataset Preparation and Text Preprocessing

The Brown Corpus was loaded using NLTK, and the news category was selected for analysis.

The following preprocessing operations were performed:

* Loaded sample sentences from the Brown Corpus.
* Converted text into lowercase.
* Tokenized sentences into individual words.
* Removed punctuation and stop words.
* Applied lemmatization using WordNetLemmatizer.
* Displayed the original and preprocessed text.

### Task B – Vocabulary Generation and Word Frequency Analysis

A vocabulary was created from the preprocessed text, and word frequencies were analyzed.

The following operations were performed:

* Created a vocabulary of unique words.
* Calculated word frequencies using FreqDist.
* Identified the ten most frequently occurring words.
* Displayed the vocabulary size and total word occurrences.
* Prepared tokenized sentences for Word2Vec training.

### Task C – Word Embedding Generation Using Word2Vec

A Word2Vec model was trained using Gensim to learn word representations from the preprocessed sentences.

The following configurations were used:

* **Architecture:** Skip-gram
* **Embedding Dimension:** 100
* **Context Window Size:** 5
* **Minimum Word Frequency:** 2
* **Training Epochs:** 10

The embedding vectors of selected words were generated, their dimensions were displayed, and the five most similar words were identified using the trained model.

### Task D – Word Similarity Analysis and Experiment Management

Cosine similarity was calculated for selected word pairs to analyze their contextual relationships.

The following operations were performed:

* Selected meaningful word pairs from the trained vocabulary.
* Calculated cosine similarity scores using Word2Vec.
* Compared similarity scores between word pairs.
* Identified the pair with the highest similarity score.
* Analyzed the relationship between contextual similarity and word embeddings.
* Documented the experiment using GitHub.

---

## Dataset

**Dataset:** Brown Corpus – News Category

The Brown Corpus is a collection of English text samples used for Natural Language Processing research. In this experiment, the news category was selected to perform text preprocessing, word frequency analysis, and word embedding generation.

---

## Technologies Used

| **Technology**    | **Purpose**                         |
| ----------------- | ----------------------------------- |
| Python            | Programming                         |
| NLTK              | Text preprocessing and tokenization |
| Brown Corpus      | Text dataset                        |
| WordNetLemmatizer | Lemmatization                       |
| Gensim            | Word2Vec model training             |
| NumPy             | Numerical operations                |
| Google Colab      | Cloud-based code execution          |
| GitHub            | Version control and documentation   |

---

## Model Configuration

| **Parameter**      | **Value** |
| ------------------ | --------- |
| Model              | Word2Vec  |
| Architecture       | Skip-gram |
| Vector Size        | 100       |
| Context Window     | 5         |
| Minimum Word Count | 2         |
| Training Epochs    | 10        |
| Dataset Category   | News      |

---

## Key Observations

* Text preprocessing improves the consistency and quality of textual data.
* Stop-word removal reduces unnecessary words in the dataset.
* Lemmatization converts words into their base forms.
* Word frequency analysis identifies commonly occurring words.
* Word2Vec generates dense numerical vectors representing words.
* Skip-gram learns word representations by predicting surrounding context words.
* Words appearing in similar contexts tend to have more similar embeddings.
* Cosine similarity helps compare the contextual relationships between word pairs.
* The quality of word embeddings depends on the dataset, vocabulary, and model parameters.

---

## Conclusion

The experiment demonstrated text preprocessing using NLTK and word embedding generation using Gensim Word2Vec. The Brown Corpus was preprocessed using tokenization, stop-word removal, and lemmatization. Word frequency analysis was performed to identify common words, and a Skip-gram Word2Vec model was trained to generate 100-dimensional word embeddings. Cosine similarity was used to compare selected word pairs and analyze their contextual relationships. This experiment provided an understanding of how text preprocessing and word embeddings support Natural Language Processing tasks.
