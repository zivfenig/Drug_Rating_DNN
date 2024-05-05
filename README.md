# Drug Rating Classification Using BERT and BioBERT

This project focuses on classifying drug reviews into multiple classes using advanced NLP models, specifically BERT and BioBERT. The goal is to accurately predict the sentiment expressed in drug reviews, initially categorizing them into 10 classes and later into 3 classes for improved specificity.

## Table of Contents
- [Installation](#installation)
- [Data](#data)
- [Models](#models)
- [Training](#training)
- [Results](#results)
- [References](#references)


## Installation

To set up your environment to run this code, you will need Python 3.x and the following packages:
- PyTorch
- Transformers
- NumPy
- Pandas

Install the necessary packages using pip:

```bash
pip install torch transformers numpy pandas
```
## Data
The dataset used in this project is from the UCI Machine Learning Repository, specifically the Drug Review Dataset (Drugs.com). It contains detailed drug reviews along with associated ratings, which are used as labels for classification.

## Models
Two main models are used:

BERT - For the initial 10-class classification.
BioBERT - For the subsequent 3-class classification, enhancing the model's ability to understand biomedical context.

## Training
The notebooks contain code for training the models, including preprocessing steps like tokenization and setting up dataloaders. The models are trained using the AdamW optimizer with a linear schedule for learning rate adjustment.

## Results
The models show promising results in both setups:

- The 10-class model showed gradual improvement across epochs but indicated potential overfitting.
- The 3-class BioBERT model demonstrated high accuracy and F1 scores, suggesting effective training and generalization capabilities.

## References
A comprehensive list of references is included in the project, ranging from academic papers to online resources that provide additional context and technical insights.



