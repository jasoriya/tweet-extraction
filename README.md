# Udacity MLE Nanodegree Capstone Project - Tweet Extraction
Tweet Extraction Kaggle Challenge

This repository contains the following notebooks:
1. [Exploratory data analysis on Sentiment Analysis: Emotion in Text Dataset](https://github.com/jasoriya/tweet-extraction/blob/master/train_notebooks/tweet-extraction-eda.ipynb)
2. [Data pre-processing, Transformation, and Modeling](https://github.com/jasoriya/tweet-extraction/blob/master/train_notebooks/tweet-extraction_train.ipynb)
3. [Data inference](https://github.com/jasoriya/tweet-extraction/blob/master/inference_notebooks/tweet-extraction-inference.ipynb)


All the development of this project was done on the Kaggle cloud environment. The best way to reproduce these notebooks is to run them in a kaggle environment. The folllowing libraries were pre-installed in the kaggle environment:

|   Library    |   Version    |
|--------------|--------------|
| numpy        | 1.18.1       |
| pandas       | 1.0.3        |
| tensorflow   | 2.1.0        |
| tqdm         | 4.45.0       |
| sklearn      | 0.22.2.post1 |
| transformers | 2.9.0        |
| tokenizers   | 0.7.0        |


If you want to reproduce them in some other environment, you'll need the following files:
- RoBERTa pre-trained model config file and weights. RoBERTa tokenizer merges and vocab file. 
  - All four of these can be obtained using the `from_pretrained()` method of Huggingface [transformers](https://huggingface.co/transformers/index.html) library
  - Or just download them from [here](https://www.kaggle.com/cdeotte/tf-roberta)
- If you want to run the [inference notebook](https://github.com/jasoriya/tweet-extraction/blob/master/inference_notebooks/tweet-extraction-inference.ipynb) directly, you'll need the trained model weights. My trained weights can be downloaded from [here](www.kaggle.com/dataset/c4e853dc7af4d7ccfc6cd345cb9aafb546cdec90c33aea4bd96b20fd028abdd1).
