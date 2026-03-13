# 📈 Análise Exploratória de Vendas (AdventureWorks)

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Data_Analysis-00f2ff?style=for-the-badge&logo=googleanalytics&logoColor=black" />
</div>

<br>

> **Objetivo:** Conduzir uma **Análise Exploratória de Dados (EDA)** completa sobre o histórico de vendas do clássico banco de dados da Microsoft (AdventureWorks), respondendo a perguntas estratégicas de negócio através de visualizações gráficas e tabelas dinâmicas.

---

## 🎯 Visão Geral do Projeto

Este projeto tem foco na transformação de dados brutos de planilhas (`.xlsx`) em *insights* de negócio. Foram utilizadas técnicas de limpeza, agrupamento e visualização de dados em **Python** para entender o comportamento de vendas, margens de lucro e desempenho temporal da empresa fictícia *AdventureWorks*.

Toda a análise foi construída e documentada em um notebook interativo:
👉 **[Acessar o Notebook da Análise Completa (`analise-exploratoria.ipynb`)](analise-exploratoria.ipynb)**

---

## 🗂️ O Dataset

Os dados utilizados são provenientes da base pública **AdventureWorks** disponibilizada pela Microsoft, focada em registrar transações de vendas de equipamentos de ciclismo.

- **Arquivo Principal:** `AdventureWorks.xlsx`
- **Variáveis Chave Analisadas:** Custo, Preço de Venda, Lucro, Classe do Produto, Tempo de Envio, e Volume de Vendas por Loja/Região.

---

## 💡 Perguntas de Negócio Respondidas

Durante a análise, focamos em desvendar métricas vitais para a tomada de decisão da gerência comercial. Algumas das perguntas respondidas no código incluem:

1. Qual foi a **Receita Total** e o **Lucro Total** gerados no período?
2. Qual a margem de lucro por marca ou categoria de produto?
3. Qual é o tempo médio de envio (em dias) dos produtos vendidos?
4. Quais são as marcas mais lucrativas do portfólio?
5. Como está distribuído o lucro ano a ano e mês a mês (Sazonalidade e Crescimento)?

*(Todas as respostas são acompanhadas de gráficos de linha, barra e matrizes geradas pelo `matplotlib` / `seaborn`).*

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Ambiente:** Jupyter Notebook
- **Bibliotecas Principais:**
  - `pandas`: Para manipulação, limpeza e agregação do dataframe.
  - `matplotlib` & `seaborn`: Para a criação de dashboards e visualizações gráficas.

---
*Este repositório faz parte do meu portfólio de Análise de Dados, demonstrando aplicação prática de Python para Inteligência de Negócios.*
