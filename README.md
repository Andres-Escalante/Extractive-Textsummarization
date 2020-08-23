# Extractive Text summarization

Code used for my master thesis, It explores 4 difference methods of extractive text summarization in 2 different datasets. The code + commentaries are in the 4 notebooks.

This code uses 2 datasets:
- Dataset 1: https://www.kaggle.com/sunnysai12345/news-summary
- Dataset 2: https://www.tensorflow.org/datasets/catalog/cnn_dailymail or https://cs.nyu.edu/~kcho/DMQA/ both CNN and Daily mail stories
- Dataset 3: https://www.tensorflow.org/datasets/catalog/multi_news or https://github.com/Alex-Fabbri/Multi-News

The methods explored are:
1. Top k sentences (modified lead-3-sentences)
2. Word frequency
3. TextRank
4. Latent Semantic Analysis (LSA)
5. [Presumm](https://github.com/nlpyang/PreSumm)

There are different notebooks:
- datasets.ipynb: Initial preprocessing
- dataset1.ipynb: Methods 1-4 for dataset 1
- dataset2.ipynb: Methods 1-4 for dataset 2
- dataset3.ipynb: Methods 1-4 for dataset 3
- PreSumm.ipynb: Method 5 for all datasets


The results are evaluated Using the F1-Score of ROUGUE-1, ROUGE-2 and ROUGE-L

For more details specific notebook and see the report.

The extra code needed have also been included. PresSumm source code from https://github.com/nlpyang/PreSumm with little modifications, stanford-corenlp-full-2018-10-05, PyTLDR library and the datasets as txt files.

Author: Andrés Escalante Ariza
All references are in the report and the code
