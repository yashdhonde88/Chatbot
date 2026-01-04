# Chatbot

An intelligent conversational AI built using Deep Learning and Natural Language Processing (NLP) in Python. This project demonstrates how to build a chatbot from scratch, including data preprocessing, model training, and response generation.

![Chatbot Output](https://github.com/yashdhonde88/Chatbot/blob/main/Chat%20Bot.png)

## 📝 Description
This Chatbot is designed to understand and reply to user queries by matching them to known patterns (intents). It uses a Feed Forward Neural Network trained on a dataset of intents to classify user messages and retrieve the most appropriate response. It is an excellent example of applying NLP techniques and Keras for text classification.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * TensorFlow / Keras (for Deep Learning)
    * NLTK (Natural Language Toolkit for NLP)
    * NumPy (for numerical operations)
    * Pickle (for serializing the model)

## ✨ Features
* **Text Preprocessing:** Tokenization and Lemmatization of user input.
* **Intent Classification:** Uses a trained Neural Network to predict the intent of the message.
* **Dynamic Responses:** Selects random responses from the matched intent category for variety.
* **Confidence Threshold:** Filters out responses if the prediction confidence is too low.

## 🚀 Highlights
* **Customizable:** You can easily add new intents, patterns, and responses by editing the `intents.json` file (or equivalent data source).
* **Lightweight:** Efficient model structure suitable for quick deployment.
* **Educational:** Provides a clear implementation of the NLP pipeline: `Input -> Preprocessing -> Model -> Classification -> Response`.
