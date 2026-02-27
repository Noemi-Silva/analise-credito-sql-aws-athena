# 📊 Análise de Crédito com SQL no AWS Athena

## 🎯 Contexto do Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados de crédito utilizando SQL no AWS Athena, com dados armazenados em um bucket no Amazon S3.

A proposta é simular um ambiente real de análise de dados em nuvem, aplicando consultas SQL para extrair insights relevantes sobre o perfil de crédito dos clientes.

---

## ☁️ Arquitetura Utilizada

- Amazon S3 (armazenamento dos dados)
- AWS Athena (consulta SQL serverless)
- Google Colab
- Kaggle Notebook

Fluxo:

S3 → Athena → Queries SQL → Análise → Storytelling

---

## 🗄️ Criação da Base de Dados

### 1️⃣ Upload para o S3
Foi criado um bucket chamado:

`bucket-transacoes`

O arquivo `credito8.csv` foi carregado no bucket.

### 2️⃣ Criação da Tabela no Athena

A tabela foi criada utilizando o comando SQL disponibilizado no material de apoio.

---

## 🔎 Exploração dos Dados com SQL

Foram desenvolvidas queries para responder perguntas como:

- Qual o perfil médio de renda?
- Distribuição por estado civil?
- Relação entre limite de crédito e inadimplência?
- Análise por faixa etária?
- Perfil de clientes com maior risco?

---

## 📈 Exemplos de Análises

### Distribuição por tipo de Cartão

<img width="672" height="565" alt="image" src="https://github.com/user-attachments/assets/7828631b-8ae8-479b-8c1d-551ef6410b60" />


### Análise por Estado Civil

<img width="783" height="170" alt="image" src="https://github.com/user-attachments/assets/f21f87e4-61d6-40fb-9cca-61ee095efef0" />


---

## 🧠 Principais Insights

- Identificação de padrões de crédito por perfil demográfico
- Relação entre limite e risco potencial
- Segmentações relevantes para análise de risco

---

## 🛠️ Tecnologias Utilizadas

- SQL
- AWS S3
- AWS Athena
- Python
- Pandas

---

## 🔗 Notebook no Kaggle

https://www.kaggle.com/code/noemisilva/an-lise-de-cr-dito-sql-aws-athena

---

## 👩‍💻 Autora

Noemi Silva  
Projeto desenvolvido como prática de análise de dados em ambiente cloud.
