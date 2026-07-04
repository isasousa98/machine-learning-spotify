# machine-learning-spotify
MVP da disciplina Machine Learning &amp; Analytics: classificação da popularidade de músicas utilizando características de áudio do Spotify e algoritmos de Machine Learning.

# MVP - Machine Learning e Analytics

## Predição de Popularidade de Músicas no Spotify

### Objetivo

Este projeto tem como objetivo construir um modelo de Machine Learning capaz de prever se uma música será popular ou não utilizando apenas características de áudio fornecidas pela Spotify Web API.

Trata-se de um problema de classificação supervisionada binária.

---

## Dataset

Spotify Tracks Dataset

Fonte:
https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

Também disponível em repositórios públicos no GitHub.

Quantidade aproximada de registros:

- 114.000 músicas

Quantidade de atributos:

- 20 colunas

---

## Variável alvo

Foi criada uma nova variável:

```
is_popular
```

onde:

- 1 → popularity >= 50
- 0 → popularity < 50

---

## Principais Features

- danceability
- energy
- loudness
- valence
- acousticness
- speechiness
- instrumentalness
- liveness
- tempo
- duration_ms
- explicit


## Tecnologias

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Autor

Isadora Sousa
