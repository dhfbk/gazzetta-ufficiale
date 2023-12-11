# Italian Legislative Text Classification for Gazzetta Ufficiale

This repository contains the dataset used in the following paper:

M. Rovera, A. Palmero Aprosio, F. Greco, M. Lucchese, S. Tonelli and A. Antetomaso (2023) [Italian Legislative Text Classification for Gazzetta Ufficiale](https://aclanthology.org/2023.nllp-1.6/). In *Proceedings of the Natural Legal Language Processing Workshop 2023*, pp. 44-50, 2023.

The [model](https://huggingface.co/dhfbk/gulbert-ft-ita) can be found on our [Hugging Face account](https://huggingface.co/dhfbk).

## Dataset
The *data* folder contains a *stratified* data split (60/20/20) used for evaluation.
Each data point has a unique identifier, created by the data provider (ex. *088G0010*).
Data fields:
- *date*: date of publication of the current document (act)
- *title*: text of the document's title
- *labels*: list of labels assigned to the current document
- *talking_labels*: list of labels assigned to the current document (in human-readable format) 

