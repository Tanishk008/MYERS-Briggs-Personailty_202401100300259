MBTI Personality Prediction Using NLP
This project uses Natural Language Processing (NLP) and Machine Learning to predict a person’s MBTI (Myers-Briggs Type Indicator) personality type based on the text they write.

Built as part of a college mini-project for the course “Intro to AI,” this tool demonstrates how AI can interpret and classify human personality based on language patterns.

Overview
MBTI stands for Myers-Briggs Type Indicator — a popular psychological framework with 16 personality types like INFP, ENTJ, ISTJ, etc.

This project takes text input (e.g., blog posts or messages) and predicts the corresponding MBTI type using:

✅ Natural Language Processing (text cleaning, TF-IDF vectorization)
✅ Machine Learning (Logistic Regression classifier)
✅ Real-time predictions for new input
✅ Visualization of class distribution and evaluation metrics

Project Workflow
Load dataset from CSV

Clean and preprocess text (remove noise, stopwords, etc.)

Encode MBTI types to numeric labels

Convert text to numerical features using TF-IDF

Train Logistic Regression classifier

Evaluate accuracy and precision using test data

Predict MBTI type for new user-written input

Visualize MBTI distribution
Dataset
The dataset contains two main columns:

type: MBTI personality type (e.g., INFJ, ENTP)

posts: Combined written text for each user

This dataset is pre-collected and cleaned, suitable for educational purposes.

Note: The dataset is slightly imbalanced, with more examples of certain types (like INFP and INTP).

Technologies Used
Python 3.x

pandas, numpy

nltk (Natural Language Toolkit)

scikit-learn (ML model & preprocessing)

seaborn, matplotlib (visualizations)

Google Colab (recommended environment)
Sample Output
🧩 Classification Accuracy: ~80% (varies)
📊 Sample Visualization:
![image](https://github.com/user-attachments/assets/28b750a1-0f41-4e79-af1b-5f9057e8f7e0)



📌 Results
Logistic Regression gave consistent accuracy across dominant classes.

Class imbalance slightly affected rare classes (like ESTJ, ESFJ).

High TF-IDF dimensionality helped improve accuracy.

Prediction is based on language tendencies and writing styl
