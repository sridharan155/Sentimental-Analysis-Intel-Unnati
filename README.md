# Consumer Feedback Sentiment Analysis (Intel Unnati Project)

This project focuses on "Sentiment Classification" of User/Consumer comments collected from product review platforms. Built under the "Intel® Unnati program", the goal is to analyze natural language and classify sentiments as **Positive**, **Negative**, or **Neutral** to help businesses understand customer feedback.

🧠Problem Statement

In the digital world, customer reviews are abundant. Manually analyzing this data is time-consuming. This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automate the process of determining customer sentiment from text.

📌 Features

- Sentiment classification for real-world comments
- Preprocessing pipeline for noisy user-generated text
- Multiple ML models tested: Logistic Regression, SVM, Naive Bayes
- Supports both static dataset evaluation and live user input
- Visualization tools for insights and model performance


🗃️ Dataset Used

- **I3 & I5 Dataset**: Contains product-related user feedback/comments with sentiment labels.
- Each entry includes:
  - User comment/review
  - Associated product or service (optional)
  - Labeled sentiment (Positive/Negative/Neutral)

🔧 Technologies Used

- **Language:** Python  
- **Libraries:** pandas, numpy, sklearn, nltk, matplotlib, seaborn, wordcloud  
- **Notebook:** Jupyter  
- **Optional Visualization Tools:** Plotly, Streamlit
-

📊 Model Performance

| Model              | Accuracy  |
|-------------------|-----------|
| Logistic Regression | 84%      |
| Naive Bayes         | 81%      |
| SVM (Linear)        | 85%      |


