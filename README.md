# Implementation-of-chatbot-using-nlp
## Overview
This project implements a chatbot that uses Natural Language Processing (NLP) techniques to understand and respond to user inputs. The chatbot is designed to interpret user intents and provide responses based on predefined patterns and responses. The core technologies and components involved in this project are:

*NLP with nltk: The chatbot utilizes the nltk library to process natural language inputs, including tokenization, lemmatization, and intent recognition.
*Machine Learning with scikit-learn: The project incorporates machine learning algorithms for intent classification. The model is trained on a dataset of user inputs to improve the chatbot's ability to understand various queries and respond accurately.
*Interactive Interface with streamlit: The chatbot features an interactive web interface built using streamlit, enabling users to communicate with the bot in real-time.

---

## Features
- Understands various user intents such as greetings, farewells, gratitude, and more.
- Provides relevant responses based on user input.
- Maintains a conversation history that can be viewed by the user.
- Built using Python and leverages popular libraries for NLP and machine learning.

---

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

---

## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
We can see the conversation history at the left side of the interface.It shows how we interact to the chatbot and what are the conversation was done between us and the chatbot.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.
