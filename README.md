# Santander Customer Transaction Prediction

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** e o treinamento de um modelo de **Machine Learning** para prever se um cliente realizará uma transação.

O trabalho utiliza o dataset **Santander Customer Transaction Prediction**, amplamente utilizado em competições de ciência de dados.

---

## Objetivo

O objetivo do projeto é:

- Explorar os dados do dataset
- Identificar padrões nas variáveis
- Analisar o comportamento da variável target
- Construir um modelo de classificação para prever transações

---

## Dataset

O dataset contém:

- **200 variáveis numéricas anônimas**
- **1 variável target**

A variável **target** indica se o cliente realizará uma transação ou não.

---

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. Importação das bibliotecas
2. Carregamento dos dados
3. Análise exploratória (EDA)
4. Visualização das distribuições das variáveis
5. Análise da variável target
6. Treinamento do modelo
7. Validação utilizando **Stratified K-Fold**
8. Avaliação do modelo utilizando **ROC-AUC**

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- Jupyter Notebook

---

## Modelo Utilizado

O modelo utilizado foi o **LightGBM**, um algoritmo baseado em **Gradient Boosting**, conhecido por sua eficiência e desempenho em problemas de classificação.

A validação foi realizada utilizando **Stratified K-Fold**, garantindo melhor avaliação em datasets desbalanceados.

---

## Métrica de Avaliação

A métrica utilizada foi:

**ROC-AUC**

Essa métrica é adequada para problemas de classificação com classes desbalanceadas.

---
├── README.md


---

## Resultados

O modelo foi capaz de identificar padrões nas variáveis e realizar previsões sobre a probabilidade de transação de um cliente.

---

## Possíveis Melhorias

- Testar diferentes algoritmos de machine learning
- Realizar engenharia de features
- Ajuste de hiperparâmetros
- Análise de importância das variáveis

---

Projeto desenvolvido para fins de estudo em **Ciência de Dados e Machine Learning**.
