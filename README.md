# 🏥 Health Data Analysis | Clamed Data Insights

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Visão Geral

Este projeto realiza uma análise exploratória e tratamento de dados de saúde, com foco em gerar insights estratégicos sobre:

- Perfil dos pacientes  
- Custos hospitalares  
- Eficiência operacional  

A base foi fornecida no contexto da empresa fictícia **Clamed Data Insights**, simulando um cenário real de análise de dados no setor de saúde.

---

## 🎯 Objetivo do Projeto

Transformar dados brutos em informações úteis para tomada de decisão, através de:

- Limpeza e tratamento de dados  
- Correção de inconsistências  
- Análise exploratória (EDA)  
- Identificação de padrões e tendências  

---

## 📊 Dataset

- 📁 Arquivo: `healthcare_dataset.csv`  
- 📌 Registros: 55.500 linhas  
- 📌 Variáveis: 15 colunas  

### Principais campos:

- 👤 Paciente: Nome, Idade, Gênero, Tipo sanguíneo  
- 🏥 Médico: Condição, Médico, Hospital  
- 💰 Financeiro: Valor de faturamento  
- 📅 Datas: Admissão e Alta  
- 💊 Tratamento: Medicação e Resultados  

---

## 🧠 Etapas da Análise

### 🔹 1. Importação e Exploração
- Leitura com `pandas`
- `head()`, `info()`, `describe()`

### 🔹 2. Limpeza de Dados
- Remoção de duplicados (534 registros)
- Padronização de nomes
- Conversão de datas
- Correção de valores inconsistentes

💡 Valores negativos em faturamento foram substituídos pela média por condição médica.

### 🔹 3. Análise Exploratória (EDA)
- Estatísticas descritivas  
- Boxplot para outliers  

---

## 📈 Insights

- Idade média: ~51 anos  
- Faturamento médio: ~25.5 mil  
- Base final limpa e pronta para análise  

---

## 🛠️ Tecnologias

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 Como Executar

```bash
git clone https://github.com/natiruhling/mini_projeto_clamed.git
cd mini_projeto_clamed
pip install pandas numpy matplotlib seaborn
jupyter notebook
```

---

## 👩‍💻 Autora

Nathália Rühling Rocha
Data Analyst em formação
