⚽ PREVISÕES LEAGUE

**Sistema de análise preditiva focado em estatísticas de jogadores da Premier League 2024.**

## Sobre o projeto

O **Previsões League** é um dashboard interativo que consome dados reais do campeonato inglês para apresentar rankings e probabilidades matemáticas de eventos por partida (como gols, faltas e cartões).

O foco deste projeto foi construir o fluxo completo da informação de ponta a ponta. A lógica preditiva não utiliza ferramentas de IA prontas, mas sim cálculos estatísticos e de lógica de programação diretos, baseados no histórico de performance de cada atleta.

Neste repositório, disponibilizamos todo o código-fonte da solução, separando as responsabilidades de extração de dados, armazenamento, backend e interface.

## Tecnologias e Conceitos Aplicados

* **Extração e Tratamento (ETL):** Python e Pandas
* **Banco de Dados Relacional:** PostgreSQL
* **Backend:** API REST desenvolvida com FastAPI
* **Frontend:** Dashboard dinâmico construído com Streamlit
* **Lógica Aplicada:** Matemática estatística e manipulação de dados reais

## Estrutura do Repositório

O código está organizado da seguinte forma:
* `/etl`: Scripts responsáveis por buscar os dados via API externa e realizar a limpeza.
* `/database`: Arquivos de configuração e persistência no banco relacional.
* `/api` e `/services`: Rotas e estruturação das regras de negócio do backend.
* `app.py`: Aplicação principal responsável por renderizar o frontend.

## Equipe do projeto

* Allan Patrick Fantoni Filho
* Miguel Miceli
