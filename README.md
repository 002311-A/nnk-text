# Non-Negative Kernel Regression (NNK) in NLP Applications

## Introduction ##


This work considers the effectiveness of graph signal processing techniques in generating instance-based explanations for natural language processing models. The focus is on Non-Negative Kernel Regression (NNK) an alternative to the K-Nearest Neighbors algorithm. The project involved quantiative and qualitative analysis of NNK graphs for various NLP models and across different architectures. 

## Methods ##

- Analysed explanations given by the NNK graph of NLP models based on LSTM and Transformer architectures
- Generated LIME visualizations for NNK-based classifiers to further aid interpretability 


## Results ##

- NNK was able to eliminate redundancies in the generated examples and explanations
- Combining LIME-based approaches with NNK provided powerful insights into model decisions 
- NNK-based classifiers were able to maintain or improve accuracy compared to the original model and KNN classifiers 
- Interpretable examples were achieved only on transformer- based architectures

## Possible Future Work ##

A lack of qualitative evaluation methods makes evaluating interpretability challenging, hence future work should focus on building better qualitative metrics to evaluate interpretability methods.
