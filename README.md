This repository contains code for the Kaggle competition [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)

## Approaches
Both approaches try to answer the question "What do we know about COVID-19 risk factors?"

###  Pattern Matching
Simple pattern matching approach via regular expressions, to first find relevant text passages and the mentioned risk factors and then search for specific information, again via regular expressions.

### QA via BERT
Finding relevant texts via pattern matching then applying BERT to generate answers which are then summarized via BAR
