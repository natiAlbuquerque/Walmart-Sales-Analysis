# Walmart Sales Analysis - Projeto Aplicado I

Este repositório contém o projeto desenvolvido para a disciplina **Projeto Aplicado I** da Universidade Presbiteriana Mackenzie.

## Conteúdo
- 📊 Análise exploratória de dados (EDA)
- 🤖 Modelagem preditiva inicial
- 🧠 Refinamento do pipeline de treinamento
- 📝 Relatório e storytelling final

## Ferramentas utilizadas
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- GitHub
  
##Storytelling:
Storytelling – Análise de Vendas do Walmart

Este projeto tem como objetivo analisar um conjunto de dados de vendas do Walmart, identificando padrões, fatores de influência e comportamentos relevantes para apoiar decisões estratégicas. A análise foi realizada como parte da disciplina Projeto Aplicado I da Universidade Presbiteriana Mackenzie, seguindo uma abordagem exploratória, iterativa e orientada à construção de hipóteses.

1. Introdução
O Walmart é uma das maiores redes varejistas do mundo, operando em um mercado extremamente competitivo e dinâmico. Compreender como variáveis como temperatura, datas especiais, desemprego e índices econômicos influenciam as vendas é fundamental para ajustar estratégias, melhorar previsões e otimizar recursos.
Este projeto tem como foco entender como essas variáveis se relacionam com o volume de vendas semanais, utilizando técnicas de análise exploratória, visualização e modelagem preditiva simples.

2. Entendimento do Problema

Perguntas-chave que guiaram a análise:
Quais fatores externos influenciam mais as vendas semanais?
Há padrões sazonais importantes?
Feriados têm impacto positivo ou negativo?
As lojas apresentam comportamentos diferentes entre si?
É possível usar modelos simples para prever vendas futuras?
Essas questões orientaram todo o processo de exploração dos dados.

3. Entendimento dos Dados

A base original contém variáveis como:
Store – código da loja
Date – data da observação
Weekly_Sales – vendas totais semanais
IsHoliday – indicador de feriado
Temperature – temperatura local
Fuel_Price – preço do combustível
CPI – índice de preços ao consumidor
Unemployment – taxa de desemprego
As análises iniciais permitiram identificar tendências gerais, outliers e correlações relevantes.

4. Principais Descobertas da Análise Exploratória
4.1 Variação das vendas ao longo do tempo
As vendas demonstram picos sazonais — em especial nos meses próximos a grandes feriados — e quedas consistentes em períodos de retração econômica.

4.2 Efeito dos feriados
Embora feriados costumem aumentar o volume de vendas, nem todos os eventos apresentam impacto significativo.
Algumas lojas têm desempenho elevado durante feriados, enquanto outras não sofrem grandes alterações.

4.3 Influência de fatores econômicos
Variáveis como CPI e Unemployment mostraram relação mais fraca com o volume de vendas, indicando que seu impacto pode ser indireto ou distribuído ao longo de longos períodos.

4.4 Diferenças entre lojas
Algumas lojas possuem vendas consistentemente maiores, sugerindo diferença de porte, localização ou fluxo de clientes.

5. Construção e Ajuste do Pipeline do Modelo

Após entender o comportamento dos dados, o pipeline inicial de modelagem foi construído com base em:
divisão treino/teste
cálculo de métricas
um modelo simples (baseline)
tentativa de introdução de um modelo um pouco mais robusto (SVD, quando possível)
Durante a segunda etapa, o pipeline foi ajustado para melhorar o desempenho — incluindo revisão do tratamento da base, remoção de duplicatas, adequação dos formatos e reavaliação da estratégia de predição.

6. Impacto do Projeto na Aprendizagem

A experiência contribuiu para o desenvolvimento das competências transformadoras do MackSTLR, especialmente:
Reflexão crítica ao interpretar os padrões e validar hipóteses
Liderança e autonomia ao estruturar o trabalho em várias etapas
Competências analíticas e tecnológicas ao manipular dados reais
Comunicação ao traduzir resultados técnicos em linguagem acessível
O projeto reforçou a importância de observar dados reais com profundidade, questionar resultados e ajustar abordagens sempre que necessário.

Conclusão
O storytelling evidencia como a análise evoluiu desde o entendimento do problema até a conclusão das primeiras previsões. Cada etapa ajudou a construir uma visão mais clara sobre os fatores que influenciam o comportamento das vendas e permitiu estruturar um pipeline inicial que pode ser aprimorado nas próximas fases do curso.


## Autora
**Natália Albuquerque**
