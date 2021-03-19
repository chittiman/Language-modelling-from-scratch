# Language-modelling-from-scratch

This project is about language modelling on Indian Ex-PM Mr.Manmohan singh speeches

Note - This is my 1st project just after I completed my NLP course. I wanted to learn how to create an entire project from scratch. I made many mistakes in this, but it was a great learning experience. Wherever possible in the notebook, the mistakes were noted and the better alternatives are explained.

The repository consists of 4 notebooks which demonstrate the following tasks

1) [Preparing dataset through scraping the web](https://github.com/chittiman/Language-modelling-from-scratch/blob/main/Dataset%20Preparation%20through%20web%20scraping.ipynb): This notebook demonstrates how the dataset is prepared by scraping the archives of PM speeches using Scrapy. This forms our training dataset
2) [Cleaning the dataset](https://github.com/chittiman/Language-modelling-from-scratch/blob/main/Dataset%20Cleaning%20through%20Regex.ipynb): This notebook demonstrates how to clean the data to using Regex inorder to maximize the coverage of vocabulary using GLOVE word vectors.
3) [Language Modelling using Pytorch](https://github.com/chittiman/Language-modelling-from-scratch/blob/main/Language%20Modelling%20through%20Pytorch.ipynb): This notebbok demonstrates how to create a language model using Pytorch and how to generate better text during inference using Top-K sampling.

Additional: [Preparation of Dataset](https://github.com/chittiman/Language-modelling-from-scratch/blob/main/Test%20Dataset%20Preparation.ipynb): When the speeches archive is scraped earlier, some speeches were missed. Those missing speeches were scraped in this notebook and those are used as Test set during inference
