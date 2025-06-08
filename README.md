# 📊 Sinapi-analysis

Este projeto realiza o tratamento, análise exploratória e visualização de dados do SINAPI (Sistema Nacional de Pesquisa de Custos e Índices da Construção Civil), obtidos a partir da API do IBGE.

---

## 🔍 Objetivo

Explorar dados de custos da construção civil fornecidos pelo SINAPI, aplicando boas práticas de organização, limpeza, visualização e apresentação de relatórios, utilizando Python e Jupyter Notebooks.

---

## 🗂️ Estrutura do Projeto

```
Sinapi-analysis/
├── data/
│   ├── raw/              # Dados brutos originais (sinapi.csv)
│   └─── processed/        # Dados limpos e prontos para análise
│
├── notebooks/
│   ├── 01_tratamento_dados.ipynb         # Limpeza e preparação
│   ├── 02_analise_exploratoria.ipynb     # EDA com gráficos
│   └── 03_relatorio_final.ipynb          # Relatório com conclusões
│
├── scripts/
│   ├── limpeza.py        # Funções para limpeza de dados
│   ├── visualizacao.py   # Funções para geração de gráficos
│   └── utils.py          # Funções auxiliares diversas
│
├── reports/              # Relatórios finais (HTML, PDF, etc.)
│
├── requirements.txt      # Bibliotecas Python utilizadas
└── README.md             # Documentação do projeto
```

---

## 📦 Requisitos

Instale as dependências do projeto com:

```bash
pip install -r requirements.txt
```

---

## 🚀 Como usar

1. Coloque os dados brutos em `data/raw/` (`sinapi.csv`)
2. Execute os notebooks em ordem:
   - `01_tratamento_dados.ipynb` → gera dados tratados em `data/processed/`
   - `02_analise_exploratoria.ipynb` → gera gráficos e estatísticas
   - `03_relatorio_final.ipynb` → organiza os principais gráficos com conclusões
3. Os resultados finais estarão em `reports/`

---

## 📊 Ferramentas utilizadas

- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)

---

## 🏛️ Fonte dos dados

Os dados utilizados são provenientes da [API pública do IBGE](https://servicodados.ibge.gov.br/api/docs/), especificamente da base do SINAPI.

---

## 📌 Licença

Este projeto é livre para fins educacionais e analíticos.
