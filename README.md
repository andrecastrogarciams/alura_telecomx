# Projeto TelecomX Data Analysis

Este repositório contém um notebook em Google Colab para realização de uma análise exploratória de churn de clientes da TelecomX, cobrindo etapas de extração, limpeza, transformação e visualização de dados.

---

## 📝 Descrição

O objetivo deste projeto é demonstrar um pipeline completo de dados, desde a extração via API até a geração de insights através de visualizações e clusterização de perfis de clientes. Inclui ainda abordagens de EDA (Análise Exploratória de Dados) e segmentação via K-Means.

## 📥 Fonte de Dados

Os dados são disponibilizados em formato JSON no GitHub:

```
https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json
```

O dicionário de dados principal inclui campos como:

* `customerID` – ID único do cliente
* `Churn` – indicador de cancelamento (Yes/No)
* `tenure` – meses de contrato
* `MonthlyCharges` – faturamento mensal
* `TotalCharges` – faturamento total
* Várias assinaturas de serviços adicionais (ex.: OnlineSecurity, StreamingTV, etc.)

## 🛠️ Pré-requisitos

* Conta no Google (para usar o Colab)
* Acesso à internet para leitura do JSON
* Bibliotecas Python: `pandas`, `scikit-learn`, `matplotlib`

## 📋 Estrutura do Notebook

1. **Etapa 1: Carregamento e Flattening**
2. **Etapa 2: Inspeção Inicial**
3. **Etapa 3: Limpeza e Transformação**
4. **Etapa 4: Análise Exploratória**

## 🚀 Como Executar

1. Abra o notebook TelecomX.ipynb no Google Colab.
2. Certifique-se de ter as bibliotecas instaladas (executar a célula de instalação, se necessário).
3. Execute cada célula em ordem, acompanhando as saídas e gráficos.
4. Para explorar outras visões, modifique parâmetros (número de clusters, profundidade de modelo, etc.).

## 💡 Próximos Passos

* Implementar modelos preditivos (Logistic Regression, Random Forest) para prever churn.
* Criar dashboards interativos com Plotly ou Power BI.
* Automatizar o pipeline usando Airflow ou scripts Python.

---

### Autor

André Castro Garcia – Coordenador de Tecnologia e Análise de Dados

---


