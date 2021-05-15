Competências com * são consideradas opcionais/avançadas e com ** são medalhas.


Python
======

## [py-elementary](auto)
### Resolver os exercícios da ilha elementary do check.io

* Deve resolver pelo menos 14 exercícios


## [py-home](auto)
### Resolver a ilha "home" do check.io

* Deve resolver pelo menos 14 exercícios


## [py-checkio*](auto)
### Chegar no nível 10+ do check.io


## [py-bug*]
### Encontrar e reportar bug não trivial em projeto relacionado ao conteúdo da disciplina. 

* Bug pode ser identificado no Lark, Ox ou em algum outro projeto relacionado a compiladores.
* É necessário comunicar o bug utilizando o sistema de issues do Github e fornecer as informações necessárias para reprodução do mesmo que forem requisitadas pelo desenvolvedor.
* Pedido de novas funcionalidades não serão considerados.


## [py-pr*]
### Realizar um pull request para projeto utilizado na disciplina ou relacionado ao conteúdo de compiladores. 

* PR pode ser aceito no Lark, Ox ou em algum outro projeto relacionado à disciplina.


## [py-package*]
### Empacotar o projeto de programação desenvolvido na disciplina usando boas práticas de empacotamento e distribuição da comunidade. 

* Publicar o projeto no PyPI (ou equivalente, se preferir utilizar outra linguagem).
* Criar repositório público com boas práticas de publicidade.
* Instrumentar repositório com testes unitários com boa cobertura


Expressões regulares e análise léxica
=====================================

## [re-ler](auto)
### Compreender e elicitar a linguagem gerada por expressões regulares simples. 

* Identificar exemplos clássicos de linguagens regulares escritas como regex.
* Identificar exemplos simples gerados pela combinação de 2 a 3 operadores.


## [re-basico](auto)
### Criar padrões simples a partir dos operadores básicos de sequência, alternativas, repetição e epsilons. 

* Criar expressões regulares para alguns exemplos clássicos.
* Escrever operações com opcionais, repetições de 1 ou mais casos a partir dos operadores clássicos.


## [re-prog](manual)
### Converter e associar expressões regulares da teoria de compiladores com expressões regulares escritas em linguagem de programação. 

* Criar e manipular expressões regulares em Python ou outra linguagem de programação.
* Escrever expressões do livro texto na sintaxe utilizada em linguagens de programação.


## [re-pat](auto)
### Aplicar expressões regulares para encontrar padrões de texto simples em um documento. 

* Utilizar regex em um programa de computador para identificar padrões de texto.
* Conhecer métodos como match, search, split e finditer.


## [re-grp](auto)
### Aplicar expressões regulares e utilizar grupos e sub-padrões para extrair informação a partir de um texto. 

* Conhecer sintaxe para criação de grupos nomeados e posicionais.
* Obter grupos de um objeto de match.
* Identificar sub-padrões de uma string maior a partir de expressões regulares.


## [lex-ler](auto)
### Compreender a motivação e mecanismos da análise léxica. 

* Separar um código fonte em tokens e lexemas.
* Identificar os diferentes tipos de lexemas.
* Identificar lexemas em linguagens de programação reais como Python ou C.


## [lex-re](auto)
### Criar um analisador léxico baseado em expressões regulares utilizando alguma biblioteca de apoio.

* Criar analisador léxico a partir da declaração das expressões regulares.
* Resolver conflitos de procedência devido à ordem das declarações.
* Conhecer os mecanismos da biblioteca utilizada (seja ela Lark, Ox, PLY, etc).


## [re-adv*]
### Utilizar operadores avançados de expressões regulares, look-ahead positivo e negativo.

* look-behind positivo e negativo.
* repetições não-gulosas.


## [lex-prog*]
### Criar um analisador léxico utilizando apenas recursos básicos do Python. Implementar algoritmo genérico baseado em expressões regulares.

* Tratar casos especiais como comentários e palavras reservadas.
* Tratar precedência de expressões.


## [re-tools*]
### Utilizar expressões regulares em ferramentas de programção. Utilizar expressões regulares para encontrar padrões e realizar substituições em editor de código.

* Utilizar expressões regulares em ferramentas de busca do Linux como grep e variantes.


Gramáticas livres de contexto
=============================

## [cfg-classicas](auto)
### Montar e reconhecer gramáticas livres de contexto para exemplos clássicos de linguagens simples . 

* Exemplos: a^n b^n, parênteses pareados e outras.
* Expressar e compreender estas linguagens em sintaxe BNF.


## [cfg-bnf](auto)
### Entender e reconhecer operações básicas de gramática generativa na notação BNF. 

* Reconhecer linguagens regulares na forma de gramática livre de contexto.
* Identificar quando uma gramática livre de contexto corresponde a uma linguagem regular. 


## [cfg-ebnf](auto)
### Entender operadores na notação EBNF. 

* Reconhecer sintaxe e operdores em sua implementações no Lark.
* Realizar transformação de operações EBNF para suas respectivas representações em BNF.


## [cfg-list](auto)
### Representar sequências em notação BNF e EBNF. 

* Representar sequências com separadores.
* Diferenciar separadores intercalados de listas com último separador opcional.
* Representar listas com delimitadores.


## [cfg-op](auto)
### Representar precedência de operadores em gramática (E)BNF. 

* Reconhecer relação entre gramática e precedência.
* Definir gramática para obter uma precedência desejada.
* Implementar corretamente exemplos clássicos como uma calculadora.


## [cfg-cst*]
### Relacionar gramática com a representação do código como árvore concreta . 

* Relacionar regras de produção com o formato de uma árvore sintática concreta.
* Derivar árvores sintáticas concretas para um texto a partir de uma gramática.


## [cfg-ast](auto)
### Criar árvore sintática 

* Utilizar transformers do Lark ou outro mecanismo para registrar métodos que constroem nós da árvore sintática.
* Realizar a transformação de tipos atômicos como números e strings.


## [cfg-reduce](auto)
### Utilizar transformers para obter resultados a partir da análise sintática 

* Construir um transformer para obter diretamente resultados da interpretação do código.
* Implementar linguagem simples no escopo de uma calculadora avançada ou algo do gênero.


## [cfg-sexpr*]
### Dominar a representação de árvores sintáticas abstratas por S-Expressions. 

* Entender S-Expression como uma linearização de uma árvore.
* Produzir código Python para representar árvores sintáticas como listas, tuplas ou estruturas semelhantes


Autômatos
=========

## [dfa-repr](manual)
### Entender o mecanismo de operação de um autônomo determinístico finito. 

* Definir autômato na forma gráfica e compreender o mecanismo de operação.
* Compreender a influência do estado inicial, alfabeto de entrada e estados de aceite na operação de um autômato.


## [dfa-prog*]
### Implementar um algoritmo para a execução de autômatos determinísticos finitos em linguagem de programação. 

* Implementar código para autômatos específicos.
* Generalizar a implementação para autômatos arbitrários.
* Traduzir autômatos escritos como diagramas para código.


## [nfa-repr](manual)
### Entender o mecanismo de operação de um autônomo não-determinístico finito. 

* Definir autômato na forma gráfica e compreender o mecanismo de operação.
* Compreender as diferenças de operação com relação a um autômato determinístico.
* Compreender a influência do estado inicial, alfabeto de entrada e estados de aceite na operação de um autômato.


## [nfa-thompson](manual)
### Criação de NFA para representação de Regex na construção de Thompson. 

* Compreender limitações da abordagem intuitiva.
* Entender a propriedade de composição da construção de Thompson.
* Realizar corretamente a construção de Thompson para expressões regulares arbitrárias.


## [nfa-epsilon](manual)
### Conversão de NFA-e para NFA. 

* Compreender que ambos possuem o mesmo poder computacional.
* Ser capaz de converter NFA-e para NFA sem transições epsilon


## [nfa-dfa](manual)
### Conversão de NFA para DFA. 

* Compreender que ambos possuem o mesmo poder computacional.
* Realizar a conversão de um NFA no DFA correspondente.indentificar
* Traduzir autômatos escritos como diagramas para código. 


Algoritmos de análise sintática
===============================


## [rd-prog*]
### Implementar gramática simples usando descida recursiva. 

* Compreender como mapear regras de produção em chamadas recursivas de funções.
* Conhecer limitações mais comuns como recursão à esquerda.
* Implementar corretamente programa que realiza análise sintática de linguagens ou formatos simples (ex.: listas ou objetos) 


## [ll1-conv*]
### Criação da tabela de transição para o algoritmo LL(1). 

* Identificar conjuntos FIRST e FOLLOW associados a cada regra de produção. 
* Criar da tabela a partir dos conjuntos FIRST para gramáticas sem epsilons.
* Indentificar a existência de conflitos em uma gramática.
* Identificar casos problemáticos tradicionais como recursão a esquerda.


## [ll1-epsilon*]
### Tratar caso especial do LL(1) em gramática que possui epsilons. 

* Criar tabela de transição na existência de produções vazias de uma gramática.
* Identificar conflitos em produções vazias.


## [ll1-err*]
### Resolução de conflitos simples em gramáticas para algoritmo LL(1). 

* Consertar recursões a esquerda simples.
* Implementar calculadora de expressões de uma linguagem (tanto como calculadora independente, quanto como parte de uma linguagem maior).


## [ll1-prog*]
### Implementação de um algoritmo LL(1) a partir de uma tabela de transição pronta. 

* Criar programa capaz de validar uma sentença utilizando o algoritmo LL(1)
* Implementar programa que retorne a árvore sintática de uma expressão utilizando o LL(1)


Arquitetura de compiladores e interpretadores
=============================================


## [comp-org](manual)
### Compreender as etapas tradicionais de análise do código em um compilador. 

* Conhecer o papel e função das etapas de análise léxica, análise sintática, análise semântica, otimização e geração de código.
* Conhecer superficialmente como esse mecanismo funciona em alguma linguagem real e possuir elementos conceituais para comparar estas etapas em diferentes linguagens.


## [comp-vs-interp](manual)
### Compreender as principais diferenças entre um compilador e um interpretador. 

* Situar um interpretador no contexto da arquitetura tradicional de compiladores.
* Compreender a distinção entre um interpretador de árvores sintáticas e uma máquina virtual.
* Identificar, entre as linguagens de programção mais conhecidas, quais são tradicionalmente interpretadas e quais são compiladas. 


## [parser-fmt*]
### Compreender a relevância das técnicas de compiladores no processamento de arquivos.

* Entender o papel da análise léxica e sintática no processamento de arquivos estruturados.
* Ler e compreender uma gramática relacionada a um formato de arquivo.
* Ser capaz de elicitar a gramática associada a formatos simples como JSON e CSV.  


## [proj-calc](auto)
### Implementar um interepretador para DSL com separação explícita entre etapas de análise léxica, sintática e avaliação das árvores sintáticas. 

* Linguagem deve implementar operações básicas no seu domínio (ex.: calculadora com as 4 operações, parênteses e chamada de funções)
* Cada etapa deve estar separada explicitamente no código ou pela organização imposta pela biblioteca de implementação (ex.: Lark)
* Interpretação do código pode ser feita a partir da árvore sintática.


## [semantica*]
### Implementar alguma etapa de análise semântica em projeto de compilador ou interpretador. Identificar inconsistência de tipos.

* OU Identificar bugs e erros de programação comuns em código sintaticamente válido.


Projeto de programação
======================


## [proj-dsl-gramatica*]
### Criar uma linguagem de domínio específico usando as técnicas aprendidas na matéria. 

* Criar um analisador sintático para a linguagem.
* Linguagem deve possuir uma semântica bem definida.
* Linguagem possui estruturas gramaticais não triviais (algo mais sofisticado que LISP e Brainfuck).
* Pode ser uma linguagem original ou a implementação de uma linguagem já existente.


## [proj-interp*]
### Criar interpretador de linguagem de domínio específico. 

* Interpretador para linguagem sintaticamente simples e que preserve a maior parte da semântica do Python ou da linguagem de implementação (ex: Lispy)
* Linguagem deve conter estruturas de controle básicas (if/while/sequências) ou (condicionais e funções e recursão)
 

## [proj-vm*]
### Criar interpretador de linguagem de domínio específico com arquitetura de máquina virtual. 

* Implementar o compilador para bytecodes (ou outra representação binária).
* Criar interpretador da linguagem de bytecode.  


## [proj-comp*]
### Criar compilador para linguagem de domínio específico. 

* Criar compilador que emite código em uma liguagem de destino comum como Python, C ou Javascript.


## [proj-codigo**]
### Projeto final apresenta ótima qualidade de código. 

* Projeto utiliza boas e apresenta boa arquitetura.
* Código legível e documentado nas partes onde existe ambiguidade. 


Genérico
========


## [conteudo-arte**]
### Produziu material com alta qualidade estética/artística. 

* Criou material de estudo, ou material para o projeto final com expressão de qualidade artística.



## [conteudo-texto**]
### Produziu material com qualidade de escrita. 

* Criou material de estudo, ou material para o projeto final com ótima qualidade de escrita. 


## [tutor*]
### Produziu material didático. 

* Criou material de estudo na forma de texto, vídeo ou outro formato eletrônico.
