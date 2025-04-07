# Applying PhoBERT in Customer Sentiment Analysis on Tiki Book Reviews
### Overview
This project is the final assignment for the Deep Learning in Business Analytics course at the University of Economics and Law, Faculty of Information Systems. It focuses on leveraging the PhoBERT model—a Vietnamese-optimized version of BERT—to analyze customer sentiments from book reviews on the Tiki e-commerce platform. The goal is to provide actionable insights for Tiki to enhance customer satisfaction and optimize business strategies, while also developing an intuitive user interface (UI) for real-time sentiment analysis.

### Submission Date: August 10, 2024

Lecturer: MSc. Nguyen Quang Phuc

Group: 5

Group Members
No	Member	ID	Contribution
1	Hoang Thi Nhat Quyen	K214162151	20%
2	Tran Thi Y Nhu	K214162149	20%
3	Ly Vu Thien An	K214161372	20%
4	Le Thi Bich Van	K214162159	20%
5	Le Tuan Nguyen	K214160993	20%

#### Objectives
Sentiment Analysis Model: Train a deep learning model using PhoBERT to classify customer sentiments (positive, neutral, negative) from Tiki book reviews.
Interactive UI: Develop a user-friendly interface for users to input reviews and receive instant sentiment analysis results.
Project Scope
Dataset: Customer reviews of books from the Tiki platform, sourced from the Tiki Books Dataset on Kaggle.
Focus: Sentiment analysis of Vietnamese text data using NLP and deep learning techniques.
#### Methodology
1. Data Collection
Source: Tiki Books Dataset
Content: 2,024 bestselling books and associated customer reviews.
2. Data Preprocessing
Cleaned text data by removing duplicates, handling missing values, and normalizing Vietnamese text (e.g., standardizing vowels, encoding punctuation).
Converted slang/abbreviations (e.g., "ok" → "okay") and applied TF-IDF for feature extraction.
3. Model Training
Utilized PhoBERT combined with TF-IDF features for sentiment classification.
Training process: Tokenization, model optimization with AdamW, and evaluation with CrossEntropyLoss.
Achieved accuracy ranging from 51% to 64% across epochs.
4. UI Development
Built using Qt Designer and PyQt6.
Features: Book search, detailed book info, review submission, and real-time sentiment prediction.

├── data/                   # Dataset files (Tiki Books Dataset)
├── src/                    # Source code
│   ├── preprocessing.py    # Data cleaning and preprocessing scripts
│   ├── model.py            # PhoBERT model training and evaluation
│   └── ui/                 # UI implementation (PyQt6)
├── README.md               # Project overview (this file)
└── docs/                   # Full report and documentation

#### Key Features
Sentiment Classification: Analyzes reviews as positive, neutral, or negative using PhoBERT.
Home Page: Browse books with titles, prices, and images.
Review Page: View book details and submit reviews.
Real-Time Analysis: Displays sentiment results instantly via a message box.
### Results
Model Performance: Improved accuracy from 51% to 64% during training, demonstrating effective learning of sentiment patterns.
UI Usability: Provides an intuitive experience for users to explore books and submit feedback.
### Limitations
Dataset Size: Limited to 2,024 books, potentially missing broader sentiment nuances.
Bias: Reviews may not fully represent all Tiki customers.
Complex Semantics: PhoBERT struggles with extreme emotions or highly contextual reviews.
Future Directions
Model Enhancement: Fine-tune PhoBERT or integrate with other models for better accuracy.
Expanded Scope: Apply sentiment analysis to other product categories on Tiki.
Multilingual Support: Extend to additional languages using similar techniques.

[full project](https://drive.google.com/drive/u/0/folders/13kUsGijjZd5iE5k8d0lA6PJQ0p5-W9ij)
