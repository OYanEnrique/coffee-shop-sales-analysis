[Read in English](README.md)

---

# Análise de Vendas de uma Rede de Cafeterias

Este projeto realiza uma análise exploratória dos dados de vendas (EDA) de uma cafeteria, cobrindo o período de Janeiro a Junho de 2023. O objetivo é extrair insights acionáveis para a gestão do negócio através da análise de faturamento, produtos e padrões de consumo.

## 🎯 Objetivo

A análise busca responder a 3 perguntas de negócio chave:
1.  Quais são os meses de maior e menor faturamento?
2.  Quais são as categorias de produtos mais vendidas?
3.  Em quais dias da semana a cafeteria vende mais?

## 🛠️ Ferramentas Utilizadas
* **Python** como linguagem de programação
* **Pandas** para limpeza e manipulação dos dados
* **Matplotlib** e **Seaborn** para criação de visualizações
* **Jupyter Notebook / Google Colab** como ambiente de desenvolvimento

## 📊 Fonte dos Dados
Os dados utilizados neste projeto são públicos e foram obtidos através da plataforma Kaggle. Você pode acessá-los pelo link abaixo:
* **Dataset:** [Coffee Sales no Kaggle](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)

## 🚀 Como Executar o Projeto
1.  Clone ou faça o download deste repositório.
2.  Baixe o conjunto de dados a partir do [link do Kaggle](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales) informado acima.
3.  Coloque o arquivo `.xlsx` na mesma pasta do projeto.
4.  Abra o notebook `analise_de_vendas_cafeteria.ipynb` para visualizar e executar a análise completa.

## 📈 Análise e Insights

### 1. Faturamento por Mês
![Faturamento por Mês](faturamento_por_mes_pt.png)

**Insight:** O faturamento cresceu de forma consistente de Janeiro a Maio, atingindo o pico do semestre. Junho teve uma leve queda, sugerindo uma oportunidade para investigar e talvez criar campanhas de marketing para sustentar o crescimento no início do segundo semestre.

### 2. Categorias de Produtos Mais Vendidos
![Produtos Mais Vendidos](produtos_mais_vendidos_pt.png)

**Insight:** Café é a categoria líder absoluta, confirmando o produto principal do negócio. Chá e Padaria são os próximos mais populares, indicando um grande potencial para a criação de vendas casadas (combos) para aumentar o ticket médio por cliente.

### 3. Vendas por Dia da Semana
![Vendas por Dia da Semana](vendas_por_dia_pt.png)

**Insight:** A cafeteria possui um movimento forte e constante durante todos os dias da semana, com um pico nas segundas-feiras. O sábado, por ter uma leve queda, representa uma oportunidade para promoções específicas (como um "Brunch de Sábado") para impulsionar o fluxo de clientes.
