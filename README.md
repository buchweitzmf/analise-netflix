# 🎬 Análise de Catálogo — Netflix

## Sobre o Projeto
Análise exploratória do catálogo da Netflix com o objetivo de identificar 
padrões de produção de conteúdo por país, gênero e período.

## Ferramentas Utilizadas
- SQL (PostgreSQL)
- Python + Pandas
- Jupyter Notebook
- Power BI

## Perguntas Respondidas
- Quantos filmes e séries tem no catálogo?
- Quais os 10 países que mais produzem conteúdo?
- Quantos títulos foram adicionados por ano?
- Quais são os gêneros mais comuns?

## Principais Insights
- **Estados Unidos** lidera com folga — quase 3x mais títulos que a Índia em segundo lugar
- **Filmes representam mais que o dobro** de séries no catálogo (6.131 vs 2.676)
- O catálogo cresceu fortemente entre **2016 e 2019**, com pico em 2019 e queda nos anos seguintes
- **Documentários** são o segundo gênero mais comum — surpreendente para uma plataforma de entretenimento

## Dataset
Dataset disponível no Kaggle: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Como Executar
1. Clone o repositório
2. Configure o PostgreSQL e importe o CSV para a tabela `db_netflix.sql`

3. Abra o arquivo `netflix_db.ipynb` no Jupyter
4. Execute as células em ordem
5. O dashboard está disponível em `netflix-analytics.pbix`

## Dashboard
<img width="1764" height="990" alt="image" src="https://github.com/user-attachments/assets/46939d81-3c3c-40cd-a7e7-f7569a3d099a" />

