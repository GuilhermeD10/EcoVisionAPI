# EcoVision - O eco da inovação

![image alt](https://github.com/EcoVision2-team/EcoVisionAPI/blob/main/EcoVisionLogo.jpeg)

![Status](https://img.shields.io/badge/status-em%20andamento-green)
![Projeto](https://img.shields.io/badge/API-Fatec%20SJC-blue)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Dados](https://img.shields.io/badge/Dados-RAIS-lightgrey)

## 📊 Mapeamento do Ecossistema Industrial e de Serviços - Engenharia de produção 

# Aprendizado por Projeto Integrado (API) - Mapeamento do Ecossistema Industrial e de Serviços da Região de São José dos Campos

# Índice

* [Equipe](#Equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Backlog do produto](#Product-Backlog)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Tratamento e Filtragem de Dados (Python – Google Colab)](#Tratamento-e-Filtragem-de-Dados-(Python-–-Google-Colab))
* [Registro das Sprints](#Registro-das-Sprints)


# Projeto (API) 
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO).

Dentro desse contexto, foi desenvolvido um processo de tratamento e análise de dados utilizando Python no ambiente Google Colab, com foco na base de dados da RAIS (Relação Anual de Informações Sociais). Essa etapa tem como objetivo viabilizar o mapeamento do ecossistema industrial e de serviços da região de São José dos Campos por meio da transformação de dados brutos em informações estruturadas.

O processo inclui a importação dos dados com a biblioteca pandas, a filtragem dos registros com base no recorte geográfico do município, a seleção de variáveis relevantes (como setor econômico, CNAE, vínculos empregatícios e indicadores salariais), além do tratamento de inconsistências e organização das informações. Posteriormente, os dados são agrupados e consolidados, permitindo identificar padrões, concentração de setores e principais atividades econômicas da região.

As informações tratadas servem como base para integração com o Power BI, onde são construídos dashboards interativos que possibilitam a análise visual dos dados, facilitando a interpretação e a tomada de decisão.

Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC com definição das datas do kickoff e das sprint.
# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Guilherme Donato        |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-donato-sousa-24b29b1b1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GuilhermeD10)              |
| Scrum Master  | Nicolas Jesus |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-jesus-mota-da-cruz-b3b03b331?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/nicolassmotaa)     |
| Team Member   | João Buaski              |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joão-eduardo-buaski-ba555b2a5?utm_source=share_via&utm_content=profile&utm_medium=member_ios) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joaobuaski)        |
|  Team Member  | Felipe Villela                 |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/felipe-villela-1706613b9?utm_source=share_via&utm_content=profile&utm_medium=member_ios) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/felipelfvillela-lang)        |
|  Team Member  | Iran Ricardo               |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/iran-ricardo-a308a2288?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/iranbragion)   |   
|  Team Member  | Amauri D Santos       |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amauri-d-santos-2091b8346?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B%2BrJM7q0jRzaifHjzoDJOIQ%3D%3D) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/amauridsantos77)    



# Objetivo do Projeto
Este projeto tem como objetivo mapear o ecossistema Industrial e de Serviços da Região de São José dos Campos visando:
* Fornecer uma base organizada de dados que facilite a interpretação, análise e visualização das informações sobre o setor industrial local;
* Identificar e organizar os principais setores e indústrias da cidade, possibilitando uma análise clara da composição industrial;
* Mapear os diferentes agentes do ecossistema, permitindo visualizações estruturadas e comparações entre eles;
* Analisar a distribuição e interações dos dados coletados, gerando insights sobre tendências, concentração setorial e áreas de destaque;
* Avaliar indicadores econômicos e de atuação das indústrias, facilitar decisões estratégicas com base em dados concretos;
* Consolidar todas as informações em um dashboard interativo, buscando proporcionar interpretação rápida, prática e acessível dos dados para diferentes usuários.


## Tecnologias Utilizadas

* Power BI
* Microsoft Excel
* Python (Colab)
* Canva



# Product Backlog

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|------------|------------|--------|
| 1 | Alta | Como tomador de decisões de políticas públicas, quero coletar dados da RAIS para analisar os dados do ecossistema produtivo dos principais setores de São José dos Campos. | 30/mar | 1 |
| 2 | Alta | Como tomador de decisões de políticas públicas, quero entender a estrutura de dados para identificar variáveis relevantes. | 30/mar | 1 |
| 3 | Alta | Como tomador de decisões de políticas públicas, quero importar os dados no Python e utilizando a biblioteca pandas realizar o tratamento das informações. | 10/abr | 1 |
| 4 | Alta | Como tomador de decisões de políticas públicas, quero classificar as atividades econômicas predominantes (4 setores principais). | 10/abr | 1 |
| 5 | Alta | Como tomador de decisões de políticas públicas, quero importar esses dados para o Github e conectar ao Power BI para visualização. | 17/abr | 1 |
| 6 | Alta | Como tomador de decisões de políticas públicas, quero visualizar os principais setores industriais da região de São José dos Campos para análise. | 17/abr | 1 |
| 7 | Alta | Como tomador de decisões de políticas públicas, quero criar painéis analíticos no Power BI para interpretar os dados. | 04/mai | 2 |
| 8 | Alta | Como tomador de decisões de políticas públicas, quero um gráfico para visualização da distribuição geográfica dos setores produtivos na região. | 04/mai | 2 |
| 9 | Alta | Como tomador de decisões de políticas públicas, quero visualizar indicadores econômicos e produtivos importantes. | 15/mai | 2 |
| 10 | Alta | Como tomador de decisões de políticas públicas quero visualizar indicadores de crescimento ou decrescimento durante os anos dos setores predominantes na cidade. | 22/mai | 2 |
| 11 | Média | Como tomador de decisões de políticas públicas quero definir modelo, cor e layout | 05/jun | 2 |
| 12 | Alta | Como tomador de decisões de políticas públicas, quero visualizar graficamente a participação de diferentes setores na economia regional. | 25/mai | 3 |
| 13 | Alta | Como tomador de decisões de políticas públicas, quero comparar diferentes segmentos industriais e de serviços para entender sua influência na economia. | 25/mai | 3 |
| 14 | Média | Como tomador de decisões de políticas públicas, quero definir modelo, cor e layout. | 05/jun | 3 |
| 15 | Alta | Como tomador de decisões de políticas públicas, quero uma interface clara e intuitiva combinando todos os blocos dentro do dashboard. | 05/jun | 3 |

# Tratamento e Filtragem de Dados (Python – Google Colab)
Para viabilizar o mapeamento do ecossistema industrial e de serviços da região de São José dos Campos, foi desenvolvido um código em Python no ambiente Google Colab com o objetivo de realizar a extração, filtragem e tratamento dos dados provenientes da base RAIS (Relação Anual de Informações Sociais).

Dísponivel em:
https://colab.research.google.com/drive/1lq5vQ6udxyRsS2qs2T_-syoaOEGpHb-1?usp=sharing

# Dashboard Power BI

  https://app.powerbi.com/view?r=eyJrIjoiMjg2MzIxYmYtZDEyNi00MjQxLTg1NjMtNGNhMzJjMjI0NmU2IiwidCI6ImVhYmU2NGM1LTY4ZjUtNGE3Ni04MzAxLTk1NzdhNjc5ZTQ0OSIsImMiOjR9&embedImagePlaceholder=true

# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 27/04/2026 | finalizado | [MVP](MVP/sp1.md)  |
| 02                | 25/05/2026 | finalizado | [MVP](MVP/sp2.md)  |
| 03                | 08/06/2026 | a fazer  | [MVP](MVP/sp3.md)  |
| Feira de Soluções | 18/06/2026 | a fazer  | [MVP](#)  |

