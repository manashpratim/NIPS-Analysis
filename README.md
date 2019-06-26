# NIPS-Analysis
Exploratory Data Analysis of Conference on Neural Information Processing Systems (1987-2017)
# Description
The goal of this project is to analyze the  Conference on Neural Information Processing Systems (NIPS). The dataset is available at https://www.kaggle.com/benhamner/nips-papers. In the NIPS Analysis Notebook, I have performed Exploratory Data Analysis of the Conference.

The analysis gives the following insights:
1) Number of papers accepted yearly shows an increasing trend.
2) Most of the papers have two authors.
3) Michael I. Jordan has the most number of accepted papers at NIPS.
4) Michael I. Jordan has published at NIPS for 27 years.

I have also plotted Word Cloud of the Top 100 and Top 200 words of the paper titles and paper texts.

In the Text Summarizer Notebook, I have implemented a Sequence 2 Sequence LSTM Model to present a short summary of the papers. Given a paper, the model would return a short abstractive summary of the paper. https://keras.io/examples/lstm_seq2seq/ has served as my guide in implementing the model. This model can be greatly improved by tuning the hyperparameters which is beyond my scope due to resource constraints.
