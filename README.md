# Analyse de sentiments avec PyTorch

Ce repository contient des tutoriels sur comment faire de l'analyse de sentiments en utilisant Pytorch 1.4 sur Python 3.7. 


Les deux notebooks suivants sont dédiés à l'analyse de sentiments en utilisant un modèle de réseaux de neurones récurrents.

Dans le troisième notebook, on utilise le modèle FastText

## Tutoriels

 - 1 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)
 
 Dans ce premier notebook, est présenté l'analyse de sentiments à l'aide de méthode statistique de **Bag-of-words**, **TF-IDF** et d'algorithmes de machine learning : **SVM** et **Régression Logistique**.

 - 2 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)

On utilise ici un modèle de réseaux de neurones récurrents **RNN** très simple.

 - 3 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)
 
 Le modèle précédent se complexifie dans ce notebook, on utilise un modèle **LSTM**, bidirectionnel, multi-couches. 
 
 - 4 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)

Le modèle **FastText** issu de l'article [Bag of Tricks for Efficient Text Classification](https://arxiv.org/abs/1607.01759) est implémenté ici.

 - 5 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)
 
 On utilise un modèle **LSTM** combiné avec de l'**attention**. Ce modèle est décrit dans l'article [Text Classification Research with Attention-based Recurrent Neural Networks.](https://www.researchgate.net/publication/323130660_Text_Classification_Research_with_Attention-based_Recurrent_Neural_Networks)
 
 - 6 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)
 
On utilise la libraire **transformers** pour importer un modèle transformer pré-entraîné pour obtenir les embedding du texte, et les utiliser dans un modèle **LSTM** pour prédire le sentiment.
 
 - 7 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)
 
 Dans ce notebook est implémenté le modèle **transformer** en PyTorch décrit dans l'article [Attention Is All You Need](https://arxiv.org/pdf/1706.03762v5.pdf)
 
 - 8 - [MachineLearning](https://github.com/aminaghoul/sentiment-analysis/blob/master/0-MachineLearning.ipynb)[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bentrevett/pytorch-sentiment-analysis/blob/master/1%20-%20Simple%20Sentiment%20Analysis.ipynb)

 Enfin, on implémente le modèle **BERT** décrit [ici](https://arxiv.org/abs/1810.04805) en utilisant [Hugging Face.](https://github.com/huggingface/transformers) 
 
 ## Résultats
 
 ## Références : 
 
 - [pytorch-sentiment-analysis ](https://github.com/bentrevett/pytorch-sentiment-analysis#tutorials) 
 
