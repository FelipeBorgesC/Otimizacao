# Otimização - BI Master PUC-Rio
## Arquivos e dados utilizados ao longo das aula de Otimização no curso BI-Master PUC-Rio.

### Índice
  
- [Introdução OAG](#introducao-oag)
- [Representação, Decodificação e Avaliação](#represent-decod-avaliacao)
- [Classificação](#classificacao)
- [Associação](#associação)
- [Agurpoamento](#agrupamento)
- [Regressão](#regressao)
- [Previsão de Séries Temporais](#series)

<h2 id="introducao-oag">
  
[Introdução a Otimização - Algoritmos Genéticos](https://github.com/manoelakohler/DataMining/tree/main/01_An%C3%A1liseExplorat%C3%B3ria)
  
</h2>

  - **Aula 01:** Introdução e noções básicas de otimização [`Aula 1 - OAG.pdf`](https://github.com/manoelakohler/DataMining/blob/main/01_An%C3%A1liseExplorat%C3%B3ria/mushroom.ipynb). Apresentação do conteúdo que é abordado ao longo do curso.
    - Conceitos de otimização
    - Otimização por Algoritmos Genéticos 
      - Representação
      - Função de Avaliação
      - Operadores Genéticos
      - Ciclo de Otimização
    - Aplicações de Otimização


<h2 id="represent-decod-avaliacao">
  
[Representação, Decodificação e Avaliação](https://github.com/manoelakohler/DataMining/tree/main/02_Pr%C3%A9Processamento)
  
</h2>

  - **Aula 02:** Representação, Decodificação e Avaliação de Indíviduos [`Secom.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/02_Pr%C3%A9Processamento/Secom.ipynb). Nesta apresentação é abordado com maiores detalhes o processo de representação cromossômica e sua decodificação. Qual o propósito na representação do individuo e seus tipos. Além disso, apresentar as possíveis formas de avaliação dos individuos e o seu propósito.
  
    - Representação Cromossômica
      - Tipos de representação
      - Impactos no processo de otimização
    - Decodificação     
    - Função de Avaliação
      - Problemas associados
      - Normalização
      - Windowing


  - **Ferramenta Solver:** Apresentação e utilização da ferramenta Solver do Excel [`Secom.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/02_Pr%C3%A9Processamento/Secom.ipynb). Neste exemplo é abordado a utilização de um caso benchmark para a otimização de uma função matemática famosa, chamada F6. Essa função matemática é complexa e possui picos e vales muito próximos uns aos outros, o que caracteriza um problema de difícil otimização.

    - A função não possui restrições
    - O objetivo é a maximização
    - O valor ótimo do problema é x = 0 e y = 0, resultando f(x,y) = 1


- **Python usando DEAP:** Solução de um exemplo utilizando a biblioteca DEAP em python [`Secom.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/02_Pr%C3%A9Processamento/Secom.ipynb). Este exemplo utiliza a linguagem de python para resolver um problema de otimização. O propósito desse exercício é encontrar o maior valor possível de uma função matemática exemplo que está descrita no script. 

    - A função não possui restrições
    - O objetivo é a maximização
    - O valor ótimo do problema pode ser visualizado através do gráfico presente no script


<h2 id="classificacao">
  
[Classificação](https://github.com/manoelakohler/DataMining/tree/main/03_Classifica%C3%A7%C3%A3o)
  
</h2>

 - **Análise de Crédito Bancário:** Entendimento, pré processamento e classificação de uma base de análise de crédito [`Secom.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/02_Pr%C3%A9Processamento/Secom.ipynb). A base de dados contém 2077 exemplos de créditos concedidos ou não. Possui 11 atributos de entrada e 2 classes de saída. A saída indica se o cliente pagou o empréstimo (=1) ou se não pagou (=0). 
 
    - Medidas resumo para análise exploratória      
    - Pré processamento
      - Normalização
    - Inferência (classificação)
      - SVM
      - Árvore de Decisão
      - Random Forest
    - Tuning de hiperparâmetros
      - GridSearch


 - **Câncer de Mama:** Entendimento, pré processamento e classificação de uma base de análise de crédito [`Credito_SVM.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/03_Classifica%C3%A7%C3%A3o/Credito_SVM.ipynb), [`Credito_AD.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/03_Classifica%C3%A7%C3%A3o/Credito_AD.ipynb) e [`Credito_RF.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/03_Classifica%C3%A7%C3%A3o/Credito_RF.ipynb). Base de dados de características de tumores de mama, como raio, textura, perímetro e área do tumor, totalizando 30 atributos. A base consite em 569 registros de tumores (357 benignas e 212 malignas).
 
    - Medidas resumo para análise exploratória      
    - Pré processamento
      - Normalização
    - Inferência (classificação)
      - KNN
      - Regressão Logística
    - Tuning de hiperparâmetros
      - GridSearch
    - Pós procecssamento
      - Análise das confianças nas inferências para tornar a inferência mais conservadora, ou seja, evitar classificar um tumor maligno como benigno (o pior caso de erro).


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

