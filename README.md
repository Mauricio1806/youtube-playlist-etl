# YouTube Playlist ETL and Dashboard 🚀

Este repositório contém um projeto de coleta, tratamento e análise de dados de uma playlist do YouTube, desenvolvido como parte de um teste técnico, utilizando **Python para ETL** e **Power BI para visualização de dados**.

---

## 🎯 Objetivo

- Coletar dados de uma playlist utilizando a **YouTube Data API v3**.
- Tratar os dados e exportar para **CSV**.
- Construir um **dashboard interativo no Power BI**.
- Contar uma história com os dados para facilitar decisões de marketing e conteúdo.

---

## 🛠️ Tecnologias Utilizadas

- Python (pandas, google-api-python-client)
- Power BI
- Git e GitHub

---

## ⚙️ Como funciona o projeto

**Coleta de Dados**  
O script em `src/youtube_playlist_collector.py` coleta:
- ID do vídeo
- Título
- Descrição
- Data de publicação
- Quantidade de likes
- Quantidade de views
- Quantidade de comentários
- URL da thumbnail

e exporta para `data/youtube_playlist_data.csv`.

**Dashboard no Power BI**  
Em `dashboard/youtube_dashboard.pbix`, foi construído um dashboard com:
- Indicadores de views, likes, comentários e quantidade de artistas.
- Top 10 vídeos mais assistidos.
- Visualizações por artista.
- Evolução de visualizações ao longo do tempo.
- Tabela com miniaturas e links clicáveis.

**Storytelling**  
A análise responde:
- Quais artistas performam melhor na playlist?
- Quais vídeos são mais assistidos?
- Como evoluem os engajamentos ao longo do tempo?
- Quais insights podem ajudar no planejamento de conteúdo no YouTube?

---

## 🚀 Como executar localmente

Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/youtube-playlist-etl.git
