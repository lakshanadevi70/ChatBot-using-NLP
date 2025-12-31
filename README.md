# 🤖 NLP Chatbot — Python AI Assistant
A simple conversational chatbot built using Natural Language Processing (NLP) and a neural network model trained to recognize intent and reply with appropriate responses. It reads patterns and responses from a JSON file and communicates with the user in a console interface.

## 📌 Project Overview
- This chatbot takes user input, processes it using NLP techniques (tokenization and  lemmatization), and predicts the intent using a trained TensorFlow / Keras neural network model.
- Based on the predicted intent, the chatbot selects an appropriate response from a JSON file and displays it in real time.

## 🛠 Tools & Technologies
  - Python
  - NLTK (Natural Language Toolkit)
  - TensorFlow / Keras
  - NumPy
  - JSON file for intents

## 📈 Key Concepts
  - Tokenization: Breaking text into words
  - Lemmatization: Reducing words to base form
  - Bag of Words: Representing text for model input
  - Neural Network: Classifier trained on intent patterns
  - Prediction: Choosing responses based on model output

## 📂 Files
   - project
      - ├── chatbot.py            # Main Python script (your code)
      - ├── Data.json             # Chat intents with patterns & responses
   
## 🚀 How to Run
1.Install required packages:
   - pip install nltk tensorflow numpy
2.Download NLTK data (already included in the script):
   - nltk.download("punkt")
   - nltk.download("wordnet")
3.Place your Data.json file in the same directory.
4.Run the chatbot script:
  - python chatbot.py
5.Type any message and the bot will reply!

## 🧠 Example Interaction
- User: Hello
- Chatbot: Hi there, how can I help?

- User: Tell me a joke
- Chatbot: Haha, you’re funny 😄

## 🎯 Learning Outcomes
  - Understanding NLP preprocessing steps
  - Converting text into machine-understandable format
  - Building and training a simple neural network
  - Creating real-time text-based interaction with Python

## 💡 Notes
  - This chatbot uses a simple neural network (Dense layers with Dropout)
  - You can improve accuracy by adding more patterns to Data.json
  - You can also extend it with external datasets or advanced NLP models
