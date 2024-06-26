<h1 align="center"> Modelo preditivo para falha em equipamento mecânico </h1>

<img alt="Static Badge" src="https://img.shields.io/badge/Status-Finalizado-green"> <img alt="Static Badge" src="https://img.shields.io/badge/Vers%C3%A3o-1.0-yellow"> <br>
<img alt="Static Badge" src="https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode"> <img alt="Static Badge" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white"> <br>
<img alt="Static Badge" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"> <img alt="Static Badge" src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"> <img alt="Static Badge" src="https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white"> <img alt="Static Badge" src="https://img.shields.io/badge/scikitlearn-F7931E?logo=scikitlearn&logoColor=white">

Projeto de Machine Learning de uma base de dados de manutenção para predizer falha em um torno CNC. Projeto este que serviu como TCC para obtenção do meu diploma como Engenheiro.

# Base de dados utilizada
Base utilizada foi retirada do Kaggle, publicada por Bansal (2022) com o nome "Machine Predictive Maintenance Classification". O link para a pagina do Kaggle se encontra [aqui](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification).

# Etapas
* Exploração dos dados;
* Análises estatísticas;
* Prepração da base de treinamento;
* Treinamento do modelo de árvore de decisão;
* Otimização dos hiperparâmetros utilizando BayesSearchCV;
* Metrificações utilizando AUC-ROC.

# Arquivos
* [explore.ipynb](explore.ipynb): Código contendo a importação da base e a exploração dos dados;
* [data_treatment.ipynb](data_treatment.ipynb): Código para tratamento dos dados;
* [modelo.ipynb](modelo.ipynb): Código do treinamento, testes e otimizações do modelo de ML.
