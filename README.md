# Sentiment Analysis Project

This project is based on the fine-tuning of BERT for sentiment analysis.

## Original Source for the code.

The original code is taken from [this Google Colab tutorial](https://colab.research.google.com/github/DerwenAI/spaCy_tuTorial/blob/master/BERT_Fine_Tuning.ipynb#scrollTo=8o-VEBobKwHk).

## Modified or created Function

- PerSentParagraphDataset
- plot_confusion_matrix
- fine_tune
- predict_paragraph_sentiments
- predict_document_sentiment
- evaluate_document

## Trained Models and Data

The training and test data are available from [PerSenT](https://stonybrooknlp.github.io/PerSenT/).

## Environment
Google Colab

## Major Software & Hardware Requirements
- CUDA
- Minimum 15GB GPU RAM
- Minimum 5GB System RAM 
- Minimum 25GB Disk
- Python 3.10
- torch 2.0.0+cu118
- transformers 4.10.0 or later
- pandas 1.5.3
- numpy 1.22.4

# Analysis
## Confusion Matrix
<img width="569" alt="Screenshot 2023-05-08 at 9 07 16 PM" src="https://user-images.githubusercontent.com/67400401/236968538-d605aa51-ff26-4735-b52f-530064cbb9ee.png">

## Report (Paragraph Sentiment) -Validation Set


