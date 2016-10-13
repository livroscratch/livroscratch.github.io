---
layout: chapter
title: Contar os toques na bola
number: 12
page: 140
permalink: /livro1/cap12
comments: true
project: http://bit.ly/scratch-cap12
---
Neste capítulo vês dois conceitos muito importantes do Scratch: as variáveis, que são fundamentais na programação imperativa, e as mensagens, que podem ser utilizadas para fazer os vários actores, bem como o palco, comunicarem entre si. Vês que as variáveis podem ser criadas na categoria «Dados» da Paleta, que podem ser mostradas no palco, em monitores, e que podem ser alteradas ou incrementadas. Finalmente, vês que os actores e o palco podem comunicar através da difusão de mensagens, às quais se pode reagir, definindo guiões apropriados.

## Excerto do capítulo

Neste nosso jogo de squash, pelo menos até um dia lhe adicionares um modo com dois jogadores, o objectivo é dar o maior número de toques possível na bola antes de esta tocar na parede traseira.

Para contarmos o número de toques na bola, temos de resolver quatro problemas. O primeiro é o de decidir que actor é responsável por detectar os toques. Deve ser o jogador, ou deve ser a bola, ou ambos? É razoável supor que deveriam ser ambos, pois no mundo real cada um de dois objectos que se tocam sente o efeito desse toque, mas veremos que em Scratch isso coloca algumas dificuldades. O segundo problema é o de saber quem deve ser responsável por manter o contador dos toques. Não parece razoável que seja a própria bola, mas também não parece apropriado delegar essa responsabilidade no jogador, até porque mais tarde ou mais cedo adicionaremos outros jogadores e, tal como no mundo real, será melhor atribuir estas responsabilidades a um árbitro, por exemplo. O terceiro problema é o de saber onde, de facto, deve a entidade responsável guardar o número de toques dados. O quarto e último problema é o de saber como mostrar, no palco, o número de toques dados. A resolução destes problemas passará pela utilização de difusão de mensagens, de variáveis e de monitores de variáveis, como veremos.

…