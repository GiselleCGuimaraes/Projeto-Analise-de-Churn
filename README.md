# Projeto-Analise-de-Churn



Este projeto apresenta uma análise exploratória de dados (EDA) voltada à investigação do churn em uma empresa Software as a service fictícia do segmento de ERP. A partir da preparação e integração de dados cadastrais de clientes e eventos de uso da plataforma, foram construídas métricas como taxa de churn, tempo de permanência, frequência de uso e indicadores de engajamento.

A análise evidenciou um aumento da taxa de churn no período observado (24,63%), com maior concentração de cancelamentos nos primeiros meses de contrato. Observou-se ainda que clientes com menor frequência de uso e menor nível de engajamento apresentam probabilidade significativamente maior de churn, assim como planos de menor ticket médio, que concentram taxas mais elevadas de evasão.

Os resultados indicam uma relação direta entre comportamento de uso e retenção, reforçando a importância do monitoramento contínuo de métricas de engajamento como suporte à tomada de decisão orientada por dados e à definição de estratégias preventivas de retenção.

Como entregáveis, o projeto resultou em um notebook em Python totalmente documentado, contendo o processo de tratamento, exploração e análise dos dados, além de insights analíticos que podem apoiar decisões estratégicas relacionadas à retenção de clientes e à sustentabilidade do negócio.

## Índice

1. [Visão Geral do Projeto](#visao-geral-do-projeto)
2. [Escopo e Premissas da Análise](#escopo-e-premissas-da-análise)
3. [Ferramentas e Tecnologias](#ferramentas-e-tecnologias)
4. [Abordagem Analítica e Metodologia](#abordagem-analítica-e-metodologia)
5. [Entregáveis do Projeto](#entregáveis-do-projeto)
6. [Principais Insights Gerados](#principais-insights-gerados)
7. [Considerações Finais](#considerações-finais)

## Visão Geral do Projeto

Empresas que operam no modelo Software as a Service (SaaS) dependem diretamente da retenção de clientes para garantir a recorrência de receita e a sustentabilidade do negócio. Nesse contexto, o churn torna-se um dos principais indicadores estratégicos, uma vez que variações na taxa de cancelamento podem sinalizar problemas relacionados à experiência do cliente, engajamento com o produto ou modelo de contratação.

Este projeto foi desenvolvido com o objetivo de investigar a hipótese de aumento da taxa de churn em uma empresa fictícia de tecnologia que oferece um ERP (Enterprise Resource Planning) para pequenas e médias empresas. A análise foi conduzida a partir de dados cadastrais de clientes, informações contratuais e registros de uso da plataforma, permitindo uma visão integrada do perfil dos clientes e de seu comportamento ao longo do tempo.

As principais hipóteses avaliadas ao longo da análise foram:

1. Crescimento da taxa de churn no período analisado;
2. Maior incidência de churn em contratos de curta duração em comparação a contratos de longo prazo;
3. Relação entre nível de engajamento com o sistema e probabilidade de cancelamento;
4. Diferenças na taxa de churn entre planos e perfis de clientes.

Como resultado, foram gerados insights analíticos para apoiar a tomada de decisão da área de negócios, além da utilização de Pyhton para tratamento de análise, construção de um dashboard interativo, voltado ao monitoramento de churn e indicadores de engajamento, e de uma apresentação executiva, sintetizando os principais achados da análise de forma clara e acionável para stakeholders não técnicos.

![download](https://github.com/user-attachments/assets/d8bd1750-e9b2-4179-bef2-82045d2bc760)

## Escopo e Premissas da Análise
   
A análise foi realizada com dados de churn referentes aos meses de abril e maio de 2025, considerando clientes de uma empresa fictícia que atua no modelo SaaS, com foco em um produto do tipo ERP. Os dados utilizados contemplam informações cadastrais, contratuais e registros de uso da plataforma, permitindo a avaliação do comportamento dos clientes e a identificação de padrões associados ao cancelamento de assinaturas.

Os dados analisados foram obtidos a partir da base disponibilizada no EBA – Estatística para Análise de Dados (https://renatabiaggi.com/eba-estatistica/
), sendo tratados e preparados previamente para fins analíticos. Assume-se que clientes classificados como churn são aqueles que cancelaram a assinatura dentro do período analisado e que os registros de uso representam adequadamente o nível de engajamento com o sistema.

A análise possui caráter exploratório e descritivo, tendo como objetivo identificar tendências, segmentações relevantes e relações entre engajamento, tipo de contrato e churn, sem a aplicação de modelos preditivos ou inferenciais.

## Ferramentas e Tecnologias
   
- Python
  -  Pandas
  -  Numpy
  -  Seaborn
  -  Matplotlib
 
- Canva para apresentação
  
## Abordagem Analítica e Metodologia

O projeto foi desenvolvido por meio de uma Análise Exploratória de Dados, estruturada em etapas complementares, com o objetivo de compreender a qualidade dos dados, validar hipóteses de negócio e identificar padrões associados à ocorrência de churn.

Na etapa de exploração univariada, os dados foram analisados individualmente para compreensão dos tipos de variáveis, identificação de valores únicos, verificação de valores ausentes ou nulos e avaliação da qualidade dos dados. Essa etapa incluiu a análise de distribuições de variáveis categóricas e numéricas, bem como a detecção de inconsistências, como registros inválidos, valores zerados indevidamente e padronizações incorretas.

Na etapa de exploração multivariada, foram realizadas análises temporais para validar a hipótese de aumento da taxa de churn no período analisado. Adicionalmente, foram aplicados agrupamentos e segmentações para avaliar a variável alvo (ocorrência de churn) em conjunto com outras variáveis relevantes, como tipo de contrato, plano e utilização de serviços. Essa abordagem permitiu identificar relações e padrões comportamentais associados ao cancelamento de assinaturas.

Os resultados obtidos nessas etapas fundamentaram a construção de indicadores analíticos, visualizações e entregáveis finais do projeto.

## Entregáveis do Projeto

Como resultado do processo analítico, foram gerados os seguintes entregáveis:

[Notebook em Python](https://github.com/GiselleCGuimaraes/Projeto-Analise-de-Churn/blob/main/An%C3%A1lise_de_Churn_empresa_SAAS.ipynb) contendo todo o processo de tratamento, exploração e análise dos dados, com código comentado e visualizações que documentam as etapas da análise exploratória e a validação das hipóteses levantadas;


Apresentação executiva, consolidando os principais insights e conclusões da análise de forma objetiva e orientada ao suporte à tomada de decisão por stakeholders de negócio.

Esses entregáveis permitem tanto a análise técnica quanto a comunicação clara dos resultados para públicos técnicos e não técnicos.

## Principais Insights Gerados  
**Análise de Perfil dos clientes**
* A base de clientes é bem balanceada, com 50.5% Pequenas Empresas e 49.5% Micro Empresas.
* Predominância de micro e pequenas empresas, com 70.0% possuindo até 5 funcionários e 30.0% com 6 ou mais funcionários.
* A distribuição mostra uma alta concentração de clientes nos primeiros meses, com a **frequência diminuindo acentuadamente à medida que a permanência aumenta**. A média é de 32.4 meses, com a mediana em 29 meses.
* A maioria dos clientes faz conciliação manual (44.0%) ou automática (34.4%), com 21.7% não realizando, o que indica menor nível de maturidade tecnologica.
* Observa-se que uma parcela significativa de clientes faz 'Pouco uso' (cerca de 40-50%) ou 'Nunca utilizou' (cerca de 20%) das funcionalidades de módulos (financeiro, vendas, relatórios, APIs).
* A maioria tem contrato Mês-a-mês (55.0%), seguido por Anual (24.1%) e Trimestral (20.9%).
* A maioria dos clientes (59.2%) emite boletos.
* A maioria das empresas foi fundada entre 2016 e 2021, indicando uma base de clientes predominantemente jovem.

**Análise do Churn – Comparação entre Abril/2025 e Maio/2025**

A taxa de churn aumentou 24.63% de abril para maio de 2025, passando de 14.86% para 18.52% em relação aos clientes ativos no início de cada mês. Este crescimento percentual, embora em pontos absolutos menores, indica uma aceleração dos cancelamentos e valida a hipótese inicial.
Número de Churns: 911 em abril/2025 e 958 em maio/2025.

**Análise do Churn – Padrões Observados**

* Clientes nos primeiros 12 meses de contrato têm a maior taxa de churn (48.3%). Os primeiros 1 a 4 meses são ainda mais críticos, com taxas acima de 47% (chegando a 62% no primeiro mês).A taxa de churn diminui drasticamente com o tempo, atingindo 8.3% para 61-72 meses de permanência.

<img width="990" height="590" alt="% churn por meses de permanencia" src="https://github.com/user-attachments/assets/d4222f11-8a4a-485b-bd61-0ad8e5dcc4fd" />

* Contratos 'Mês-a-mês' apresentam a maior taxa de churn (42.7%). Contratos 'Trimestrais' têm churn moderado (11.3%).Contratos 'Anuais' são os mais estáveis, com apenas 2.8% de churn.O que indica que modalidades mais longas de contrato têm menor chance de churn.  

<img width="990" height="590" alt="% churn x tipo de contrato" src="https://github.com/user-attachments/assets/4581a17b-eb48-4255-ad0e-a2a2a767672f" />

* Em relação a engajamentocom funcionalidades, clientes com 'Pouco uso' de qualquer módulo (financeiro, vendas, relatórios, APIs, etc.) têm as maiores taxas de churn (33-42%). Clientes que 'Nunca utilizaram' funcionalidades específicas têm as menores taxas de churn (7.4%), sugerindo que a funcionalidade pode não ser crítica para eles.

  <img width="990" height="590" alt="%churn x módulo financeiro" src="https://github.com/user-attachments/assets/d2828b32-14e5-4311-a407-e7831adb5079" />

*


## Considerações Finais
