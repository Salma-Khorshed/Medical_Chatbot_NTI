💬 Mental Health FAQ Chatbot

An intelligent FAQ chatbot fine-tuned on a custom Mental Health dataset using T5 (Text-to-Text Transfer Transformer).
This project allows users to ask mental health–related questions and get meaningful responses. It includes data preprocessing, model training, evaluation, visualization, and deployment using Streamlit + ngrok.

🚀 Features

📊 Exploratory Data Analysis (EDA) with Seaborn, Matplotlib, and WordCloud

🤖 Fine-tuned T5 model for Mental Health FAQs

🔍 Text preprocessing & tokenization using Hugging Face Transformers

🎯 Training & evaluation pipeline with Hugging Face Trainer

💬 Chat function for real-time interaction with the trained model

🌐 Streamlit Web App with ngrok deployment for easy sharing

📦 Exported fine-tuned model for reuse

🛠️ Tech Stack

Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

NLP & ML: Hugging Face Transformers, T5, Trainer API

Visualization: WordCloud, Heatmaps, Histograms

Deployment: Streamlit, pyngrok

📂 Project Structure
├── Mental_Health_FAQ.csv        # Dataset
├── chatbot_app.py               # Streamlit chatbot app
├── faq11-t5-base/               # Fine-tuned T5 model & tokenizer
├── logs/                        # Training logs
├── README.md                    # Project documentation
└── requirements.txt             # Dependencies

📊 Dataset

The dataset contains Questions and Answers about Mental Health.
Before training:

Dropped unnecessary columns (Question_ID)

Checked for null values & duplicates

Added derived features (question_length, answer_length)

⚡ Training Pipeline

Import & preprocess dataset (Mental_Health_FAQ.csv)

Convert into Hugging Face Dataset

Load pretrained T5 model & tokenizer

Preprocess text into tokenized inputs

Fine-tune using Hugging Face Trainer

Save trained model (faq11-t5-base/)

📈 Visualizations

Length Distribution of Questions & Answers

WordClouds for Questions & Answers

Correlation Heatmap of features
