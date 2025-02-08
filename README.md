# Análise de Dados de Aluguéis - Case Lighthouse

Este repositório contém uma análise exploratória de dados (EDA) aplicada a um conjunto de dados de aluguéis, com foco em entender padrões de preço, disponibilidade e melhores locais para investimento em hospedagens.

## 📌 Descrição do Projeto

O objetivo deste projeto é extrair insights relevantes sobre o mercado de aluguéis de curto prazo, respondendo questões como:

- Quais são os melhores locais para investir em um apartamento?
- O tempo mínimo de estadia e a disponibilidade anual influenciam no preço?
- Existe algum padrão nos títulos dos imóveis mais caros?
- Como prever o preço de um imóvel com base em suas características?

## 📊 Análise Explorátoria (EDA)

A exploração dos dados envolveu:

- Limpeza e verificação de valores ausentes
- Visualização de distribuições de preço, disponibilidade e localização
- Criação de uma métrica chamada **preco\_por\_disponibilidade**, utilizada em um heatmap geoespacial
- Análise de correlações entre variáveis

## 🤖 Modelagem Preditiva

A previsão do preço foi tratada como um problema de regressão, utilizando modelos de machine learning. Os modelos foram avaliados pelas métricas **R², MSE e RMSE**, garantindo uma análise quantitativa da performance.

## 🚀 Como Acessar o Notebook

Para visualizar o código e as análises, acesse o notebook **`Case_Lighthouse.ipynb`** diretamente no GitHub ou execute localmente usando Jupyter Notebook:

```bash
jupyter notebook Case_Lighthouse.ipynb
```

## 🏗️ Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- XGBoost
