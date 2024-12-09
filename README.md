# Spam Mail Classification System

## Overview

This project aims to develop an efficient and accurate system for classifying emails into **"spam"** or **"ham"** (non-spam) categories using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The system leverages the power of machine learning models to process incoming emails in real-time and classify them with high accuracy. It utilizes techniques such as **CountVectorizer**, model training, and a user-friendly web interface created with **Streamlit** for seamless interaction.

## Features

- **Automated Email Classification**: Automatically classifies incoming emails as either spam or non-spam based on content and metadata.
- **Real-time Spam Detection**: Processes and classifies emails instantly, enabling immediate categorization.
- **High Accuracy**: The model achieves a classification accuracy of **98.48%**, ensuring precise email categorization.
- **Scalability**: Designed to handle large volumes of emails effectively.
- **User-Friendly Interface**: Built using **Streamlit**, providing an easy-to-use platform for users to input emails and classify them.
- **Adaptability**: The system can be continuously retrained with new data to handle evolving spam techniques.

## Requirements

Before running the project, make sure to install the following dependencies:

- Python 3.x
- Streamlit
- Scikit-learn
- Pandas
- Numpy
- Pickle

You can install the required libraries using `pip`:

```bash
pip install streamlit scikit-learn pandas numpy pickle-mixin

```
pip install streamlit scikit-learn pandas numpy pickle-mixin

# How It Works

1. **Preprocessing**: The raw email text data is cleaned, tokenized, and vectorized using **CountVectorizer** to convert it into a numerical format suitable for machine learning.
2. **Model Training**: The dataset is split into **training** and **test** sets, and the model is trained on the training data to learn the patterns in emails classified as spam or non-spam.
3. **Prediction**: When an email is input into the web interface, it is transformed into numerical features using the same vectorizer, and the trained model predicts whether the email is spam or not.
4. **Real-time Interface**: The **Streamlit** interface allows users to input emails and instantly see the classification result (Spam or Not Spam).

# Example Usage

After running the **Streamlit** app:

1. Input an email into the provided text box.
2. Click **"Classify"**.
3. The system will classify the email as either **"Spam"** or **"Not Spam"** based on the trained machine learning model.

# Output

To run the application and interact with the system via a web interface, follow these steps:

1. Open your terminal or command prompt.
2. Navigate to the project directory where the `spamdetector.py` file is located.
3. Execute the following command to start the **Streamlit** web app:

   ```bash
   streamlit run "c:\Users\Megha\OneDrive\Desktop\spam mail class\spamdetector.py"

