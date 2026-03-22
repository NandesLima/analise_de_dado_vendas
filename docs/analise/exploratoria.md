# 📊 Análise Exploratória de Dados (EDA)

Toda a nossa análise foi conduzida dentro de um ambiente Jupyter Notebook, utilizando as bibliotecas `pandas` para manipulação de dados e `matplotlib` para visualização gráfica.

## 🔗 Acesso ao Notebook Original

Para visualizar o código fonte interativo, gerar os gráficos e observar a lógica de extração de dados passo a passo (como a criação das colunas de Custo, Lucro e Tempo de Envio):

👉 **[Abrir Notebook no GitHub](https://github.com/NandesLima/analise_de_dado_vendas/blob/master/notebooks/analise-exploratoria.ipynb)**

### 🛠️ Principais Técnicas Utilizadas no Notebook

1. **Limpeza e Criação de Features:**
   - Criação da coluna de **Custo Total** (`Custo Unitário` * `Quantidade`).
   - Criação da coluna de **Lucro** (`Valor Venda` - `Custo Total`).
   - Criação da coluna **Tempo de Envio** (diferença entre `Data Envio` e `Data Venda`).

2. **Agregações e Respostas:**
   - Cálculo do Lucro Total Geral e Custo Total Geral.
   - Agrupamento de tempo de envio médio por *Marca*.
   - Verificação de valores ausentes (Missing Values).
   - Lucro Anual e Mensal.

3. **Visualizações Gráficas:**
   - Gráficos de barras horizontais para o Total de Produtos Vendidos.
   - Boxplots para analisar a distribuição do Tempo de Envio e identificar *Outliers*.
   - Histograma para o Tempo de Envio.

---

*Nota: O dataset original `AdventureWorks.xlsx` está localizado na pasta `data/` do repositório para replicação dos estudos.*
