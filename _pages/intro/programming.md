---
title: Programação
---
## Computação

Vamos considerar dois momentos da história da computação para contextualizar um pouco como programamos computadores atualmente.

Esta é apenas uma das possíveis narrativas da história da computação e não inclui todos os momentos, pessoas e histórias importantes para o desenvolvimento desse campo.

Por enquanto, vamos voltar aos anos $$1930$$, quando duas ideias matemáticas abstratas começaram a se desenvolver em paralelo: as propriedades binárias de circuitos elétricos (relés) e a Máquina de Turing.

### A Máquina de Turing

O matemático inglês Alan Turing concebeu a [Máquina de Turing](https://pt.wikipedia.org/wiki/M%C3%A1quina_de_Turing) em $$1936$$, durante seu doutorado na Universidade de Princeton.

A Máquina de Turing é um modelo conceitual de computação que descreve uma máquina simples capaz de realizar computações arbitrariamente complexas a partir de um pequeno conjunto de regras.

Em sua forma mais simples, a máquina consiste em uma fita infinita que armazena símbolos que representam dados e instruções. Durante sua operação, a máquina lê um símbolo da fita e, dependendo do valor lido, pode escrever um novo símbolo, mover-se uma posição para ler o próximo símbolo ou simplesmente parar.

Só isso.

<div class="scaled-images">
  <img src="{{ '/assets/images/intro/turing-machine.jpg' | relative_url }}">
</div>
*Representação simplificada de uma Máquina de Turing com o conjunto de instruções $$\{$$ $$X$$, $$Y$$, $$\varnothing$$, $$\forall$$ $$\}$$*

Esse modelo simples, em que instruções e dados são lidos e escritos no mesmo lugar, ainda é usado hoje. É ele que permite aos computadores realizar um número praticamente infinito de tarefas a partir de um conjunto finito de instruções.

### Chaves Elétricas

Em $$1937$$, Claude Shannon escreveu sua dissertação de mestrado, intitulada [*A Symbolic Analysis of Relay and Switching Circuits*](https://pt.wikipedia.org/wiki/A_Symbolic_Analysis_of_Relay_and_Switching_Circuits), no MIT. Nesse trabalho, Shannon mostrou como otimizar circuitos de relés telefônicos usando uma forma de álgebra baseada em apenas dois valores: $$1$$ e $$0$$.

Ele também demonstrou que esse tipo de matemática, chamado [Álgebra Booleana](https://pt.wikipedia.org/wiki/%C3%81lgebra_booliana), podia ser implementado usando chaves elétricas com dois estados possíveis: ligada e desligada.

As propriedades dessa álgebra binária facilitam a construção de circuitos complexos a partir de blocos lógicos básicos e reutilizáveis. Isso significa que diferentes tipos de cálculos e problemas lógicos podem ser resolvidos usando circuitos físicos relativamente simples de conceber, construir e expandir.

<div class="scaled-images">
  <img src="{{ '/assets/images/intro/shannon-switches.jpg' | relative_url }}">
</div>
*Diferentes representações de operações lógicas implementadas por Shannon usando interruptores elétricos.*

Isso abriu caminho para a construção física de máquinas de computação capazes de manipular $$0$$s e $$1$$s para representar instruções, dados e estados. Esse princípio continua sendo usado hoje na construção de computadores cada vez mais complexos.

## Programação

Nessas duas histórias, podemos observar não apenas o início do que mais tarde se transformaria em sistemas de computação cada vez mais sofisticados, mas também o surgimento de conceitos que continuam importantes até hoje quando queremos dizer a um computador o que fazer.

Os tipos de tarefas que um computador pode realizar evoluíram constantemente desde os anos $$1930$$. Mas como especificamos aos computadores o que fazer ainda é fortemente influenciado por conceitos como memória, instruções, estado interno, loops, lógica booleana e circuitos binários. Esses conceitos remontam a uma época em que aquilo que entendemos hoje por *computador* ainda nem sequer era fisicamente possível.

Programar, ou codificar, é a arte e ciência de dizer a um computador para fazer algo, fornecendo dados e sequências de instruções que especificam exatamente o que ele deve fazer com esses dados.

Algumas formas de programação de computadores já existiam desde pelo menos os anos $$1830$$, quando Ada Lovelace escreveu um programa para calcular uma sequência de números de Bernoulli usando uma máquina mecânica. Essas máquinas eram programadas por meio de cartões perfurados: pedaços de papelão com furos que eram introduzidos na máquina em momentos específicos. A presença ou ausência de furos em determinadas posições dos cartões determinava quais conexões mecânicas eram estabelecidas, fazendo com que a máquina executasse operações específicas.

Alguma forma de programação de computadores já acontecia desde pelo menos os anos $$1830$$, quando [Ada Lovelace](https://pt.wikipedia.org/wiki/Ada_Lovelace) escreveu um programa para calcular uma sequência de números de Bernoulli em um computador mecânico. Computadores mecânicos eram programados usando pedaços de papelão com furos que eram alimentados na máquina em momentos específicos. Os furos, ou a ausência deles, em posições específicas dos cartões, determinavam se certas conexões mecânicas eram feitas, e isso é o que fazia o computador se comportar de uma maneira específica.

Foi somente nos anos $$1940$$, com o avanço dos computadores eletrônicos, que se tornou possível escrever e executar programas em computadores eletrônicos. Os comandos dados a essas máquinas, porém, ainda eram expressos basicamente por meio de sequências de sinais elétricos que representavam os estados ligado e desligado de interruptores e outros componentes.

## Linguagens

Podemos rastrear as origens das linguagens de programação que usamos hoje até o final dos anos $$1950$$, com o trabalho da cientista da computação e almirante da Marinha dos Estados Unidos [Grace Hopper](https://pt.wikipedia.org/wiki/Grace_Hopper). Hopper ajudou a demonstrar que palavras e expressões em inglês poderiam ser usadas para descrever instruções de programas de forma mais abstrata, que depois seriam traduzidas em sequências de sinais elétricos representando os estados ligado e desligado dos componentes de computadores específicos.

Isso contribuiu para o surgimento de linguagens de programação de *alto nível* como FORTRAN, ALGOL e COBOL. Essas linguagens permitiam escrever programas usando uma sintaxe mais próxima da linguagem humana e menos dependente das características específicas de *hardware*.

O termo *alto nível*, nesse contexto, é relativo. Ele é usado para descrever o grau de abstração oferecido por uma linguagem de programação e o quanto sua sintaxe se aproxima de uma linguagem natural, em oposição às instruções específicas de uma máquina. O que era considerado *alto nível* nos anos $$1950$$ e $$1960$$ certamente não é o mesmo que consideramos *alto nível* hoje.

A maioria das linguagens de programação populares atualmente possui sintaxes bastante expressivas, nas quais comandos relativamente simples podem se transformar em sequências muito mais longas de instruções para o computador executar. Algumas dessas linguagens sequer exigem uma etapa explícita de tradução para transformar o código legível por humanos em instruções executáveis pelo computador.

## JavaScript e p5.js

Uma dessas linguagens é o JavaScript.

JavaScript é uma linguagem de programação que, tradicionalmente, é classificada como interpretada. Isso significa que, em vez de precisarmos compilar nosso código antecipadamente, ou seja, traduzi-lo para instruções específicas de uma máquina, contamos com um outro programa, chamado de interpretador ou *runtime*, que é responsável por executar nosso código.

Uma das principais razões para a popularidade do JavaScript é que, na maioria dos casos, o programa responsável por executar nosso código é um navegador. A maioria dos computadores, celulares, relógios inteligentes e outros dispositivos possui algum tipo de navegador ou ambiente capaz de executar JavaScript. Isso significa que não precisamos nos preocupar diretamente com as especificidades do hardware em que nosso programa vai rodar e, na maioria dos casos, tampouco com o sistema operacional ou outras questões de compatibilidade.

Por ser uma linguagem de programação de alto nível e multiparadigma, JavaScript permite criar diferentes tipos de programas usando diferentes técnicas e estilos de programação. Como acontece com a maioria das linguagens de programação de uso geral, também podemos estender suas funcionalidades por meio de bibliotecas, que oferecem ferramentas e abstrações para facilitar a realização de tarefas específicas.

A biblioteca [p5.js](https://p5js.org/) é uma biblioteca JavaScript voltada para creative coding, com foco em tornar a programação mais acessível e inclusiva. Ela estende as funcionalidades básicas do JavaScript e facilita a criação de experiências audiovisuais, permitindo trabalhar com imagens, desenhos, vídeos, sons e outros recursos diretamente em uma página web, dentro do navegador.
