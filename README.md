# Multipage document classifier

It is repo for Machine Learning 2022 Course final project 

We create model, which can split large pdf with
several documents of the same type in small doc-
uments. For example, 10 pages of which the first
document is 5, the second is 3 and the third is 2
and we want to split it into these three documents.
That is, we need to build a classifier for pages that
will predict whether the page is the first last or is
in the middle. The document type is known, but
not the quantity in the large batch

Our best model have 87 procent accuracy


## How to use: 

We implement different methods:

1. LSTM and BERT https://github.com/EvgeniaKomleva/Multipage-document-classifier/blob/main/bert_lstm_clasifier.ipynb
2. Logistic Regression https://github.com/EvgeniaKomleva/Multipage-document-classifier/blob/main/MultiPageClassification.ipynb
3. StackingClassifier https://github.com/EvgeniaKomleva/Multipage-document-classifier/blob/main/Kirill_Part.ipynb
4. RandomForestClassifier  https://github.com/EvgeniaKomleva/Multipage-document-classifier/blob/main/Vadim_part.ipynb


## Some usefull links:

ML Project Proposal  https://docs.google.com/document/d/1pBjScz3DnUuLmm07EhDZPkjdRHO1V2f_kBrFiRIjKQ4/edit?usp=sharing

Project *.pdf report. https://www.overleaf.com/read/htkpfqnrpxgg

Data https://github.com/EvgeniaKomleva/Multipage-document-classifier/blob/main/Data.zip


