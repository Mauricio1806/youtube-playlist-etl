# YouTube Playlist ETL and Dashboard 🚀

Este repositório contém um projeto de **coleta, tratamento e análise de dados de uma playlist do YouTube**, desenvolvido como parte de um **teste técnico**, utilizando **Python para ETL e Power BI para visualização de dados**.

## 🎯 Objetivo

✅ Coletar dados de uma playlist utilizando a **YouTube Data API v3** (dentro do GCP).  
✅ Tratar os dados em Python e exportar para CSV.  
✅ Construir um **dashboard interativo no Power BI**.  
✅ Contar uma história com os dados para facilitar decisões de marketing e conteúdo.

## 🛠️ Tecnologias Utilizadas

- Python (`pandas`, `google-api-python-client`)
- GCP (YouTube Data API)
- Power BI
- Git e GitHub

## ⚙️ Funcionamento do Projeto

### 1️⃣ Coleta de Dados (ETL)

O script em `src/youtube_playlist_collector.py` coleta:

- ID do vídeo
- Título
- Descrição
- Data de publicação
- Quantidade de likes
- Quantidade de views
- Quantidade de comentários
- URL da thumbnail

E exporta para `data/youtube_playlist_data.csv`.

### 2️⃣ Dashboard no Power BI

O arquivo `dashboard/youtube_dashboard.pbix` contém um dashboard com:

- Indicadores de views, likes, comentários e quantidade de artistas.
- Top 10 vídeos mais assistidos.
- Visualizações por artista.
- Evolução de visualizações ao longo do tempo.
- Tabela com miniaturas e links clicáveis.

### 3️⃣ Storytelling

A análise responde:
- Quais artistas performam melhor na playlist?
- Quais vídeos são mais assistidos?
- Como evoluem os engajamentos ao longo do tempo?
- Quais insights podem ajudar no planejamento de conteúdo no YouTube?

## 🚀 Como Executar Localmente

1️⃣ Clone o repositório:
```bash
git clone https://github.com/Mauricio1806/youtube-playlist-etl.git
cd youtube-playlist-etl

