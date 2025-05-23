# 📊 NBA Player Data Analysis

Este projeto realiza uma análise exploratória de dados (EDA) sobre jogadores da NBA utilizando Python. Com base em um dataset contendo estatísticas e informações gerais dos atletas, são gerados gráficos para responder perguntas como:

- Quem são os maiores pontuadores?
- Quais posições contribuem mais com assistências e rebotes?
- Quais jogadores tiveram as carreiras mais longas?
- Como altura influencia os rebotes?

## 🔧 Tecnologias utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab (recomendado para execução)

## 📁 Dados utilizados

O dataset deve conter colunas como:

- `PLAYER_FIRST_NAME`, `PLAYER_LAST_NAME`
- `PTS` (Pontos), `AST` (Assistências), `REB` (Rebotes)
- `POSITION`, `HEIGHT`, `WEIGHT`
- `FROM_YEAR`, `TO_YEAR`
- `DRAFT_YEAR`, `DRAFT_ROUND`
- `COLLEGE`

> Certifique-se de carregar o DataFrame com o nome `df` para que os scripts funcionem corretamente.

## 📈 Análises realizadas

### 🏀 Desempenho individual

- **Top 10 jogadores com mais pontos**
- **Top 10 jogadores com mais rebotes**
- **Top 10 jogadores com mais assistências**
- **Top 10 jogadores com mais participações médias** (soma de pontos, assistências e rebotes)

### 🧓 Longevidade na NBA

- **Top 10 jogadores com mais anos de carreira**  
  Calculado com base em `FROM_YEAR` e `TO_YEAR`.

### 🧠 Análises por posição

- **Média de pontos por posição**
- **Média de assistências por posição**
- **Média de rebotes por posição**
- **Altura média por posição**
- **Peso médio por posição**

### 📏 Altura e rebotes

- Agrupamento por faixas de altura (`160-169 cm`, `170-179 cm`, etc.)
- Cálculo da média de rebotes por faixa

### 🎓 Formação e draft

- **Top 10 universidades com mais jogadores**
- **Número de jogadores draftados por ano**
- **Média de pontos por rodada do draft**

## ▶️ Como rodar

## Instale as dependências (em um ambiente com Python 3):

```bash
pip install pandas matplotlib seaborn
```

    Top 10 pontuadores

    Altura média por posição

    Jogadores com mais anos de carreira

## 💡 Melhorias futuras

    Adicionar análise por temporada

    Incluir gráficos interativos com Plotly ou Streamlit

    Criar dashboard completo com filtros

👨‍💻 Autor

Desenvolvido por pedro alexandre.
Este projeto é ideal para compor portfólio de análise de dados com Python, focado em visualização e insights a partir de dados reais do esporte.

