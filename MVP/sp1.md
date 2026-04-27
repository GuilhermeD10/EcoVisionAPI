# 📌 MVP - Mapeamento do Ecossistema Industrial e de Serviços da Região de São José dos Campos

## 🎯 Objetivo do MVP
> O MVP tem como objetivo validar a capacidade de transformar dados brutos da base RAIS em informações estruturadas que permitam identificar os principais setores econômicos da região de São José dos Campos.

O problema abordado é a dificuldade de interpretação de grandes volumes de dados não tratados, que dificultam análises econômicas e tomadas de decisão.

A hipótese validada é que, por meio do tratamento e filtragem dos dados em Python, é possível gerar informações organizadas e relevantes.

O valor entregue ao usuário final consiste na disponibilização de dados limpos e estruturados, aliados a uma visualização clara em dashboard, facilitando a análise e compreensão do cenário econômico. 

---

## 📝 Descrição da Solução
> A solução consiste no desenvolvimento de um processo de tratamento de dados utilizando Python (Google Colab), seguido da construção de um dashboard no Power BI.

Funcionalidades principais:

* Importação da base RAIS
* Filtragem por São José dos Campos
* Tratamento e limpeza de dados
* Agrupamento por setores econômicos
* Geração de base estruturada
* Visualização em dashboard interativo

Limitações:

* Uso de uma única base de dados
* Recorte geográfico específico
* Atualização não automatizada

Escopo: O MVP contempla o tratamento e organização dos dados e sua visualização inicial, sendo melhorias e expansões previstas para etapas futuras.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Prefeitura de São José dos Campos (Gestão Pública)
Representa órgãos públicos responsáveis pelo planejamento e desenvolvimento econômico da região.

Necessidade: acesso a dados estruturados e confiáveis sobre o mercado de trabalho e setores produtivos.

Dor: dificuldade em interpretar grandes volumes de dados brutos e ausência de informações organizadas para embasar decisões estratégicas.

- **Persona 2:** Prof. Me. Marcus Vinicius do Nascimento  (Cliente / Tomador de Decisão)
Perfil de usuário interessado em compreender o cenário econômico local.

Necessidade: visualização clara dos principais setores econômicos e seus indicadores.

Dor: dificuldade em obter análises consolidadas e confiáveis a partir de dados dispersos e pouco estruturados.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como tomador de decisões de políticas públicas, quero coletar dados da RAIS para analisar os dados do ecossistema produtivo dos principais setores de São José dos Campos. | Alta | ? |
| US2 | Como tomador de decisões de políticas públicas, quero entender a estrutura de dados para identificar variáveis relevantes. | Alta | ? |
| US3 | Como tomador de decisões de políticas públicas, quero importar os dados no Python e utilizando a biblioteca pandas realizar o tratamento das informações. | Alta | ? |
| US4 | Como tomador de decisões de políticas públicas, quero classificar as atividades econômicas predominantes (4 setores principais). | Alta | ? |
| US5 | Como tomador de decisões de políticas públicas, quero importar esses dados para o Github e conectar ao Power BI para visualização. | Alta | ? |
| US6 | Como tomador de decisões de políticas públicas, quero visualizar os principais setores industriais da região de São José dos Campos para análise. | Alta | ? |
| US7 | Como tomador de decisões de políticas públicas, quero criar painéis analíticos no Power BI para interpretar os dados. | Alta | ? |
| US8 | Como tomador de decisões de políticas públicas, quero um gráfico para visualização da distribuição geográfica dos setores produtivos na região. | Alta | ? |
| US9 | Como tomador de decisões de políticas públicas, quero visualizar indicadores econômicos e produtivos importantes. | Alta | ? |
| US10 | Como tomador de decisões de políticas públicas, quero visualizar graficamente a participação de diferentes setores na economia regional. | Alta | ? |
---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Coleta da base RAIS; entendimento da estrutura dos dados; tratamento em Python (pandas); classificação dos setores econômicos; integração com GitHub e conexão inicial com Power BI; visualização inicial dos setores industriais                       | Concluído|
| 02     | Criação de painéis analíticos no Power BI; desenvolvimento de gráfico de distribuição geográfica; definição de indicadores econômicos e produtivos; início da análise visual dos dados                          | Em andamento |




---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize e analise os principais setores econômicos de São José dos Campos a partir de dados estruturados da base RAIS.  
- O sistema deve registrar o processamento dos dados (importação, filtragem, tratamento e geração da base final), garantindo consistência entre os dados tratados no Python e os apresentados no dashboard. 
- Métricas coletadas: [exemplo: tempo de resposta, taxa de uso]  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio (exemplo: % de adesão, redução de custo, etc.)  

---

## 🚀 Próximos Passos
* Integração completa com Power BI
* Refinamento visual do dashboard
* Inclusão de novos indicadores
* Expansão da análise para outros setores
---

## 📂 Anexos / Evidências

## 📊 Dashboard Power BI
- 🌐 **Acesse:** https://app.powerbi.com/view?r=eyJrIjoiYjYzNDNlN2EtMzIwYS00ODE0LThlNTAtZDBjYjI4ZGE3NmI0IiwidCI6ImVhYmU2NGM1LTY4ZjUtNGE3Ni04MzAxLTk1NzdhNjc5ZTQ0OSIsImMiOjR9&embedImagePlaceholder=true
---

## 📁 Base de Dados Tratada 
📄 **Arquivo:** [rais_sjc_limpo (1).csv](https://github.com/user-attachments/files/27109170/rais_sjc_limpo.1.csv)
- Contém os dados da base RAIS após limpeza, filtragem e organização, prontos para análise.
---

## 📊 Slides da Apresentação
- 📄 **Arquivo:**[Eco Vision O Eco da Inovação_20260426_233509_0000.pdf](https://github.com/user-attachments/files/27110154/Eco.Vision.O.Eco.da.Inovacao_20260426_233509_0000.pdf)
- Apresenta os objetivos, metodologia, desenvolvimento e resultados do projeto.

---

## 📋 Planejamento 5W2H
- 📄 **Arquivo:** [5W2H.xlsx](https://github.com/user-attachments/files/27109234/5W2H.xlsx)
- Contém o planejamento estratégico utilizado no desenvolvimento do MVP.

