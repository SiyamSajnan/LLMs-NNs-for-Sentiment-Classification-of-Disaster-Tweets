# Breaking News or Noise? Unveiling the Power of BERT, RoBERTa, DistilBERT, and Other Deep Learning Models for Disaster Tweet Classification

## Project Description
This project explores various transformer-based and deep learning models to classify sentiments from tweets related to disasters. By categorizing tweets into disaster-related and non-disaster-related, the study aims to filter critical information for use by governmental and humanitarian agencies in real-time disaster response. The project compares the performance of models like BERT, RoBERTa, and DistilBERT with conventional deep learning models on this classification task.


## Models Employed
- **BERT (Bidirectional Encoder Representations from Transformers)**
- **RoBERTa (A Robustly Optimized BERT)** 
- **DistilBERT (A Smaller, Faster, and Lightweight BERT)**
- **LSTM (Long Short-Term Memory Networks)**
- **CNN (Convolutional Neural Networks)**
- **RNN (Recurrent Neural Networks)**

## Features
- **Data Preprocessing**: Tweets were preprocessed through tokenization, normalization, and removal of irrelevant content.
- **Transformer Models**: Fine-tuning of transformer models such as BERT, RoBERTa, and DistilBERT to capture contextual nuances in tweets.
- **Model Evaluation**: Utilized metrics like F1-score, precision, recall, and accuracy to assess model performance, highlighting the advantages of transformer-based architectures over traditional deep learning models.
- **Comparison with Baselines**: The project included comparisons with deep learning models such as LSTM and CNN to illustrate the performance gain provided by transformers in handling text classification.

## Usage
To reproduce results, run the notebook containing the models and use the dataset of disaster tweets for training and evaluation. Follow the preprocessing steps and model training routines outlined in the documentation.

## Detailed Results
The project achieved the following performance metrics:
- **BERT**: F1-score of 0.84, outperforming other models on disaster tweet classification.
- **RoBERTa**: Achieved an F1-score of 0.83.
- **DistilBERT**: Slightly lower but effective, with an F1-score of 0.82.
- **Deep Learning Baselines (LSTM, CNN)**: Lower F1-scores, ranging from 0.42 to 0.69, highlighting the superior performance of transformer-based models over the conventional NN models.

## Includes
An IEEE format report on this topic.

## Contributing
Contributions are encouraged! Please fork this repository and submit pull requests with any enhancements or improvements.

