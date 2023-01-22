# Validação de dados utilizando TFDV

Em machine learning, quando queremos criar uma rede neural temos duas frameworks que nos auxiliam nesta tarefa, PyTorch e Tensorflow. Ambos possuem suas qualidades e defeitos e neste artigo iremos abordar uma biblioteca muito interessante do Tensorflow chamada Tensorflow Data Validation ou TFDV.

Tensorflow Data Validation (TFDV) analisa dados de treino e teste afim de:

* Computar estatística descritiva.

* Deduzir um schema.

* Detectar anomalias nos dados.

A finalidade deste notebook é demostrar o quão útil esta biblioteca pode ser, ela pode facilitar muito a nossa vida na hora da limpeza dos dados. Vale a pena mencionar que TFDV está presente nas etapas de limpeza dos dados, treinamento de um modelo, realizar previsões e deploy. Aqui iremos demonstrar como ela pode ser usada para auxiliar na Limpeza dos dados. As outras funcionalidade serão tratadas em futuros notebooks.
