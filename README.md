# DeepTTA implementation
An implementation of the architecture described in the paper "DeepTTA: a transformer-based model for predicting cancer drug response" (https://academic.oup.com/bib/article/23/3/bbac100/6554594). 

The model is designed to predict the response to a wide array of different drugs based on the individual patient’s gene expression data. A transformer architecture is used to encode the chemical structure of the drugs, while the gene expression data is passe trough a feed forward layer. The output is the drugs predicted IC50 value.

The authors are providing their own implementation on GitHub (https://github.com/jianglikun/DeepTTC). However, possible due to a slight change in one of the datasets, their code is no longer running. The complex structure and limited documentation make it very difficult to fix or adapt. Therefore, this implementation is solely based on the description of the architecture in the paper and follows it closely.

This implementation successfully demonstrates the concept, but the long training time and limited resources didn't allow for a systematic exploration of the parameter space. Therefore, it does not achieve the same performance advertised in the paper. Better tuning of hyperparameters could certainly improve the results.
