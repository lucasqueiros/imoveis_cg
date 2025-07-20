# 🏠 Imóveis CG - Análise Estatística do Mercado Imobiliário de Campina Grande

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/status-em_desenvolvimento-yellow)

## 📋 Sobre o Projeto

Este repositório contém uma análise estatística abrangente do mercado imobiliário de Campina Grande - PB, desenvolvida através de web scraping e análise de dados. O objetivo principal é entender padrões de preços, características dos imóveis e tendências do mercado local, servindo como base para futuros modelos preditivos de precificação.

## 🎯 Objetivos

- **Coleta e Raspagem de dados**: Coletar e tratar dados de apartamentos disponiveis no site da [ZapImoveis](www.zapimoveis.com.br) na cidade de Campina Grande
- **Análise Descritiva**: Compreender o panorama atual do mercado imobiliário local
- **Identificação de Padrões**: Descobrir relações entre características dos imóveis e preços
- **Preparação de Dados**: Estruturar dados para modelagem preditiva
- **Visualizações**: Criar dashboards e gráficos informativos
- **Modelos Preditivos**: (Futuro) Desenvolver algoritmos para predição de preços

## 📊 Estrutura dos Dados

O projeto trabalha com as seguintes informações dos imóveis:
- **Localização**: Bairro, endereço
- **Características Físicas**: Área, quartos, banheiros, vagas
- **Preços**: Valor de venda, condomínio, IPTU

## 🗂️ Estrutura do Repositório

```
imoveis_cg/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   ├── raw/                    # Dados brutos
│   │   ├── links_imoveis.csv
│   │   └── imoveis.json
│   ├── processed/              # Dados processados
│   │   └── imoveis_processados.csv
├── notebooks/
│   ├── 01_web_scraping.ipynb           # Coleta de dados
│   ├── 02_data_cleaning.ipynb          # Limpeza e preparação
│   ├── 03_exploratory_analysis.ipynb   # Análise exploratória
│   └── 04_statistical_analysis.ipynb   # Análise estatística
├── src/
│   ├── __init__.py
│   ├── scraping/
│   │   ├── __init__.py
│   │   ├── scraper.py          # Funções de web scraping
│   │   └── utils.py            # Utilitários para scraping
│   ├── data_processing/
│   │   ├── __init__.py
│   │   ├── cleaner.py          # Limpeza de dados
│   │   └── preprocessor.py     # Pré-processamento
│   ├── analysis/
│   │   ├── __init__.py
│   │   ├── statistics.py       # Análises estatísticas
│   │   └── visualizations.py   # Visualizações
│   └── models/                 # (Futuro) Modelos preditivos
│       ├── __init__.py
│       ├── price_predictor.py
│       └── feature_engineering.py
├── reports/
│   ├── figures/                # Gráficos e visualizações
│   ├── statistical_report.md   # Relatório de análise
│   └── market_insights.md      # Insights do mercado
├── config/
│   ├── __init__.py
│   └── settings.py             # Configurações do projeto
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**: Linguagem principal
- **Pandas**: Manipulação e análise de dados
- **NumPy**: Computação numérica
- **Matplotlib/Seaborn**: Visualização de dados
- **Plotly**: Visualizações interativas
- **Selenium**: Web scraping
- **Jupyter Notebook**: Desenvolvimento e análise
- **Scikit-learn**: (Futuro) Machine learning
- **Statsmodels**: Análises estatísticas avançadas

## 📈 Principais Análises

- **Distribuição de Preços**: Análise por bairro, tipo de imóvel
- **Correlações**: Relação entre área, quartos e preço
- **Tendências Temporais**: Evolução dos preços ao longo do tempo
- **Análise Geoespacial**: Mapeamento de preços por região
- **Outliers**: Identificação de imóveis com preços atípicos

## 📊 Resultados Principais

> 📝 **Nota**: Esta seção será atualizada conforme as análises forem concluídas

- Preço médio por m² em Campina Grande: R$ XXX
- Bairros com maior valorização: [A definir]
- Características que mais impactam no preço: [A definir]

## 🔮 Roadmap

- [x] Coleta inicial de dados (web scraping)
- [x] Análise exploratória básica
- [x] Limpeza e tratamento completo dos dados
- [ ] Análise estatística avançada
- [ ] Visualizações interativas
- [ ] Relatório final de insights
- [ ] Modelo preditivo de preços (Fase 2)
- [ ] API para consulta de preços estimados (Fase 2)
- [ ] Dashboard web interativo (Fase 2)

-----
⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!