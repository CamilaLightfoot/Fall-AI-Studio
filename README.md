# Planned Parenthood AI Studio Project  
### Confidential Portfolio Version

## Overview

This project was completed through the **Break Through Tech AI Studio Program** in collaboration with **Planned Parenthood Federation of America (PPFA)**.

Our team worked on improving **Roo**, PPFA’s sexual and reproductive health chatbot, by developing a machine learning workflow to better understand chatbot conversations and identify cases that may require escalation to a human educator.

> **Confidentiality Notice:**  
> Due to confidentiality and data privacy agreements, this public version does not include the original dataset, trained models, credentials, internal files, or specific confidential outputs.  
> This repository is intended as a portfolio overview that explains the project scope, workflow, tools, and learning outcomes without exposing sensitive information.

---

## Project Goal

The main goal of this project was to explore how machine learning could support chatbot improvement by analyzing conversation patterns and helping identify when automated responses may not be enough.

Because the chatbot handles sensitive health-related questions, our work focused on responsible model development, careful data handling, and evaluating prediction quality in a way that could support safer and more reliable user experiences.

---

## My Contributions

As part of Team PPFA 1D, I contributed to:

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Dataset augmentation
- Analysis of class imbalance and label distributions
- Decision Tree model training and evaluation
- Collaboration on model comparison and result interpretation
- Responsible AI discussions related to healthcare chatbot data

---

## Technical Workflow

The project followed an end-to-end machine learning workflow:

### 1. Data Exploration

We analyzed the structure, quality, and distribution of chatbot conversation data. This included reviewing missing values, identifying redundant columns, and understanding how different labels were represented in the dataset.

### 2. Data Cleaning and Preprocessing

The preprocessing pipeline included:

- Lowercasing text
- Removing unnecessary characters
- Cleaning inconsistent formatting
- Handling missing or redundant values
- Tokenization
- Lemmatization
- Preparing text for model input

### 3. Data Augmentation

One major challenge was class imbalance. Some conversation categories had fewer examples than others, which could affect model performance.

To address this, we explored data augmentation techniques to increase representation for underrepresented categories while preserving the meaning of the original conversations.

### 4. Feature Engineering

We converted cleaned text into numerical representations using techniques such as:

- TF-IDF vectorization
- Text embeddings / semantic representations

These features helped machine learning models identify important patterns in chatbot conversations.

### 5. Model Development

We experimented with multiple supervised machine learning models, including:

- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting

The models were compared based on their ability to classify chatbot interactions and support escalation-related decision making.

### 6. Model Evaluation

We evaluated model performance using:

- Accuracy
- Precision
- Recall
- Weighted F1 Score
- Confusion Matrix analysis

Because the dataset involved imbalanced classes, we paid special attention to metrics beyond accuracy.

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- TF-IDF
- Sentence-BERT / text embeddings
- Matplotlib
- Git and GitHub

---

## Responsible AI Considerations

Because this project involved healthcare-related conversational data, responsible AI was an important part of the process.

Key considerations included:

- Protecting sensitive data
- Avoiding exposure of private or confidential information
- Evaluating potential bias caused by class imbalance
- Considering the impact of false positives and false negatives
- Supporting human review for sensitive or complex cases

---

## Business and Social Impact

This project demonstrated how machine learning can support real-world chatbot improvement by:

- Helping identify conversations that may need human educator support
- Improving the reliability of automated responses
- Supporting better resource allocation
- Reducing the risk of incomplete or inappropriate chatbot guidance
- Contributing to safer digital health support experiences

---

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Text data analysis
- Exploratory Data Analysis
- Data augmentation
- Classification modeling
- Model evaluation
- Responsible AI
- Team collaboration
- Technical communication

---

## Note

This repository is a public portfolio version of the project. Sensitive files, confidential data, internal results, credentials, and proprietary materials have intentionally been removed.

## Resources
- **GitHub Repository:** [Fall-AI-Studio](https://github.com/CamilaLightfoot/AI-Health-Chatbot-Optimization)  
