# Analyse de sentiments avec PyTorch

Ce repository contient des tutoriels sur comment faire de l'analyse de sentiments en utilisant Pytorch 1.4 sur Python 3.7. 

## Installation 

 - Pour installer PyTorch, les instructions sont sur [ce site.](https://pytorch.org/get-started/locally/) 

 - TorchText : ` pip install torchtext`
 
 - spaCy en anglais : `python -m spacy download en`
 
 - transformers : `pip install transformers`
## Données

On utilise les données [IMBD.](https://ai.stanford.edu/~amaas/data/sentiment/)
## Tutoriels

 - 0 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb) 
 
 Dans ce premier notebook, on utilise les librairies **sklearn** et **nltk** pour faire de l'analyse de sentiments à l'aide de méthode statistique de **Bag-of-words**, **TF-IDF** et d'algorithmes de machine learning : **SVM** et **Régression Logistique**.

 - 1 - [RNN](https://github.com/aminaghoul/sentiment-analysis/blob/master/1-RNN-Simple.ipynb)

On utilise ici un modèle de réseaux de neurones récurrents **RNN** très simple.

 - 2 - [LSTM](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)
 
 Le modèle précédent se complexifie dans ce notebook, on utilise un modèle **LSTM**, bidirectionnel, multi-couches. 
 
 - 3 - [FastText](https://github.com/aminaghoul/sentiment-analysis/blob/master/3-FastText.ipynb)

Le modèle **FastText** issu de l'article [Bag of Tricks for Efficient Text Classification](https://arxiv.org/abs/1607.01759) est implémenté ici.

 - 4 - [CNN](https://github.com/aminaghoul/sentiment-analysis/blob/master/4-CNN.ipynb) 
 
On utilise le modèle **CNN** pour l'analyse de sentiments.
 
 - 5 - [AttentionLSTM](https://github.com/aminaghoul/sentiment-analysis/blob/master/5-AttentionLSTM.ipynb) 
 
 On utilise un modèle **LSTM** combiné avec de l'**attention**. Ce modèle est décrit dans l'article [Text Classification Research with Attention-based Recurrent Neural Networks.](https://www.researchgate.net/publication/323130660_Text_Classification_Research_with_Attention-based_Recurrent_Neural_Networks)
 
 - 6 - [TransformersLSTM](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb) 
 
On utilise la libraire **transformers** pour importer un modèle transformer pré-entraîné pour obtenir les embedding du texte, et les utiliser dans un modèle **LSTM** pour prédire le sentiment.
 
 - 7 - [Transformers](https://github.com/aminaghoul/sentiment-analysis/blob/master/7-Transorfmers.ipynb)
 
Dans ce notebook est implémenté le modèle **transformer** en PyTorch décrit dans l'article [Attention Is All You Need](https://arxiv.org/pdf/1706.03762v5.pdf)
 
  - 8 - [BERT](https://github.com/aminaghoul/sentiment-analysis/blob/master/8-BERT.ipynb)

 Enfin, on implémente le modèle **BERT** décrit [ici](https://arxiv.org/abs/1810.04805) en utilisant [Hugging Face.](https://github.com/huggingface/transformers) 
 
 ## Résultats
 
Modèle          |Accuracy|Nombre de paramètres|
----------------|--------|--------------------|
SVM - BOW       | 86.95  |                    |
LR - BOW        | 87.08  |                    |
SVM - TF-IDF    | 87.80  |                    | 
LR - TF-IDF     | 87.82  |                    |
RNN             | 68.21  |     2,684,009      |
BiLSTM          | 88.67  |     4,810,857      |
GRU             | 91.01  |     4,233,321      |
FastText        | 87.22  |     2,500,301      |
CNN             | 84.97  |     2,620,801      |
AttentionLSTM   | 83.27  |     39,559,466     |
AttentionGRU    | 80.28  |     39,273,770     |
TransformersLSTM| 90.31  |     3,678,721      |
TransformersGRU | 91.36  |     2,759,169      |
Transformers    | 73.31  |     6,928,642      |
BERT            | 91.77  | 

   
 ## Références : 
 
 - [pytorch-sentiment-analysis ](https://github.com/bentrevett/pytorch-sentiment-analysis#tutorials) 

