# AI Customer Support Chatbot (NLP)

## Project Overview
This project is a simple AI chatbot that answers customer queries using Natural Language Processing and Machine Learning.

The chatbot predicts the intent of user queries and returns an appropriate response.

## Technologies Used
- Python
- NLP
- Scikit-learn
- Google Colab

## How It Works
1. User enters a question.
2. Text is converted into numerical vectors using CountVectorizer.
3. Logistic Regression model predicts the intent.
4. The chatbot returns a predefined response based on the predicted intent.

## Example Queries
- Hello
- Reset password
- What are working hours?

## Files in this Repository
- `ai_chatbot.ipynb` → Notebook containing chatbot implementation
- `model.pkl` → Trained machine learning model
- `vectorizer.pkl` → Text vectorization model used to convert user input into features
