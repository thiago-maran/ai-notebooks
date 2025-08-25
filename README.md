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

    - [`BTC_forecasting_DL_vs_linear`](deep-learning/time-series/BTC_forecasting_DL_vs_linear.ipynb)  
      Previsão do preço de fechamento do **Bitcoin (BTC-USD)** com múltiplos modelos e análise de desempenho.
    
    - [`AAPL_forecasting_DL_vs_linear`](deep-learning/time-series/AAPL_forecasting_DL_vs_linear.ipynb)  
      Estudo semelhante focado nas ações da **Apple (AAPL)** com os mesmos modelos preditivos.

  - [`multilayer-perceptron/`](deep-learning/multilayer-perceptron/)  
      - [`fraud-detection-mlp-vs-transformer/`](deep-learning/multilayer-perceptron/fraud-detection-mlp-vs-transformer/)  
        Comparação de **MLP** (rede neural densa) e **Transformer** com baseline em **Regressão Logística** para **detecção de fraudes**.  
        Ênfase em arquiteturas de **deep learning** para dados tabulares.  
        Discussão sobre trade-offs: interpretabilidade, custo computacional e desempenho.  
        Visualizações completas: ROC, Precision-Recall, matrizes de confusão e gráficos comparativos.  
        Uso de técnicas de balanceamento: **SMOTE** e **SMOTEENN**.  

