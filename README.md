# analise-de-dados-da-participacao-do-uso-de-energias-renovaveis-no-mercado-energetico-br
#### Aluno: Renata Moreira Farias de Macedo(https://github.com/renatamacedo)
#### Orientador: Anderson Nascimento(https://github.com/insightds)

---
Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bimaster) como pré-requisito para conclusão de curso e obtenção de
crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à
Decisão".

---
### Resumo
Este artigo tem por finalidade identificar, através da análise de dados históricos de fornecimento de energia no mercado energético brasileiro, soluções para a crescente demanda de consumo na população brasileira, através da análise do potencial do uso das fontes de energia renovável. O projeto de business intelligence (BI) desenvolvido visa atender a essas necessidades de percepção para este problema. Neste artigo são identificados os objetivos do projeto, o processo de BI desenvolvido, os resultados e conclusões obtidos.
### Abstract This article aims to identify, through the analysis of historical data of energy supply in the Brazilian energy market, solutions to the growing demand for consumption in the Brazilian population, analysis of the potential of the use of renewable energy sources. The  business intelligence (BI) project developed aims to meet these perception needs for this problem. This article identified the objectives of the project, the BI process developed, the results and conclusions obtained.
### 1. Introdução
O surgimento de ferramentas de BI vem apoiar na transformação de dados em informações valiosas, na tomada de decisões assertivas e confiáveis, em um contexto em que a quantidade de dados é muito vasta e se encontra muitas vezes dispersa por inúmeras bases de dados, facilitando a sua compilação, organização, uniformização e o desenvolvimento de análises sobre esses dados (Olszak e Ziemba, 2007). Estas ferramentas, quando devidamente implementadas, trazem vários benefícios para as empresas, nomeadamente, o aumento da eficiência, quer pelo acesso mais rápido a grandes volumes de informação, quer pela partilha do acesso a outros departamentos da empresa, e a possibilidade de utilizar os dados para realizar previsões mais fiáveis, identificar tendências e analisar desvios.
Considerando a contínua e cada vez mais acelerada evolução tecnológica e industrial no mundo, associado ao crescimento da população brasileira (estimativa de aumento, em 2020, de 0,77% em relação a 2019), o consumo energético amplia-se em escala exponencial. Visando com que todo esse crescimento de demanda não acarrete aumento na poluição, o uso de fontes de energias renováveis torna-se imprescindível e cada vez mais necessário.
Através da extração de dados obtidos através da Empresa de Pesquisa Energética (EPE) empresa pública federal, vinculada ao Ministério de Minas e Energia (MME), procura-se informações precisas e confiáveis que possam identificar quais são as fontes de energia de maior crescimento e quais são os potenciais de crescimento por regiões brasileiras. 
Este estudo possui como referência dados obtidos no período de 2012 a 2019 no Balanço Energético Nacional (BEN) e no Anuário Estatístico de Energia Elétrica, ambos disponibilizados pela EPE, sobre tipos de fontes de energia renovável, composição setorial da economia brasileira no que tange a consumo, dependência externa, centrais elétricas, capacidade instalada por região e unidade da federação, consumo por região geográfica e população e consumo per capita. Ao todo foram analisadas 237 planilhas, buscando identificar quais seriam os dados mais relevantes para essa análise.
### 2. Modelagem
Obteve-se o modelo transacional através de análise minuciosa dos dados e de sua importância para este estudo. Finalmente gerou-se 4 tabelas dimensionais e 11 tabelas fato. Preservou-se os dados mais recentes, no período de 2012 a 2019.
Inicialmente o processo de BI será alimentado com estes dados, mas tem-se como objetivo o carregamento de dados mais atualizados, à medida que forem divulgados pela Empresa de Pesquisa Energética (EPE). 
Com os dados escolhidos, iniciou-se a etapa de preparação dos dados para o Data Warehouse (DW) através do processo de ETL para executar a transformação dos dados, buscando-se a uniformização de unidades de medidas e nomes de campos. A carga de dados será total para que possa posteriormente, e caso haja interesse, sejam realizadas cargas incrementais com dados dos próximos anos.
### 3. Resultados
Foram gerados 3 painéis com visuais conectados.
No painel Análise por fonte é possível realizar filtros por tipo de fonte e ano. Há cinco visuais com as informações de oferta interna, consumo e produção e importação e exportação por tipo de fonte. Além destas, obtém-se informações de consumo de energia por setor e gênero econômicos. Uma análise detalhada por região e estado poderá ser obtida no painel Análise por UF – Brasil, onde encontra-se informações da população e consumo per capita, capacidade instalada do setor elétrico, o consumo energético e quantidade de consumidores por setor econômico em cada unidade da federação. Com filtros por região, estados (no mapa do Brasil) e por ano é possível escolher a localidade pretendida para obter referências do potencial de crescimento das fontes de energia renováveis.
No terceiro painel é possível comparar a colocação do Brasil frente aos 20 maiores países do mundo em geração de energia, principalmente tendo como foco de estudo a produção de energia renovável.
### 4. Conclusões
O seguimento de todas as fases do processo de BI (transformação dos dados, utilização de uma stage área e ETL), auxilia sobremaneira na elaboração de painéis mais profissionais e que cumprem com seu objetivo principal: ser uma ferramenta importante em uma análise rápida e confiável para os que pretendem aumentar a utilização de fontes renováveis para a geração de energia.

---
Matrícula: 192.671.135

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master

