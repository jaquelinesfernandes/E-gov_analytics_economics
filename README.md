# 📊 E-Gov Analytics: 

Este projeto tem como objetivo analisar dados de gastos públicos disponibilizados pelo banco mundial de um país, com foco em analise e verificar a correlação entre gastos com educação e saúde influenciam no aumento do PIB.

## 🗂 Fonte dos Dados

Os dados utilizados foram extraídos do portal API fornecida pelo Banco Mundial no endereço abaixo:
http://api.worldbank.org/v2/en/country.

Extraído dados de um dos países no período de 2003 a 2019 e ajustado os nomes dascolunas.

## 🛠 Principais Ferramentas Utilizadas

- **Python 3.10**
- **Pandas**: manipulação e limpeza de dados
- **Matplotlib & Seaborn**: visualização gráfica
- **Plotly**: gráficos interativos
- **Scikit-learn (sklearn)**: aplicação de modelo de regressão linear
- **Jupyter Notebook / Google Colab**: ambiente de desenvolvimento e execução

## 🧹 Tratamento e Limpeza dos Dados

- Tratamento de valores ausentes:
  - Interpolação: preenchimento com a média dos valores
  - Backfilling: preenchendo com valores anteriores
- Remoção de colunas não necessárias
- Conversão de tipos de dados (valores monetários)

## 📁 Análise de Dados
- Análise de PIB Per Capita
- Análise de Despesas

## 📈 Resultados Obtidos

- Identificação de padrões de execução orçamentária ao longo dos anos
- Visualização da proporção entre valores empenhados, liquidados e pagos
- Análise comparativa entre diferentes órgãos e tipos de despesa
- Aplicação de **Regressão Linear** para prever valores de pagamento com base nos valores liquidados
- Avaliação da performance do modelo com métricas como R² e erro médio absoluto
- Gráficos interativos que facilitam a compreensão dos dados



## 👩‍💻 Autoria

Projeto desenvolvido por [Jaqueline Fernandes](https://github.com/jaquelinesfernandes)

---
