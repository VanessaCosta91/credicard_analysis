# Projeto de análise de cartão de crédito

---

## 1. Coleta de Dados

* **Origem**: Plataforma [Kaggle](https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset?utm_source=chatgpt.com)
* **Acesso**: aquivo .csv
* **Tipo de dados**: Estruturados (tabelas padronizadas)

c

## 2. Limpeza dos dados 

* **Duplicatas**: Verificação de registros repetidos que poderiam distorcer os resultados da análise.
* **Valores Nulos**: Análise de campos ausentes que poderiam comprometer os agrupamentos e visualizações.


Nesta base, não foram encontrados registros duplicados nem valores ausentes.

---

## 3 - Análise Exploratória dos Dados (EDA)

Foram realizadas as seguintes investigações:

* Distribuição dos valores de transação por estado e cidade.
* Correlação entre valor da transação, limite de crédito e localização geográfica.
* Dispersão entre o valor das transações e o limite de crédito.
* Identificação de transações com valores atípicos (outliers).
* Frequência de uso de cada cartão de crédito.

### Principais Leituras:
* O maior volume financeiro das transações está concentrado no estado de New Hampshire, representando 38,88% do total. Em seguida vêm Pensilvânia (15,19%) e Nova York (10,42%).
* A cidade com maior volume de transações é Washington, com 37,06% do total, seguida por Houston (7,14%) e Nova York (5,90%).
* A correlação entre o valor da transação e o limite de crédito, cidade ou estado é insignificante, sugerindo que o comportamento do consumidor independe dessas variáveis.
* Foi observado um alto volume de transações com valores abaixo de R$ 200,00, mesmo entre clientes com limites elevados. Isso pode indicar uma disparidade entre o limite concedido e o comportamento real de consumo, apontando uma possível oportunidade de revisão na política de concessão de crédito.

---

## 4. Tecnologias Utilizadas

* **Google Colab**
* **Python (Pandas, Matplotlib, Seaborn)**

---

## Autora

**Vanessa Costa**
