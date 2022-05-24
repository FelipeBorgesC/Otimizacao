# Otimização - BI Master PUC-Rio
## Arquivos e dados utilizados ao longo das aula de Otimização no curso BI-Master PUC-Rio.

### Índice
  
- [Introdução OAG](#introducao-oag)
- [Representação, Decodificação e Avaliação](#represent-decod-avaliacao)
- [Operadores Genéticos](#operadores)
- [Associação](#associação)
- [Agurpoamento](#agrupamento)
- [Regressão](#regressao)
- [Previsão de Séries Temporais](#series)

<h2 id="introducao-oag">
  
[Introdução a Otimização - Algoritmos Genéticos](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%201%20-%20Conceitos%20B%C3%A1sicos%20Otimiza%C3%A7%C3%A3o)
  
</h2>

  - **Aula 01:** Introdução e noções básicas de otimização [`Aula 1 - OAG.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%201%20-%20Conceitos%20B%C3%A1sicos%20Otimiza%C3%A7%C3%A3o/Aula%201%20-%20OAG.pdf). Apresentação do conteúdo que é abordado ao longo do curso.
    - Conceitos de otimização
    - Otimização por Algoritmos Genéticos 
      - Representação
      - Função de Avaliação
      - Operadores Genéticos
      - Ciclo de Otimização
    - Aplicações de Otimização


<h2 id="represent-decod-avaliacao">
  
[Representação, Decodificação e Avaliação](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%202%20-%20Respresenta%C3%A7%C3%A3o%2C%20Decodifica%C3%A7%C3%A3o%20e%20Avalia%C3%A7%C3%A3o)
  
</h2>

  - **Aula 02:** Representação, Decodificação e Avaliação de Indíviduos [`Aula 2 - OAG.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%202%20-%20Respresenta%C3%A7%C3%A3o%2C%20Decodifica%C3%A7%C3%A3o%20e%20Avalia%C3%A7%C3%A3o/Aula%202%20-%20OAG.pdf). Nesta apresentação é abordado com maiores detalhes o processo de representação cromossômica e sua decodificação. Qual o propósito na representação do individuo e seus tipos. Além disso, apresentar as possíveis formas de avaliação dos individuos e o seu propósito.
  
    - Representação Cromossômica
      - Tipos de representação
      - Impactos no processo de otimização
    - Decodificação     
    - Função de Avaliação
      - Problemas associados
      - Normalização
      - Windowing


  - **Ferramenta Solver:** Apresentação e utilização da ferramenta Solver do Excel [`Solução_F6.xlsx`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%202%20-%20Respresenta%C3%A7%C3%A3o%2C%20Decodifica%C3%A7%C3%A3o%20e%20Avalia%C3%A7%C3%A3o/Excel%20-%20Solver/Solu%C3%A7%C3%A3o_F6.xlsx). Neste exemplo é abordado a utilização de um caso benchmark para a otimização de uma função matemática famosa, chamada F6. Essa função matemática é complexa e possui picos e vales muito próximos uns aos outros, o que caracteriza um problema de difícil otimização.

    - A função não possui restrições
    - O objetivo é a maximização
    - O valor ótimo do problema é x = 0 e y = 0, resultando f(x,y) = 1


- **Python usando DEAP:** Solução de um exemplo utilizando a biblioteca DEAP em python [`Aula_02_ExemploInicial.ipynb`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%202%20-%20Respresenta%C3%A7%C3%A3o%2C%20Decodifica%C3%A7%C3%A3o%20e%20Avalia%C3%A7%C3%A3o/Python%20-%20DEAP/Aula_02_ExemploInicial.ipynb). Este exemplo utiliza a linguagem de python para resolver um problema de otimização. O propósito desse exercício é encontrar o maior valor possível de uma função matemática exemplo que está descrita no script. 

    - A função não possui restrições
    - O objetivo é a maximização
    - O valor ótimo do problema pode ser visualizado através do gráfico presente no script


<h2 id="operadores">
  
[Operadores Genéticos](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%203%20-%20Operadores%20Gen%C3%A9ticos)
  
</h2>

 - **Aula 03:** Operadores Genéticos: Seleção, Cruzamento e Mutação [`Aula 3 - OAG.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%203%20-%20Operadores%20Gen%C3%A9ticos/Aula%203%20-%20OAG.pdf). Conteúdo apresentado sobre os operadores genéticos e suas variações. Fluxograma do processo evolutivo e explicação detalhada das etapas de seleção, cruzamento e seleção. Além disso, são apresentadas as técnicas de melhoria do processo evolutivo.
 
    - Fluxograma do ciclo evolutivo      
    - Seleção
    - Cruzamento
      - 1 ponto de corte
      - N pontos de corte
      - Uniforme
      - Baseado em maioria
    - Mutação
      - Único bit
      - Uniforme
    - Seleção de Operadores
    - Elitismo
    - Steady State


 - **Resolução Exercícios:** Resolução dos exercícios abordados na aula anterior [`Aula 2 Resolvido.xlsx`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%203%20-%20Operadores%20Gen%C3%A9ticos/Resolu%C3%A7%C3%A3o%20Aula%202/Aula%202%20Resolvido.xlsx). Respostas dos exercicios comentados na aula 02.
 
    - Normalização      
    - Windowing


 - **Resolução Rainhas:** Resolução do exercício das rainhas abordado na aula anterior [`Rainhas.xlsx`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%203%20-%20Operadores%20Gen%C3%A9ticos/Resolu%C3%A7%C3%A3o%20Rainhas/Rainhas.xlsx). Apresentação de diversas soluções possíveis para o problema das rainhas.
 
    - Representações Incomuns     
    - Alternativas de Funções Objetivo

- **Exercício Telecom:** Exercicio para praticar sobre alocação de antenas de telecomunicações [`Exercicio Telecom.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%203%20-%20Operadores%20Gen%C3%A9ticos/Telecom/Exercicio%20Telecom.pdf). Exercicio para praticar os conhecimentos de otimização. Identificar os principais pilares para aplicação de um otimizador. Buscar resolver o problema através dos otimizadores mencionados anteriormente.
 
    - Identificação das variáveis     
    - Modelagem da função objetivo
    - Definir as restrições
    - Executar a otimização


<h2 id="associacao">
  
[Associação](https://github.com/manoelakohler/DataMining/tree/main/04_Associa%C3%A7%C3%A3o)
  
</h2>

 - **Transações em um mercado francês:** Entendimento, pré processamento e associação de itens de um mercado utilizando o algoritmo Apriori [`Market_Apriori.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/04_Associa%C3%A7%C3%A3o/Market_Apriori.ipynb) e o FP-Growth [`Market_FPGrowth.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/04_Associa%C3%A7%C3%A3o/Market_FPGrowth.ipynb). Lista de transações (compras) em um mercado francês: Cada linha da base é uma transação; Cada transação tem de 1 a N itens; Existem 119 produtos diferentes no mercado; Base tem 7501 transações feitas no decorrer de 1 semana.
 
    - Pré processamento
      - Transformação de transações em uma matriz esparsa
    - Inferência (classificação)
      - Apriori
      - FP-Growth
    - Pós processamento
      - Geração de regras a partir de conjuntos de itens frequentes

<h2 id="agrupamento">
  
[Agrupamento](https://github.com/manoelakohler/DataMining/tree/main/05_Agrupamento)
  
</h2>

<h2 id="regressao">
  
[Regressão](https://github.com/manoelakohler/DataMining/tree/main/06_Regress%C3%A3o)
  
</h2>

<h2 id="series">
  
[Previsão de Séries Temporais](https://github.com/manoelakohler/DataMining/tree/main/07_Previs%C3%A3o_de_S%C3%A9ries_Temporais)
  
</h2>

