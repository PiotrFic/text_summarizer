# BBC News TL;DR Generator
## Simple Text Summarizer

This 'Too Long; Didn't Read' generator creates simple, extraction-based summary bullets from random BBC tech-related news stories (full dataset is available at http://mlg.ucd.ie/datasets/bbc.html).

Program is using a cosine similarity to compare the sentences and rank them accordingly using PageRank algorithm. Top ranked sentences are presented as a summary.

Cosine similarity is a metric that measures the cosine of an angle between two vectors projected in multi-dimensional space. The smaller the angle between the vectors, the more similar they are to each other (check out https://youtu.be/m_CooIRM3UI for more details).
