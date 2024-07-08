# Projeto-SQL

Projeto de análise de dados usando o SQL Lite em conjunto com o AWS S3.

Este repositório contém um projeto de analise dados de clientes de cartão de crédito utilizando ferramentas de armazenamento em nuvem da Amazon, linguagem SQL para tratamento e analise dos dados e bibliotecas python para visualização dos resultados,
Objetivo do Projeto

O objetivo deste projeto é identificar, com base em um banco de dados, as principais características dos clientes de uma empresa de cartão de crédito desde sua caratacterísticas quanto ao uso do crédito para compras. Iremos obeservar qual a idade, sexo, escolaridade e renda dos clientes para poder traçar um perfil que pode ser utilizado para trabalhos de melhoria de produtos e identificação do público alvo, e como os clietes atuais utlizam seu crédito de diversas meneiras para tanto para gastos ocasionais quanto para recorrentes. Ao fim queremos observar quem são as pessoas que mais utilizam o cartão, e como o fazem para que assim diversos insights possam ser gerados.

# Conjunto de Dados

O conjunto de dados utilizado neste projeto contém informações sobre os clientes (resguardadas as diretrizes do LGPD) como por exemplo: idade, sexo, escolaridade, estado civil, salario anual, tipo do cartão, número de iterações anuais, limite de crédito, valor gasto anualmente no cartão

# Técnica Utilizada

Nesse projeto utilizamos duas principais tecnologias: a primeira foi o armazenamento em nuvem da Amazon Web Services S3, onde alocamos nosso arquivo de database e a partir dele conseguimos carrega-lo em um  Jupyter Notebook para iniciar a analise; e segundo a linguagem SQL para consulta a agregação dos dados, onde através de um interface virtual conseguimos realizar consultas dentro do próprio notebook tornando a analise bem mais fácil e intuitiva.


# Ferramentas Utilizadas

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21.4-blue.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-blue.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11.1-blue.svg)](https://seaborn.pydata.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-blue.svg)](https://scikit-learn.org/)

