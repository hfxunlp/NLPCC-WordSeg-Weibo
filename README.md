# NLPCC2016-WordSeg-Weibo
NLPCC 2016 微博分词评测项目

##Description of the Task

Word is the fundamental unit in natural language understanding. However, Chinese sentences consists of the continuous Chinese characters without natural delimiters. Therefore, Chinese word segmentation has become the first mission of Chinese natural language processing, which identifies the sequence of words in a sentence and marks the boundaries between words.

Different with the popular used news dataset, we use more informal texts from Sina Weibo. The training and test data consist of micro-blogs from various topics, such as finance, sports, entertainment, and so on.

Each participant will be allowed to submit the three runs: closed track run, semi-open track run and open track run.

1. In the **closed** track, participants could only use information found in the provided training data. Information such as externally obtained word counts, part of speech information, or name lists was excluded.
2. In the **semi-open** track, participants could use the information extracted from the    provided background data in addition to the provided training data. Information such       as externally obtained word counts, part of speech information, or name lists was excluded.
3. In the **open** track, participants could use the information which should be public        and be easily obtained. But it is not allowed to obtain the result by the manual         labeling or crowdsourcing way.

## Data

The data are collected from Sina Weibo. Both the training and test files are UTF-8 encoded. Besides the training data, we also provide the background data, from which the training and test data are drawn. The purpose of providing the background data is to find the more sophisticated features by the unsupervised way.

## Evaluation Metric

Different with the standard precision, recall, F1-score, we will provide a new measure metric this year. The detailed metric will be available when we release the training and test datasets.

## Papers

1. Peng Qian, Xipeng Qiu, Xuanjing Huang, A New Psychometric-inspired Evaluation Metric for Chinese Word Segmentation, In Proceedings of Annual Meeting of the Association for Computational Linguistics (ACL), 2016. [[PDF\]](http://aclweb.org/anthology/P/P16/P16-1206.pdf)

## Contact Information

For any questions about this shared task, please contact:
[Xipeng Qiu](http://nlp.fudan.edu.cn/xpqiu/)
Group of NLP & DL
School of Computer Science, Fudan University
Email: xpqiu@fudan.edu.cn