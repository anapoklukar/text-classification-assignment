# Text Classification: Assignment 2 for Intelligent Systems

This repository contains the implementation for the second seminar assignment in the **Intelligent Systems** course at the University of Ljubljana, Faculty of Computer and Information Science.

## Authors
- [anapoklukar](https://github.com/anapoklukar)
- [eddzu](https://github.com/eddzu)
- [smoncko](https://github.com/Smoncko)

## Date
January 2024

## Overview
Text classification is a complex task due to the inherent difficulties of language, such as words having multiple meanings and various grammatical forms (e.g., plurals, gender conjugations, verb tenses). Handcrafted algorithms struggle with these challenges, so in this assignment, we apply machine learning techniques to classify documents.

The models we explored include:
- **Linear Regression**
- **Random Forest Classifier**
- **Gradient Boosting**

Additionally, we compare these models' performance against **BERT**, a pretrained transformer model that has been trained on a much larger dataset.

### Evaluation Metrics:
- **Accuracy**
- **Recall**
- **Precision**
- **F1 Score** (primary focus)

## File Structure
- `assignment2.ipynb`: Jupyter Notebook containing the implementation of linear regression, random forest classifier, and gradient boosting models.
- `bert.ipynb`: Jupyter Notebook containing the BERT implementation and performance comparison.
- `news_category_dataset_is_course.json`: Input dataset used for text classification.


## Technologies Used
- Python
- Machine Learning Libraries (e.g., Scikit-learn)
- BERT (via Hugging Face Transformers)
- Data Processing Libraries (e.g., Pandas, NumPy)
