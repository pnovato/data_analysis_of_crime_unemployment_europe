# Análise de Correlação: Desemprego x Criminalidade na Europa
Este projeto analisa a relação entre as taxas de desemprego e os índices de criminalidade em capitais europeias, utilizando dados reais do Kaggle.

## Dados utilizados
- **Desemprego:** Unemployment in European Union (Kaggle)
- **Criminalidade:** Crime in Europe (Kaggle)

## Objetivo
Investigar se existe correlação entre as duas variáveis e visualizar os padrões por país e ano.

## Etapas realizadas
1. Importação dos dados via `kagglehub`
2. Transformação de dados (formato largo → longo)
3. Limpeza de valores ausentes e conversões
4. Agregação dos dados por país e ano
5. Cálculo da correlação e visualizações (scatter, heatmap)

## Conteúdo do repositório
- `notebook_english.ipynb`: versão em inglês
- `report_unemployment_crime_analysis_en.docx`: relatório
- `datasets/`: arquivos originais
- `README.md`: você está aqui

## Como executar o projeto
Para rodar este projeto, é necessário ter o **Jupyter Lab** instalado.

### Instalação recomendada (com virtualenv):

```bash
python -m venv myenv
source myenv/bin/activate  # ou myenv\Scripts\activate no Windows
pip install jupyterlab pandas seaborn matplotlib kaggle kagglehub
jupyter lab
```

Depois, abra o arquivo `notebook_portugues.ipynb` para iniciar.

---

# Correlation Analysis: Unemployment vs. Crime in Europe
This project investigates the relationship between unemployment rates and crime indices in European capitals, using real data from Kaggle.

## Datasets used
- **Unemployment:** Unemployment in European Union (Kaggle)
- **Crime:** Crime in Europe (Kaggle)

## Goal
To assess if there's a meaningful correlation between unemployment and crime, and visualize trends across countries and years.

## Steps
1. Data import via `kagglehub`
2. Data transformation (wide to long format)
3. Cleaning missing/invalid values
4. Aggregation by country and year
5. Correlation analysis and visualizations

## Repository contents
- `notebook_english.ipynb`: translated notebook
- `report_unemployment_crime_analysis_en.docx`: English report
- `datasets/`: original data
- `README.md`: this file

## How to run the project
You need **Jupyter Lab** installed to run this project.

### Recommended installation (with virtualenv):

```bash
python -m venv myenv
source myenv/bin/activate  # or myenv\Scripts\activate on Windows
pip install jupyterlab pandas seaborn matplotlib kaggle kagglehub
jupyter lab
```

Then, open the file `notebook_english.ipynb` or `notebook_portugues.ipynb` to get started.