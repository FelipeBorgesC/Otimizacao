# Otimização - BI Master PUC-Rio
## Arquivos e dados utilizados ao longo das aula de Otimização no curso BI-Master PUC-Rio.

### Índice
  
- [Introdução OAG](#introducao-oag)
- [Representação, Decodificação e Avaliação](#represent-decod-avaliacao)
- [Operadores Genéticos](#operadores)
- [Restrições](#restricao)
- [Múltiplos Objetivos](#multi-obj)
- [Material Complementar](#complementar)

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


 - **Resolução Exercícios:** Resolução dos exercícios abordados na aula anterior [`Aula 2 Resolvido.xlsx`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%203%20-%20Operadores%20Gen%C3%A9ticos/Resolu%C3%A7%C3%A3o%20Aula%202/Aula%202%20Resolvido.xlsx). Respostas dos exercicios comentados na aula 02 (Breakout Room).
 
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


<h2 id="restricao">
  
[Restrições](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es)
  
</h2>

 - **Aula 04:** Tratamento de Restrições e Aplicações Variadas [`Aula 4 - OAG.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es/Aula%204%20-%20OAG.pdf). Conteúdo abordado sobre o tema de restrições. Tipos de restrições, formas de lidar com as restrições e os mecanismos para corrigir indivíduos inválidos. Além disso, mais algumas aplicações de otimização.
 
    - Tipos de restrições
    - Tratamento de restrições
    - Mecanismos de correção


 - **Resolução Exercícios:** Resolução dos exercícios abordados na aula anterior [`Aula 3 Resolvido.xlsx`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es/Resolu%C3%A7%C3%A3o%20Aula%203/Aula%203%20Resolvido.xlsx). Respostas dos exercicios comentados na aula 03 (Breakout Room).
 
    - Sem elitismo      
    - Com elitismo


- **Solução Telecom:** Solução parte A do exercício de alocação de antenas de telecomunicações [`Solução Telecom A`](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es/Resolu%C3%A7%C3%A3o%20Telecom). Solução do exercício de Telecom da parte A.
 
    - [Excel usando o Solver](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es/Resolu%C3%A7%C3%A3o%20Telecom/Solu%C3%A7%C3%A3o%20Telecom%20-%20Parte%20A.xlsx)
    - [Python usando DEAP](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es/Resolu%C3%A7%C3%A3o%20Telecom/Solu%C3%A7%C3%A3o%20Telecom%20-%20Parte%20A.ipynb)


- **Exercício Fábrica:** Exercicio para praticar sobre produção industrial [`Exercicio Fabrica.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%204%20-%20Tratamento%20de%20Restri%C3%A7%C3%B5es/F%C3%A1brica/Exercicio%20Fabrica.pdf). Exercicio para praticar os conhecimentos de otimização. Identificar os principais pilares para aplicação de um otimizador. Buscar resolver o problema através dos otimizadores mencionados anteriormente.
 
    - Identificação das variáveis     
    - Modelagem da função objetivo
    - Definir as restrições
    - Executar a otimização


<h2 id="multi-obj">
  
[Múltiplos Objetivos](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%205%20-%20M%C3%BAltiplos%20Objetivos)
  
</h2>

 - **Aula 05:** Tratamento de Restrições e Aplicações Variadas [`Aula 5 - OAG.pdf`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%205%20-%20M%C3%BAltiplos%20Objetivos/Aula%205%20-%20OAG.pdf). Conteúdo sobre o tema de múltiplas funções objetivo. Fundamento de múltiplos objetivos, métodos de solução para problemas com múltiplos objetivos. Exemplos de exercícios com mais de um objetivo presente e as diferentes técnicas de solução.


 - **Resolução Exercícios:** Resolução dos exercícios abordados na aula anterior [`Resolução Fábrica e Plantação`](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%205%20-%20M%C3%BAltiplos%20Objetivos/Resolu%C3%A7%C3%A3o%20F%C3%A1brica%20e%20Planta%C3%A7%C3%A3o). E do exercicio [`Resolução Telecom`](https://github.com/FelipeBorgesC/Otimizacao/tree/main/Aula%205%20-%20M%C3%BAltiplos%20Objetivos/Resolu%C3%A7%C3%A3o%20Telecom).
 
    - Plantação e Fábrica - Exercício de otimização com restrições lineares      
    - Telecom parte B e C - Exercício de otimização com restrições não-lineares


<h2 id="complementar">
  
[Material Complementar](https://github.com/FelipeBorgesC/Otimizacao/tree/main/)
  
</h2>

 - **Material Extra:** Diversos exercícios de otimização [`Material extra`](https://github.com/FelipeBorgesC/Otimizacao/blob/main/Aula%205%20-%20M%C3%BAltiplos%20Objetivos/Aula%205%20-%20OAG.pdf). Material extra com diversos exercícios de otimização desde os mais básicos até os mais complexos. Alguns com a resolução em Excel, outros em Python e até mesmo em Matlab.


