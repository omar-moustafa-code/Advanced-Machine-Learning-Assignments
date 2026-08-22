# Advanced Machine Learning Assignments

The full collection of assignments completed for the CSCE 4604 course: **Advanced Machine Learning**. The assignments cover a progression of machine learning and deep learning techniques, ranging from regression and classification to convolutional neural networks, recurrent neural networks, transformers, as well as reinforcement learning.

## Course Topics

| Assignment   | Topic                                | Main Techniques                                                                  |
| ------------ | ------------------------------------ | -------------------------------------------------------------------------------- |
| Assignment 1 | Regression                           | Linear Regression, Logistic Regression, Regularization, Early Stopping           |
| Assignment 2 | Multiclass Classification            | Fully Connected Neural Networks, CNNs, MNIST, Model Interpretability             |
| Assignment 3 | CNN Use Cases                        | Custom CNNs, Transfer Learning, Pretrained CNNs, Layer Freezing                  |
| Assignment 4 | Text Generation                      | RNNs, LSTM, GRU, Bidirectional RNNs, Shakespeare Text Generation                 |
| Assignment 5 | Transformer-Based Sentiment Analysis | Tokenization, Multi-Head Attention, Transformer Encoder, IMDB Sentiment Analysis |
| Assignment 6 | Reinforcement Learning               | CartPole, Agents, Rewards, Deep Reinforcement Learning                           |

---

## 🧠 Assignments

### Assignment 1 — Regression

The first assignment explores both **linear regression** and **logistic regression**.

#### Part 1 — Linear Regression

* House price prediction
* Data preprocessing and feature engineering
* Handling skewed features
* Model training and validation
* Identifying and addressing overfitting
* Regularization and Early Stopping
* Evaluation of regression performance

#### Part 2 — Logistic Regression

* Binary classification
* Heart disease prediction
* Feature preprocessing
* Logistic regression modeling
* Classification evaluation

**Files:**

* `Omar_Assignment1_part1.ipynb`
* `Omar_Assignment1_part2.ipynb`
* `Report.pdf`

---

### Assignment 2 — Multiclass Classification

This assignment focuses on classifying handwritten digits from the **MNIST dataset**.

Two neural network approaches are explored:

1. A fully connected neural network
2. A convolutional neural network followed by fully connected layers

The assignment also investigates the effects of different experimental configurations on model performance and includes **machine learning interpretability analysis**.

**Files:**

* `Omar_Assignment2.ipynb`
* `Report.pdf`

**Dataset:** MNIST

---

### Assignment 3 — Convolutional Neural Network Use Cases

This assignment explores different approaches to image classification using **Convolutional Neural Networks**.

The work includes:

* Building a custom CNN
* Using pretrained CNN architectures
* Transfer learning
* Freezing pretrained layers
* Comparing different CNN configurations
* Evaluating the effect of architectural and training modifications on accuracy

The classification task focuses on determining whether a person is **happy or not happy** from facial images.

**Files:**

* `Omar_Assignment3.ipynb`
* `Report.pdf`

---

### Assignment 4 — Text Generation with RNNs

This assignment explores **character-level text generation** using recurrent neural networks.

A Shakespeare text corpus is used to train different recurrent architectures, including:

* Deep RNNs
* LSTM networks
* GRU networks
* Bidirectional recurrent networks

The models learn sequential patterns from Shakespeare's works and are used to generate new text.

**Files:**

* `Omar_Assignment4.ipynb`
* `shakespeare.txt`

**Dataset:** Shakespeare text corpus

---

### Assignment 5 — Transformer-Based Sentiment Analysis

This assignment focuses on building a **Transformer-based sentiment analysis model from scratch**.

The classifier consists of three major components:

1. **Tokenizer** — using a pretrained BERT tokenizer
2. **Transformer Encoder** — implemented from scratch
3. **Classification Head** — used to predict sentiment

The model is trained for binary sentiment classification using the **IMDB movie review dataset**.

Key concepts explored include:

* Tokenization
* Embeddings
* Multi-head self-attention
* Feed-forward networks
* Transformer encoder architecture
* Sentiment classification

**Files:**

* `Omar_Assignment5.ipynb`

**Dataset:** IMDB Movie Reviews

> **Note:** This assignment requires a GPU runtime for practical training times.

---

### Assignment 6 — Reinforcement Learning

The final assignment introduces **Reinforcement Learning** through the CartPole environment.

The project explores the interaction between an agent and its environment through:

* States and observations
* Actions
* Rewards
* Agent memory
* Learning algorithms
* Policy improvement
* CartPole control

The goal is to train an agent capable of keeping the pole balanced by learning from interactions with the environment.

**Files:**

* `Omar_Assignment6.ipynb`
* `CartPole-v1.mp4`

---

## Technologies & Libraries

The assignments make use of a range of Python-based machine learning and deep learning tools, including:

* **Python**
* **Google Colab**
* **TensorFlow / Keras**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* **OpenAI Gym / Gym environments**
* **BERT tokenization**
* **Transformer architectures**

---

## Learning Progression

The assignments demonstrate a progression through several major areas of modern machine learning:

```text
Regression
    ↓
Neural Network Classification
    ↓
Convolutional Neural Networks
    ↓
Recurrent Neural Networks
    ↓
Transformers
    ↓
Reinforcement Learning
```

Together, they provide hands-on experience with both **supervised and reinforcement learning**, covering traditional machine learning techniques as well as modern deep learning architectures.

---

## Notes

These assignments were completed as part of the **Advanced Machine Learning** course at **The American University in Cairo (AUC)**.

The repository is intended as an academic record and portfolio of the implementations, experiments, and analyses completed throughout the course.

Some assignments are based on course-provided labs and tutorials. Original sources and references are retained within the corresponding notebooks where applicable.

---

## 👤 Author

**Omar Moustafa**

The American University in Cairo (AUC)
