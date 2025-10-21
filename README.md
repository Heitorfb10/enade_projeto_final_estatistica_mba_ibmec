# Projeto Final do Curso de Estatística do MBA em IA, Data Science e Big Data para Negócios do IBMEC: Análise de dados do ENADE 2017

![Status: Concluído - Nota 10/10] 

# Relatório Completo e Visualização Interativa:
Este trabalho visa analisar os dados do ENADE 2017 para responder a avaliação final do curso de Estatística para Ciência de dados do MBA em IA, Data Science e Big Data para Negócios do IBMEC. O relatório final (HTML) contém todos os códigos em R, gráficos e análises estatísticas exigidas.

**ACESSE O DASHBOARD INTERATIVO AQUI:**
[Projeto Final - Relatório ENADE (HTML)] (https://heitorfb10.github.io/enade_projeto_final_estatistica_mba_ibmec/projeto_final_estatistica_ibmec_v4.html)

## Objetivo e Contexto da Análise
O objetivo central deste trabalho é aplicar técnicas de **Estatística Descritiva e Inferencial** para analisar os microdados do ENADE 2017, com foco no curso de **Engenharia de Controle e Automação**.
A análise busca **evidenciar disparidades de desempenho** e responder à seguinte hipótese:
**Há razão para desconfiar que variáveis socioeconômicas (Raça/Cor) e geográficas (Região) causam diferenças estatisticamente significativas nas notas dos alunos.**

## Metodologia e Ferramentas
| Ferramenta / Técnica | Finalidade |
| :--- | :--- |
| **Linguagem / Ambiente** | R (RStudio) |
| **Transformação de Variáveis** | `case_when()` para rotular 17 colunas (Ex: códigos `1` para `Norte`). |
| **Limpeza de Dados** | `na.omit()` para garantir a qualidade estatística da amostra. |
| **Estatística Descritiva** | `summarise()` com `Mode`, `skewness`, `kurtosis` (forma da distribuição). |
| **Visualização Principal** | **Box-Plots Fasetados** (`facet_wrap`) para cruzar Nota por Raça DENTRO de cada Região. |
| **Análise de Frequência** | **Gráficos de Barras Empilhadas** (`geom_bar(position="fill")`) para visualizar proporção de satisfação. |
| **Relatório de Entrega** | **RMarkdown** (output `rmdformats::readthedown`). |
---
