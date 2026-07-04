Predição da Popularidade de Músicas no Spotify

Projeto de Machine Learning para classificação da popularidade de músicas utilizando características de áudio disponibilizadas pela Spotify Web API. O objetivo é desenvolver um modelo capaz de prever se uma música será popular ou não popular com base em atributos como dançabilidade, energia, valência, tempo e outras features acústicas. Projeto MVP desenvolvido para a disciplina de Machine Learning & Analytics da pós-graduação em Ciência de Dados e Analytics da PUC-Rio.

Objetivos
- Desenvolver um modelo de classificação supervisionada para prever a popularidade de músicas.
- Avaliar o desempenho de diferentes algoritmos de Machine Learning.
- Identificar quais características de áudio mais influenciam a popularidade das músicas.
- Comparar métricas de desempenho entre os modelos desenvolvidos.

Questões de Pesquisa
- É possível prever a popularidade de uma música utilizando apenas suas características de áudio?
- Quais atributos possuem maior influência na classificação das músicas?
- Qual algoritmo apresenta o melhor desempenho para esse problema de classificação?

Principais Etapas
- Análise exploratória dos dados (EDA)
- Tratamento e pré-processamento dos dados
- Criação da variável-alvo is_popular
- Engenharia de atributos
- Treinamento e comparação de modelos de classificação
- Avaliação utilizando métricas de desempenho

Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


Como Executar
Google Colab

Abra o notebook diretamente no Google Colab:
https://colab.research.google.com/drive/1lUBIWnYnRoMzKQ56_zwECC-OvnTMwswG?usp=sharing

Execução Local
Clone este repositório.

Instale as dependências:
pip install -r requirements.txt

Execute o Jupyter Notebook:
jupyter notebook


Dataset

O projeto utiliza o Spotify Tracks Dataset, disponível publicamente no Kaggle:

https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset


Resultados Esperados
- Identificação das características de áudio mais relevantes para a popularidade das músicas.
- Comparação do desempenho entre diferentes modelos de Machine Learning.
- Avaliação das limitações do modelo considerando fatores externos, como marketing e popularidade do artista, que não estão presentes no dataset.


Possíveis Melhorias
- Testar modelos mais avançados, como XGBoost e LightGBM.
- Ajustar hiperparâmetros para otimização dos modelos.
- Utilizar técnicas de seleção de atributos.
- Incorporar informações sobre artistas, álbuns e tendências temporais.
- Desenvolver uma aplicação para realizar previsões em tempo real.


Autora

Isadora Sousa
