# Estudo Dirigido 4 – Aprendizado Estatístico (CEFET-MG)

Este repositório contém um Jupyter Notebook desenvolvido para a disciplina de **Aprendizado Estatístico**, focado na aplicação prática de técnicas de seleção de modelos estatísticos utilizando a linguagem **R** e o conjunto de dados `Hitters`.

## 📘 Descrição

O notebook realiza uma série de análises estatísticas com foco em:

- Análise descritiva e pré-processamento do conjunto de dados `Hitters`
- Seleção de modelos com diferentes abordagens:
  - Best Subset Selection
  - Forward Stepwise Selection
  - Validação com conjunto hold-out
  - Validação cruzada (Cross Validation)
  - Regressão Ridge
  - Regressão Lasso

As bibliotecas utilizadas incluem:

- `ISLR`
- `leaps`
- `glmnet`

## 📊 Conjunto de Dados

O conjunto `Hitters` é proveniente do pacote `ISLR` e contém informações sobre jogadores de beisebol, incluindo estatísticas de desempenho e salário. O objetivo principal é prever o salário dos jogadores com base nas demais variáveis.

## 📁 Estrutura

- `AE_estudodirigido4.ipynb`: notebook principal com todo o código e análises comentadas.
- O código está organizado em blocos com explicações teóricas e interpretação dos resultados.

## ▶️ Execução

Para executar o notebook:

1. Certifique-se de ter um ambiente Jupyter configurado com suporte a R (`IRkernel`).
2. Instale os pacotes necessários no R:
   ```r
   install.packages(c("ISLR", "leaps", "glmnet"))
    ```

3. Abra o notebook e execute os blocos de código sequencialmente.

## 🧠 Objetivos de Aprendizado

* Compreender técnicas de seleção de modelos em regressão linear.
* Comparar diferentes critérios de seleção (Cp, BIC, RSS).
* Implementar validação cruzada para avaliação de modelos.
* Aplicar penalizações (Ridge, Lasso) e interpretar seus efeitos.

## 📌 Requisitos

* Jupyter Notebook com suporte a R
* R 4.5
* Pacotes: `ISLR`, `leaps`, `glmnet`

## 📎 Fonte

Este estudo está baseado no material didático do CEFET-MG para a disciplina de Aprendizado Estatístico ministrada pelo professor Fabio Rocha da Silva.