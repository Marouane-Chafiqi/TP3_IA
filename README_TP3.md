# TP3:

Salut, je suis Marouane Chafiqi, étudiant en master TEE.

Ce projet est mon troisième TP de NLP (Natural Language Processing). J'y ai appris à entraîner des modèles de classification pour qu'une machine décide si un texte est positif ou négatif.

## Ce que j'ai fait

1. **Jeu de données** : une petite base de phrases avec deux classes, sentiment positif et sentiment négatif
2. **Prétraitement** : minuscules, suppression de la ponctuation, tokenisation, stopwords et lemmatisation (comme dans le TP 1)
3. **Vectorisation** : transformation des textes en vecteurs avec `TfidfVectorizer`
4. **Séparation des données** : 80 % pour l'entraînement et 20 % pour le test
5. **Entraînement** : trois modèles (régression logistique, Naive Bayes, SVM linéaire) comparés avec une validation croisée à 5 plis

## Outils utilisés

Python, Jupyter Notebook, NLTK, spaCy, scikit-learn, pandas

## Fichier principal

`TP3_NLP.ipynb` : le notebook avec le code, les résultats et mes réponses aux questions.

## Pour le lancer

```
pip install nltk spacy scikit-learn pandas
python -m spacy download fr_core_news_sm
jupyter notebook
```
