---
layout: chapter
title: Começar da forma certa
number: 11
page: 132
permalink: /livro1/cap11
comments: true
project: http://bit.ly/scratch-cap11
---
Neste capítulo vês a importância da inicialização para os nossos programas e aprendes a criar guiões de inicialização simples. Vês também como inicializar o tamanho, a posição, a direcção, o volume de som e o estilo de rotação de um actor. Vês, finalmente, como podemos copiar um guião de um actor para outro actor do teu programa.

## Excerto do capítulo

Neste capítulo vamos tratar de um assunto muito importante: a inicialização. Chamamos inicialização ao processo de colocar o nosso programa num estado apropriado quando ele se inicia ou quando ele se reinicia devido a um evento importante no jogo, como uma bola fora, que leva ao final de uma partida de squash.

Neste momento há várias inicializações por fazer, tanto para a bola como para o jogador de squash. No caso do jogador, queremos que ele comece o jogo numa posição adequada, virado para a parede frontal do campo e com um tamanho mais adequado em proporção com o campo. No caso da bola, queremos que ela comece o jogo também com um tamanho mais apropriado, com um volume de som mais baixo (para o «Pop!» que produz não ser tão incomodativo), e movendo-se para a direita a partir de uma posição adequada.

Para resolver estes problemas, vamos criar um guião de inicialização em cada um dos nossos actores. Esta solução não é a solução ideal, pois podemos querer garantir que só depois de completa a inicialização se iniciam as restantes acções do jogo. Mas teremos oportunidade mais tarde de melhorar o nosso projecto.

…