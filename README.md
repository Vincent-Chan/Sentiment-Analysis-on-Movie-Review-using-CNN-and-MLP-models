# Sentiment Analysis on Movie Review using CNN and MLP models

This is my group project assignment 1 of COMP4332 Big Data Mining and Management in HKUST.

This project invloves using the CNN and MLP models to predict the movie review ratings based on viewer's comments.

You should see the following things in this repository:

* COMP4332_Project_1.ipynb: the Jupyter Notebook
* COMP4332_Project_1_Report.pdf: the report for this project
* COMP4332 Project 1 and 2 presentation (Group 4).pdf: the presentation slide of this project
* cnn_model.h5: the weights of the CNN model
* pred.csv: the submitted movie rating prediction on the testing dataset
* Project 1 Sentiment Analysis.pdf: the description of this project
* evaluate.py: the Python file for evaluating the validation prediction on the validation dataset
* data: the folder that contains the training dataset, the validation dataset and the testing dataset
* submission: the submission for this project

---

## How to run?

1. Upload the jupyter notebook and the data folder to the same directory on Google Drive
2. Open Google Colab and change the location path of the data files if necessary
3. Run all the code at once

---

## Baseline Performance

The baselines we use are 

1) Glove Embedding (glove.6B.100d.text from glove.6B.zip on the official website: https://nlp.stanford.edu/projects/glove) + CNN, and 

2) Term Frequency (TF) + Logistic Regression. 

You can try other models, like TF-IDF, RNN, etc.

|               Baseline               | Validation Performance |
|:------------------------------------:|:----------------------:|
|         Glove Embedding + CNN        |         45.10%         |
| Term Frequency + Logistic Regression |         48.30%         |

---

### Group members:

* CHAN, Chun Hin (me)
* CHAN, Long Ki
* LEE, Seungho
* WAN, Nga Chi