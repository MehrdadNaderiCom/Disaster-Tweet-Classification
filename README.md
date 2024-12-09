# Disaster Tweet Classification

This project aims to classify disaster-related tweets using NLP techniques and a Bidirectional LSTM model. The solution involves exploratory data analysis, text preprocessing, feature extraction with TF-IDF, and deep learning model training.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Model Performance](#model-performance)
- [Future Improvements](#future-improvements)
- [Acknowledgments](#acknowledgments)

## Overview
Disaster tweet classification is critical for identifying real-time disaster events and aiding disaster response teams. This project processes a Kaggle-provided dataset and uses a Bidirectional LSTM model to achieve a validation accuracy of **79.3%**.

## Project Structure
The repository contains the following files and directories:

- **`data/`**
  - `submission.csv`: Submission file for Kaggle.

- **`notebooks/`**
  - `nlp_disaster_project.ipynb`: Main Jupyter Notebook with all project steps.

- **`images/`**
  - `leaderboard_screenshot.png`: Screenshot of the Kaggle leaderboard showing the model's position.

- **`README.md`**
  - Overview and details of the project.


## Getting Started

1. Clone the repository:
   git clone https://github.com/MehrdadNaderiCom/Disaster-Tweet-Classification.git
   cd Disaster-Tweet-Classification
2. Open the notebook:
  jupyter notebook notebooks/nlp_disaster_project.ipynb


---

### **Markdown 6: Model Performance**
## Model Performance
- **Validation Accuracy**: 79.3%
- **Precision**: 0.81
- **Recall**: 0.80
- **F1 Score**: 0.80

## Future Improvements
- Implement pretrained embeddings like GloVe or Word2Vec.
- Use advanced data augmentation techniques to enhance robustness.
- Experiment with ensemble models for improved accuracy.

## Acknowledgments
- Kaggle for providing the dataset: [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)
