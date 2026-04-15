# ResumeRise
This project focuses on building an intelligent system that automatically classifies resumes into predefined job categories using Machine Learning and Natural Language Processing (NLP) techniques.

The goal is to reduce manual effort in resume screening and help recruiters quickly identify suitable candidates based on their skill sets and experience.
## Dataset
The [dataset](https://www.kaggle.com/iammhaseeb/resumes-dataset-with-labels) consists of 1000 labelled resumes (labelled according to the primary category/class that a particular resume belongs to) in a csv format. We will be using this csv formatted resume dataset to train our model for classification. Our model should then be able to work on any unseen resume.

Problem Statement

Recruiters often deal with thousands of resumes, making manual screening time-consuming and inefficient.

This project addresses:
1.How can we automatically categorize resumes based on their content?
2. Can machine learning models accurately identify job domains from resume text?
Dataset

The dataset consists of resumes labeled into different job categories such as:

 Software Development
 Data Science / Analytics
 Cloud / DevOps
 Business / Management

Each record contains:

Resume text
Category label

Project Workflow
 1. Data Preprocessing
Text cleaning (removal of stopwords, punctuation)
Tokenization and normalization
Handling noisy/unstructured resume data
 2. Feature Engineering
TF-IDF vectorization to convert text into numerical format
Extraction of relevant keywords and patterns
 3. Model Building

Applied classification algorithms such as:

Logistic Regression
Naive Bayes
(Add others if used)

These models learn patterns in resume text to classify them into appropriate domains.

Model Evaluation

The model performance is evaluated using:

Accuracy Score
Precision, Recall, F1-score
Confusion Matrix

Key Insights
NLP techniques effectively capture resume semantics
TF-IDF plays a crucial role in feature representation
Classification models can significantly automate resume screening
Data preprocessing greatly impacts model accuracy

Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, NLTK
Visualization: Matplotlib, Seaborn
Environment: Jupyter Notebook

