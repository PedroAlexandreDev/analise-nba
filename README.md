# 📊 NBA Player Data Analysis

Este projeto tem como objetivo analisar dados de jogadores da NBA utilizando Python e bibliotecas de visualização como Seaborn e Matplotlib. A análise cobre estatísticas como pontos, assistências, rebotes, anos de carreira, altura, peso, posição, universidade e draft.

## 🔍 Funcionalidades

- Top 10 jogadores com mais:
  - Pontos
  - Rebotes
  - Assistências
  - Participações médias (PTS + AST + REB)
- Jogadores com maior tempo de carreira
- Médias por posição:
  - Pontos
  - Assistências
  - Rebotes
  - Altura e peso
- Análise por altura:
  - Faixa de altura × rebotes
- Universidades com mais jogadores na NBA
- Número de jogadores draftados por ano
- Média de pontos por rodada do draft

## 🛠️ Tecnologias utilizadas

- Python 3
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Google Colab (recomendado para execução)

## 📁 Dados

Os dados foram utilizados a partir de um arquivo CSV com informações como:
- `PLAYER_FIRST_NAME`, `PLAYER_LAST_NAME`
- `PTS`, `AST`, `REB`
- `FROM_YEAR`, `TO_YEAR`
- `HEIGHT`, `WEIGHT`, `POSITION`
- `COLLEGE`, `DRAFT_YEAR`, `DRAFT_ROUND`

> Certifique-se de carregar o DataFrame `df` corretamente antes de executar os códigos de análise.

## ▶️ Como executar

1. Clone este repositório ou copie o código para um notebook.
2. Carregue o arquivo CSV com os dados dos jogadores.
3. Execute cada célula de análise para gerar os gráficos.
4. Os resultados serão exibidos diretamente no notebook.

```python
import pandas as pd
df = pd.read_csv("nba_players.csv")  # substitua pelo nome do seu arquivo
```
feito por pedro alexandre
