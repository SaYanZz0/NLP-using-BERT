# Natural Language Processing for Disaster Tweets using BERT Model
![header](https://github.com/SaYanZz0/NLP-using-BERT/assets/88038655/d72b860c-fdd7-464d-be64-e9b1305a4c92)


Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programmatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster Submissions are evaluated using F1 between the predicted and expected answers.

## Overview

This repository contains:

- Implementation of a BERT-based model for tweet classification.
- Dataset used for training and evaluation.
- Evaluation metrics, including F1 score, used to assess the model's performance.

## Features

- **BERT Model**: Utilizes the Bidirectional Encoder Representations from Transformers (BERT) model, a state-of-the-art NLP model, for tweet classification.
- **Data Preprocessing**: Includes preprocessing techniques tailored for tweet data, such as tokenization, padding, and attention masks.
- **Model Training**: Provides scripts and notebooks for training the BERT model on the dataset.
- **Evaluation**: Evaluates the model's performance using F1 score, measuring the balance between precision and recall.
- **Inference**: Allows for making predictions on new tweet data using the trained model.

## Dataset

The dataset used in this project contains labeled tweets, where each tweet is annotated as either disaster-related or not. This dataset serves as the foundation for training and evaluating the BERT model.


## Acknowledgments

- The BERT model implementation is based on the Hugging Face Transformers library.
- Special thanks to the creators of the dataset used in this project.

## Contact

For any inquiries or questions regarding this project, feel free to contact me.

---

By leveraging the power of BERT and NLP techniques, this project aims to aid disaster relief efforts and enhance situational awareness during emergencies through automated tweet classification.
