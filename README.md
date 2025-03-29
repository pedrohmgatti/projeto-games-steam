# **EN**
# **Comparison Between Minimum Requirements and Actual Player Hardware**

This project aims to perform a descriptive analysis and compare the Minimum and Recommended Requirements of a list of games. Additionally, it seeks to draw conclusions about the optimization of the most recent titles. For this initial study, the analysis focused exclusively on NVIDIA GPUs, considering that this is the most expensive component of a gaming PC.

The project was structured into three main stages: **Data Extraction, Data Processing, and Exploratory Analysis**.

## Data Extraction
- Web scraping was performed using the Selenium library.
- Game requirements were extracted from the *System Requirements* website.
- GPU benchmark scores were obtained from the *Benchmarks* website.
- Player hardware data was collected from the Steam hardware survey.

## Data Processing
- Standardization of GPU names.
- Creation of organized tables based on the extracted data.
- Cleaning and structuring of information to ensure analysis consistency.

## Exploratory Analysis
- Development of visualizations to interpret each game's requirements.
- Verification of GPU compatibility with minimum and recommended requirements.
- Evaluation of the optimization of the most recent games based on the collected data.

With this approach, the study aims to better understand the relationship between hardware requirements and the actual performance of GPUs in the latest games.

# About the project

The project lasted for a month, with the extraction phase being the most challenging. At first, I struggled since I had never worked with Web Scraping before. However, throughout the project, I learned the fundamentals of the Selenium library and managed to achieve a satisfactory result.

During the processing phase, several functions were applied to standardize names and create new tables, which proved to be very useful for exploratory data analysis. However, this stage also significantly reduced the volume of game data, making the analysis more concise than I had hoped.

Finally, the exploratory data analysis phase was where I felt most comfortable, as I have been focusing my theoretical and practical studies on this area since last year. However, as mentioned earlier, the reduction in data limited the number of insights I could generate.

In summary, developing this project was an enriching experience. From data extraction to the final analysis, I had the opportunity to practice and enhance my skills, especially when it comes to games a topic I am passionate about and could talk about for hours.

---

# **PT-BR**
# **Comparação Entre Requisitos Mínimos e Hardware Real dos Jogadores**

Este projeto tem como objetivo realizar uma análise descritiva e comparar os Requisitos Mínimos e Recomendados de uma lista de jogos. Além disso, busca tirar conclusões sobre a otimização dos títulos mais recentes. Para este estudo inicial, a análise focou exclusivamente em GPUs da NVIDIA, considerando que este é o componente mais caro de um PC gamer.

O projeto foi estruturado em três principais etapas: **Extração de Dados, Processamento de Dados e Análise Exploratória**.

## Extração de Dados
- Web scraping foi realizado utilizando a biblioteca Selenium.
- Os requisitos dos jogos foram extraídos do site *System Requirements*.
- Os benchmarks das GPUs foram obtidos no site *Benchmarks*.
- Os dados de hardware dos jogadores foram coletados na pesquisa de hardware da Steam.

## Processamento de Dados
- Padronização dos nomes das GPUs.
- Criação de tabelas organizadas com base nos dados extraídos.
- Limpeza e estruturação das informações para garantir a consistência da análise.

## Análise Exploratória
- Desenvolvimento de visualizações para interpretar os requisitos de cada jogo.
- Verificação da compatibilidade das GPUs com os requisitos mínimos e recomendados.
- Avaliação da otimização dos jogos mais recentes com base nos dados coletados.

Com essa abordagem, o estudo busca compreender melhor a relação entre os requisitos de hardware e o desempenho real das GPUs nos jogos mais recentes.

# Sobre o projeto

O projeto teve a duração de um mês, sendo a fase de extração a mais desafiadora. No início, tive dificuldades, pois nunca havia trabalhado com Web Scraping antes. No entanto, ao longo do projeto, aprendi os fundamentos da biblioteca Selenium e consegui alcançar um resultado satisfatório.

Durante a fase de processamento, várias funções foram aplicadas para padronizar os nomes e criar novas tabelas, o que se mostrou muito útil para a análise exploratória dos dados. No entanto, essa etapa também reduziu significativamente o volume de dados dos jogos, tornando a análise mais concisa do que eu esperava.

Por fim, a fase de análise exploratória foi onde me senti mais confortável, pois venho focando meus estudos teóricos e práticos nessa área desde o ano passado. No entanto, como mencionado anteriormente, a redução dos dados limitou a quantidade de insights que pude gerar.

Em resumo, desenvolver este projeto foi uma experiência enriquecedora. Desde a extração dos dados até a análise final, tive a oportunidade de praticar e aprimorar minhas habilidades, especialmente em um tema pelo qual sou apaixonado e sobre o qual poderia falar por horas.