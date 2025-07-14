<div align="center">

# 📈 Python Insights

### Análise de Cancelamento de Clientes

![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Plots-3f4f75?logo=plotly)

</div>

---

<p align="center">
  <b>Projeto de análise de dados para identificar os principais motivos de cancelamento de clientes e propor ações para redução da inatividade.</b>
</p>

---

## 📑 Sumário

- [📊 Sobre o Projeto](#-sobre-o-projeto)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [🗂️ Estrutura do Projeto](#️-estrutura-do-projeto)
- [🧩 Padrões e Boas Práticas](#-padrões-e-boas-práticas)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [⚙️ Configurações](#️-configurações)
- [📈 Resultados Esperados](#-resultados-esperados)
- [📚 Referências](#-referências)
- [👤 Autor](#-autor)

---

## 📊 Sobre o Projeto

Este projeto utiliza Python e bibliotecas de análise de dados para explorar e visualizar informações sobre cancelamentos de clientes de uma empresa. O objetivo é fornecer insights que ajudem a empresa a entender e mitigar o churn.

---

## 🛠️ Tecnologias Utilizadas

- <b>Python 3.11+</b>
- <b>Jupyter Notebook</b> (`.ipynb`)
- <b>Pandas</b> — Manipulação e análise de dados tabulares
- <b>Plotly</b> — Visualização interativa de dados
- <b>Numpy</b> — Operações numéricas
- <b>Openpyxl</b> — Leitura/escrita de arquivos Excel
- <b>nbformat</b> & <b>ipykernel</b> — Suporte ao ambiente Jupyter

---

## 🗂️ Estrutura do Projeto

```
python_analise_dados/
├── cancelamentos.csv      # Base de dados principal (59MB)
├── inicial.ipynb          # Notebook com toda a análise e visualizações
└── README.md              # Este arquivo
```

---

## 🧩 Padrões e Boas Práticas

- <b>Notebook Modular</b>: Cada etapa da análise está separada em células, facilitando a leitura e reprodutibilidade.
- <b>Data Cleaning</b>: Remoção de colunas desnecessárias e tratamento de valores ausentes.
- <b>Visualização Exploratória</b>: Uso de histogramas para análise de variáveis relevantes.
- <b>Reprodutibilidade</b>: Todas as dependências podem ser instaladas via `pip` e o notebook pode ser executado sequencialmente.

---

## 🚀 Como Executar o Projeto

1. <b>Clone o repositório e acesse a pasta:</b>
   ```bash
   git clone <url-do-repo>
   cd python_analise_dados
   ```
2. <b>(Opcional) Crie um ambiente virtual:</b>
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate     # Windows
   ```
3. <b>Instale as dependências:</b>
   ```bash
   pip install pandas plotly openpyxl numpy nbformat ipykernel
   ```
4. <b>Abra o Jupyter Notebook:</b>
   ```bash
   jupyter notebook inicial.ipynb
   ```
5. <b>Execute as células do notebook sequencialmente para reproduzir a análise.</b>

---

## ⚙️ Configurações

- Certifique-se de que o arquivo <b>`cancelamentos.csv`</b> está na mesma pasta do notebook.
- O notebook foi desenvolvido para rodar em Python 3.11+, mas pode funcionar em versões anteriores do Python 3.

---

## 📈 Resultados Esperados

- Estatísticas descritivas sobre cancelamentos
- Visualizações interativas para identificar padrões de churn
- Insights para tomada de decisão

---

## 📚 Referências

- [Documentação Pandas](https://pandas.pydata.org/)
- [Documentação Plotly](https://plotly.com/python/)
- [Jupyter](https://jupyter.org/)

---

## 👤 Autor
by **Rodolfo M. F. Abreu**

