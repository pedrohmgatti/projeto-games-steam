# (EN) Comparison Between Minimum Requirements and Actual Player Hardware

This project analyzes the compatibility between the minimum game requirements and the actual hardware of players, extracting and processing data to identify discrepancies and trends.

## ✅ Week 1: Data Collection (Completed)
1. Define detailed project scope:
    - Use popular and trending games
2. Research and select data sources:
    - Steam Hardware Survey and the list of popular games from CanYouRunIt
3. Extract GPU data from the Steam Hardware Survey
4. Extract VRAM data from the Steam Hardware Survey
5. Extract RAM data from the Steam Hardware Survey
6. Extract processor data from Intel’s website
7. Extract data from CanYouRunIt website

## ✅ Week 2: Data Processing (Completed)
1. Generate tables
2. Fix the system_requirements_website_data code (switch GPU and RAM columns)
3. Extract data from SystemRequirements website (will be used instead of CanYouRunIt)
5. Standardize GPU names using the Steam Hardware Survey as parameter
4. Standardize CPU names using the Intel website as parameter
6. Standardize RAM capacity using the Steam Hardware Survey as parameter

## ✅ Week 3: Exploratpry Data Analysis (Completed)
1. Convert reales_date to datetime
2. Join Market Share table and Game Requirements table
3. Extract benchmark data from Benchamarks website
4. Join Benchmark Score table and Game Requirements table
5. Create new tables

## 🔄 Week 4: Comparison of player hardware vs. game requirements (In Progress)
1. Modify the benchmark code to extract GPU data from notebooks
2. Changes in the processing code
    - Create a code to update/create tables
    - Merge benchmark scores into the GPU table
    - Modify the requirements table to include only the minimum and recommended benchmark scores
3. Most dominant graphics cards in the market
    - Which games they can run
    - How many games they can run

## 🔄 Week 5: Evolution of game requirements over time.

## 🔄 Week 6: Insights and predictions (player clusters, predictive models).

## 🔄 Week 7: Final report and interactive dashboard with Streamlit.

# ----------------------------------------------------------------

# (PT-BR) Comparação Entre Requisitos Mínimos e Hardware Real dos Jogadores

Este projeto analisa a compatibilidade entre os requisitos mínimos dos jogos e o hardware real dos jogadores, extraindo e processando dados para identificar discrepâncias e tendências.

## ✅ Semana 1: Coleta de dados (Concluída)
1. Definir escopo detalhado do projeto:
    - Utilizar jogos famosos e em alta.
2. Pesquisar e selecionar fontes de dados
    - Pesquisa de Hardware da Steam e a Lista de jogos populares do CanYouRunIt.
3. Extrair os dados de Placa de Vídeo da Pesquisa de Hardware da Steam
4. Extrair os dados de VRAM da Pesquisa de Hardware da Steam
5. Extrair os dados de RAM da Pesquisa de Hardware da Steam
6. Extrair os processadores no site da Intel
7. Extrair os dados dos dados do site CanYouRunIt

## ✅ Semana 2: Processamento dos dados (Concluída)
1. Generate tables
2. Correção o código system_requirements_website_data (trocar colunas de GPU e RAM)
3. Extrair os dados do site SystemRequirements (será usado ao invés do CanYouRunIt)
5. Padronizar os nomes de GPU utilizando a pesquisa de Harware da Steam
4. Padronizar os nomes de CPU utilizando o site da Intel como base
6. Padronizar a capacidade de RAM utilizando a pesquisa de Harware da Steam
 
## ✅ Semana 3: Análise exploratória dos Dados (Concluída)
1. Converter release_date para tipo datetime
2. Juntar a fatia de mercado nas tabelas de requerimento
3. Extrair os dados de benchmark do site Benchmarks
4. Juntar as pontuações de benchmark nas tabelas de requerimento
5. Construir tabelas auxiliares

## 🔄 Semana 4: Comparação do hardware dos jogadores vs. requisitos dos jogos (Em Andamento)
1. Alteração no código de benchmark para extrair GPU de notebooks
2. Alterações no código de processamento
    - Criar um código para atualizar/criar tabelas
    - Juntar as pontuações de benchmark na tabela de GPU
    - Alterar a tabela de requerimentos para que ela contenha apenas a pontuação mínima e recomendada de benchmark
    - Salvar novas tabelas
3. Placas mais dominantes no mercado
    - Quais jogos elas conseguem rodar
    - Quantos jogos elas conseguem rodar

## 🔄 Semana 5: Evolução dos requisitos ao longo do tempo.

## 🔄 Semana 6: Insights e predições (clusters de jogadores, modelos preditivos).

## 🔄 Semana 7: Relatório final e dashboard interativo com Streamlit.