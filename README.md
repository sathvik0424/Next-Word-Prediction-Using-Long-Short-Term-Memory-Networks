# Next Word Prediction Using LSTM

This project demonstrates how to build a **Next-Word Prediction** model using **LSTM (Long Short-Term Memory)** networks in Keras. The model takes a sequence of words as input and predicts the most likely next word.

---

## Problem Statement

The goal of this project is to predict the next word in a sequence of words. Given a prompt or a series of words, the model will predict the next word based on the training data it has learned from. This is a common task in **Natural Language Processing (NLP)** and forms the basis for applications like text completion, chatbots, and even predictive typing.

---

## 💡Proposed System

- **Text Preprocessing**: The input text is tokenized and converted into sequences of words.
- **Embedding Layer**: Words are mapped to dense vectors to capture semantic relationships.
- **LSTM Model**: A Long Short-Term Memory (LSTM) network is used to capture the temporal dependencies in the text.
- **Output Layer**: A Dense layer with a softmax activation is used to predict the next word.

---

## 🛠 Technologies Used

- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📊 Output

- The model achieves **approximately 77% accuracy** after 100 epochs.
- Example of next-word prediction:
  - **Input**: `"Hey"`
  - **Predicted Word**: `"world"`

Here is a sample output prediction of the model:
  
```bash
Input: 'Hey' → Predicted next word: 'world'
