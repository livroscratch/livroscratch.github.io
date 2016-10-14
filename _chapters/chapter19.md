---
layout: chapter
title: Em foco
number: 19
page: 252
permalink: /livro1/cap19
comments: true
project: http://bit.ly/scratch-cap19
---
Neste capítulo aprendes uma forma simples de criar um actor «satélite» de outro, fazendo-o constantemente ir para a posição desse actor. Vês também como usar a ideia de camadas para controlar que actores ficam à frente e que actores ficam atrás, ou seja, que actores ficam a tapar outros actores, quando as suas posições se sobrepõem. Vês ainda que podes tornar um actor mais ou menos transparente usando o efeito fantasma. Aprendes finalmente o que é um atributo de um objecto (actor ou palco) e de que forma um actor pode aceder aos atributos de outro actor, usando um repórter sensor especial, concebido para esse efeito.

## Excerto do capítulo

O jogador só pode dar toques na bola legalmente logo depois de o jogo começar ou após a bola ter ressaltado na parede frontal. Sempre que der um toque ilegal, o jogo termina. Isso significa que é importante saber se já demos ou não um toque na bola sem que esta tenha ressaltado na parede frontal. Isso é informação importante para os nossos utilizadores. Como lhes dar essa informação de forma efectiva e apelativa? O que propomos é que usemos um foco de luz, tal como nos espectáculos, para seguir o nosso jogador pelo campo, e que a cor desse foco seja amarela quando o jogador pode dar toques legais na bola e vermelha quando o jogador não puder dar toques legais na bola.

Uma solução para fazermos o que queremos seria adicionar o foco aos trajes do jogador, mas o foco não é parte do jogador, na realidade. Além disso, não colocar o foco como parte do jogador, mas sim como algo que o segue, permite-nos facilmente prescindir do foco quando ele não for necessário. Assim sendo, vamos fazer com que o foco seja um novo actor.


…