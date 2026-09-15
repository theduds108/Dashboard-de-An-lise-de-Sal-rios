# 📊 Dashboard de Análise de Salários na Área de Dados

Dashboard interativo em **Streamlit** para explorar salários na área de dados, com filtros dinâmicos e visualizações construídas com **Plotly**.

## Funcionalidades

- Filtros por ano, senioridade, tipo de contrato e tamanho da empresa
- KPIs de salário médio, salário máximo, total de registros e cargo mais frequente
- Gráficos de top cargos por salário médio e distribuição salarial
- Análise de proporção de trabalho remoto

## Stack

Python · Streamlit · Pandas · Plotly

## Como rodar localmente

```bash
git clone https://github.com/theduds108/Dashboard-de-An-lise-de-Sal-rios.git
cd Dashboard-de-An-lise-de-Sal-rios
pip install -r requirements.txt
streamlit run app.py
```

## Fonte dos dados

Os dados são carregados de um CSV público com registros salariais anônimos da área de dados (cargo, senioridade, tipo de contrato, tamanho da empresa e salário em USD).
