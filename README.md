# Projeto-SQL

Projeto de análise de dados usando o SQLite em conjunto com o AWS S3.

Este repositório contém um projeto de análise de dados de clientes de cartão de crédito, utilizando ferramentas de armazenamento em nuvem da Amazon, linguagem SQL para manipulação e análise dos dados, e bibliotecas Python para visualização dos resultados.
# Objetivo do Projeto

O objetivo deste projeto é identificar, com base em um banco de dados, as principais características dos clientes de uma empresa de cartão de crédito, tanto em termos demográficos quanto comportamentais no uso do crédito. Analisaremos variáveis como idade, sexo, escolaridade e renda dos clientes para delinear um perfil que possa ser utilizado em estratégias de aprimoramento de produtos e segmentação de mercado. Além disso, investigaremos os padrões de utilização do crédito para despesas ocasionais e recorrentes. No final, pretendemos identificar os segmentos de clientes que mais utilizam o cartão e seus comportamentos específicos, possibilitando a geração de insights estratégicos.

# Conjunto de Dados

O conjunto de dados utilizado neste projeto contém informações detalhadas sobre os clientes, conforme as diretrizes da LGPD, incluindo: idade, sexo, escolaridade, estado civil, salário anual, tipo de cartão, número de interações anuais, limite de crédito e valor gasto anualmente no cartão.

# Técnica Utilizada

Neste projeto, empregamos as seguintes tecnologias principais:

- Amazon Web Services S3: Utilizamos o serviço de armazenamento em nuvem AWS S3 para hospedar nosso arquivo de banco de dados, permitindo seu carregamento em um ambiente Jupyter Notebook para iniciar a análise de dados.
- SQL: Utilizamos a linguagem SQL para execução de consultas e agregação dos dados. Através de uma interface virtual integrada no Jupyter Notebook, realizamos consultas diretamente no ambiente, facilitando a análise e tornando-a mais eficiente e intuitiva.


# Ferramentas Utilizadas

[![SQLite](https://img.shields.io/badge/SQLite-3.35.5-blue.svg)](https://sqlite.org/)
[![Boto3](https://img.shields.io/badge/Boto3-1.18.69-blue.svg)](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-blue.svg)](https://matplotlib.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11.1-blue.svg)](https://seaborn.pydata.org/)
[![Botocore](https://img.shields.io/badge/Botocore-1.21.69-blue.svg)](https://botocore.amazonaws.com/v1/documentation/api/latest/index.html)
[![Tabulate](https://img.shields.io/badge/Tabulate-0.8.9-blue.svg)](https://pypi.org/project/tabulate/)



