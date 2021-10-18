# Twitter Fake News Detector about COVID19 with BERT and SimpleTransformer

## Background
Fake News have become a major concern during the last years. Thanks to the advances in technology and its accessibility, anyone can post/upload any Fake News and widely spread them through the network.
This becomes a risky issue when it comes to COVID-19 pandemic topic. In this matter it hurts not only the reached person who believes them but also to the common health, as everybody can be a focus of spread of the virus.

## Aim
This notebooks intends to support the management of content on the Social Networks during the COVID-19 pandemic. For that, it's been built a Deep Learning classifier using BERT model and two of its variants: Albert and Roberta. The purpose of this classifier is to detect whether a tweet is fake news and might:
1. Under-rank them in the feeds
2. Ban the content
3. Raise a disclaimer announcing that the content might be fake-news.

### The steps followed have been:
1. Research for a labelled datasets.
2. Data mining on labelled datasets.
3. Build, train and evaluate several BERT models and choose the best one.
4. Retrieve dataset from Zenodo and hydrate tweets.
5. Run predictions over Zenodo dataset.
