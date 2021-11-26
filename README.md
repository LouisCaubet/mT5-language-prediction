# Language prediction using mT5

Test task for a JetBrains internship as an ML Engineer, 2021. 

## Project description

I am fine-tuning Google's mT5 pretrained model using the XNLI dataset to perform language detection on a text. 

The model is capable of predicting the language of a text written in one of the 14 languages of the XNLI dataset.

## Code

The code is contained in a Juypter Notebook meant to be run on Google Colab using a TPU environment and a GCS bucket for data storage. 

Click here to open the notebook in Colab: 
https://colab.research.google.com/github/LouisCaubet/mT5-language-prediction/blob/main/mT5-language-prediction.ipynb

## Sources

* multilingual-t5 on GitHub: https://github.com/google-research/multilingual-t5
* t5 on GitHub: https://github.com/google-research/text-to-text-transfer-transformer
* XNLI dataset: https://www.tensorflow.org/datasets/catalog/xnli
* t5-trivia notebook: https://github.com/google-research/text-to-text-transfer-transformer/blob/main/notebooks/t5-trivia.ipynb

