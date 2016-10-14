---
layout: chapter
title: Começar, jogar e terminar
number: 15
page: 190
permalink: /livro1/cap15
comments: true
project: http://bit.ly/scratch-cap15
---
Neste capítulo aprendes a criar novos cenários e vês de que forma podemos associar cada cenário a um acto da nossa peça de teatro, ou seja, a um estado do nosso jogo. Vês como podemos mudar de cenário, e por isso mudar de acto na nossa peça, e como podemos detectar essas mudanças de acto para fazer os nossos actores entrarem ou saírem de cena, mostrando-os ou escondendo-os. Também vês como podemos mostrar ou esconder monitores de variáveis nas mudanças de acto. Finalmente, vês como podemos detectar que uma tecla foi carregada, ou seja, como podemos detectar que uma tecla foi primeiro premida e depois largada.

## Excerto do capítulo

Quando o nosso jogo termina, simplesmente deixa de funcionar: tudo fica parado, não é mostrada sequer uma mensagem dizendo que o jogo acabou, não é dada ao jogador a opção de começar novo jogo, etc. Claramente, podemos fazer melhor. Neste capítulo vamos resolver este problema introduzindo uma noção importante: a de que o nosso programa pode estar em diferentes estados e ter uma aparência e comportamento muito diferentes em cada um deles.
Recordas-te de que programar em Scratch é como encenar uma peça de teatro? Pois bem, a nossa peça neste momento só tem um acto. Precisamos de mais. Precisamos de três actos:

* 1.º acto – Introdução ao jogo, onde se avisa que o jogo está pronto a começar e se indica como o começar.
* 2.º acto – Jogo de squash propriamente dito.
* 3.º acto – Fim do jogo, onde se mostram os resultados e onde se dá a possibilidade de voltar ao acto inicial, dando assim ao jogador a hipótese de iniciar novo jogo.

…