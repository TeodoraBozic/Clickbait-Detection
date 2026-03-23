# Clickbait Detection: Impact of Noise and Text Preprocessing Strategies

This project investigates the impact of text noise and preprocessing strategies on the performance of machine learning models for clickbait detection. The objective is to analyze how variations in text quality influence classification accuracy and to determine which preprocessing techniques contribute to more robust and reliable models.

---

## Problem Overview

Clickbait headlines are designed to attract attention and maximize user engagement, often using exaggerated or misleading language. Automatically detecting such content is a common Natural Language Processing (NLP) task with applications in content moderation, recommendation systems, and media analysis.

Real-world textual data is inherently noisy, which can negatively affect model performance. This project explores how different types of noise and preprocessing techniques influence the effectiveness of classification models.

---

## Dataset

The dataset consists of labeled headlines categorized into two classes:

* Clickbait (1)
* Non-clickbait (0)

The data is used for exploratory analysis, feature extraction, and training classification models.

---

## Methodology

The project follows a structured machine learning workflow:

### Data Analysis

* Inspection of dataset structure and statistics
* Analysis of class distribution
* Examination of headline length and text patterns

### Text Quality Analysis

* Vocabulary exploration
* Lexical diversity analysis (Type-Token Ratio)
* Word frequency visualization
* WordCloud generation

### Noise Analysis

* Identification of irregular patterns in text
* Analysis of punctuation, symbols, and formatting inconsistencies

### Text Preprocessing

Several preprocessing techniques are applied and compared:

* Lowercasing
* Removal of punctuation
* Text normalization
* Stemming
* Lemmatization

### Feature Engineering

* TF-IDF vectorization

### Model Training

The following models are trained and evaluated:

* Logistic Regression
* Linear Support Vector Machine (SVM)

### Model Evaluation

Performance is evaluated using:

* Accuracy
* Precision, Recall, and F1-score
* Confusion Matrix
* ROC Curve and AUC score

---

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* WordCloud
* Jupyter Notebook

---

## Project Structure

project/
├── proj2.ipynb
├── data/
└── README.md

---

## Key Findings

* Text noise has a measurable impact on classification performance
* Appropriate preprocessing improves model robustness
* Different preprocessing techniques lead to varying model outcomes
* Traditional models such as Logistic Regression and SVM perform effectively when combined with well-engineered features

---

## Usage

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook proj2.ipynb

---

## Author

Teodora Božić
Master’s Student in Artificial Intelligence and Machine Learning
Faculty of Electronic Engineering, Niš

---

## License

This project is intended for educational and research purposes.
