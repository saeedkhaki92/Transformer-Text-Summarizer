# Transformer-Text-Summarizer
This project implement the transformer decoder to summarize text. 
Summarization is an important task in natural language processing and could be useful for a consumer enterprise. For example, it can be used to scrape articles, summarize them, and then you can use sentiment analysis to identify the sentiments.

![Alt Text](https://github.com/saeedkhaki92/Transformer-Text-Summarizer/blob/main/transformerNews.png)


## Getting Started

### Dependencies

Following packages should be installed on python 3:

- Trax
- numpy
- random

<a href="https://github.com/google/trax" target="_blank">Trax</a> is an end-to-end library for deep learning that focuses on clear code and speed. It is actively used and maintained in the Google Brain team. It is faster than Tensorflow and Pytorch and also the codes are more clear. It also supprts both TPUs and GPUs.


### Summarization with transformer model:

![Alt Text](https://github.com/saeedkhaki92/Transformer-Text-Summarizer/blob/main/transformer_decoder_zoomin.png)





## Dataset

CNN/DailyMail non-anonymized summarization dataset is used in this project which can be found in `Tensorflow Dataset (TFDS)`. There are two features: 
- article: text of news article, used as the document to be summarized 
- highlights: joined text of highlights with around each highlight, which is the target summary.




## Instructions

You can train the model from scrath using the Google Colab notebooks. Please use `Transformer-Text-Summarizer.ipynb` for Trax version.



