# 📊 Netflix Titles Exploratory Data Analysis | Análise Exploratória dos Títulos da Netflix

This project performs an exploratory data analysis (EDA) on a dataset containing titles available on Netflix. 
It uses `pandas`, `matplotlib`, and `seaborn` to explore features such as content type, country of origin, release year, and movie duration.

---

## 📁 Dataset | Dados

- File: `netflix_titles.csv`
- Source: [Netflix Dataset (Kaggle)](https://www.kaggle.com/shivamb/netflix-shows)

---

## 🚀 Requirements | Requisitos

- Python 3.x
- pandas
- matplotlib
- seaborn

Install the required packages with:

```bash
pip install pandas matplotlib seaborn
```

---

## 📈 What the Script Does | O que o Script Faz

### In English:

1. Loads data from the CSV file.
2. Displays the first rows for initial inspection.
3. Shows general info and descriptive statistics.
4. Checks for missing values.
5. Generates plots for:
   - Release year distribution
   - Distribution between movies and TV shows
   - Top 10 countries with the most titles
   - Movie durations
   - Number of movies released per year
   - Number of TV shows released per year

### Em Português:

1. Carrega os dados do arquivo CSV.
2. Exibe as primeiras linhas para visualização inicial.
3. Mostra informações gerais e estatísticas descritivas.
4. Verifica valores nulos.
5. Cria gráficos de:
   - Distribuição de anos de lançamento
   - Distribuição entre filmes e séries
   - Top 10 países com mais títulos
   - Duração dos filmes
   - Quantidade de filmes por ano
   - Quantidade de séries por ano

---

## 📊 Example Plots | Exemplos de Gráficos

- Release Year Histogram | Histograma de Anos de Lançamento
- Bar Chart: Movies vs TV Shows | Gráfico de Barras: Filmes vs Séries
- Top 10 Countries with Most Titles | Top 10 Países com Mais Títulos
- Movie Duration Distribution | Distribuição da Duração dos Filmes
- Releases per Year | Lançamentos por Ano

---

## 🧠 Notes | Observações

- The `duration` column is processed to extract duration in minutes only for movies.
- The data may contain null values and inconsistencies that should be addressed in further analysis.

---

## 👤 Author | Autor

Jessica Wolfie  
[LinkedIn](#) | [GitHub](#)