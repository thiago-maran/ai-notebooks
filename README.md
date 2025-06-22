# 🧠 AI Notebooks

Este repositório reúne uma coleção de notebooks de **Inteligência Artificial**, **Machine Learning**, **Deep Learning** e **Processamento de Linguagem Natural (NLP)**. Organizado por temas, serve como um laboratório de experimentação, estudos e desenvolvimento de projetos com foco em aprendizado de máquina e IA.

## 📁 Estrutura do Repositório

- [`classification/`](classification/)  
  Notebooks focados em tarefas de **classificação supervisionada**, como regressão logística, árvores de decisão, etc.

  - [`cart-abandonment-xgboost/`](classification/cart-abandonment-xgboost/)  
    Predição de **abandono de carrinho em e-commerce** utilizando o algoritmo **XGBoost**.  
    O projeto simula dados de comportamento do usuário (como tempo na página, cliques e visualizações de produtos) e aplica um modelo de classificação supervisionada para prever se um cliente irá ou não concluir a compra.  
    Inclui tratamento de dados em JSON, encoding de variáveis categóricas, explicação passo a passo do pipeline de machine learning e função customizada para predição em tempo real com novos dados.
    
- [`regression/`](regression/)  
  Modelos voltados para **regressão**, prevendo valores contínuos com algoritmos como Regressão Linear e Random Forest.

- [`clustering/`](clustering/)  
  Técnicas de **agrupamento não supervisionado**, como K-Means, para segmentação e descoberta de padrões.

- [`nlp/`](nlp/)  
  Aplicações de **Processamento de Linguagem Natural**, incluindo análise de sentimentos, vetorização de texto, e similaridade semântica.

- [`recommendation-systems/`](recommendation-systems/)  
  Sistemas de recomendação com algoritmos como SVD, voltados para filtragem colaborativa e sugestões personalizadas.

  - [`svd-tfidf-ecommerce-recommender/`](recommendation-systems/svd-tfidf-ecommerce-recommender/)  
    Projeto de recomendação híbrida para **e-commerce**, combinando **SVD** (filtragem colaborativa) com **TF-IDF** (filtragem baseada em conteúdo).  
    Inclui dataset fictício e abordagem robusta para recomendação mesmo em cenários de _cold start_.

- [`deep-learning/`](deep-learning/)  
  Projetos com foco em **redes neurais profundas**, aplicadas a diferentes domínios como **visão computacional (CNNs)**, **séries temporais (LSTM, GRU)** e outras arquiteturas voltadas para classificação, previsão e análise de dados complexos.
  - [`time-series/`](deep-learning/time-series/)  
    Notebooks dedicados à **previsão de séries temporais financeiras** utilizando **redes neurais recorrentes (RNNs)** como LSTM, GRU e SimpleRNN, em comparação com abordagens tradicionais de regressão linear e polinomial.  
    Os modelos são avaliados com métricas como **MSE**, **RMSE**, **MAPE** e **índice de Sharpe**, considerando o horizonte de previsão de 14 dias.  
    Este estudo comparativo foi utilizado como base para o artigo acadêmico:  
    _**"Abordagens Tradicionais e de Deep Learning para Previsão de BTC-USD e AAPL"**_.

    - [`time_series_forecasting_BTC_models_comparison.ipynb`](deep-learning/time-series/time_series_forecasting_BTC_models_comparison.ipynb)  
      Previsão do preço de fechamento do **Bitcoin (BTC-USD)** com múltiplos modelos e análise de desempenho.
    
    - [`time_series_forecasting_AAPL_models_comparison.ipynb`](deep-learning/time-series/time_series_forecasting_AAPL_models_comparison.ipynb)  
      Estudo semelhante focado nas ações da **Apple (AAPL)** com os mesmos modelos preditivos.
