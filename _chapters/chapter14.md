---
layout: chapter
title: Comandos definidos pelo utilizador
number: 14
page: 170
permalink: /livro1/cap14
comments: true
project: http://bit.ly/scratch-cap14
---
Neste capítulo aprendes a definir blocos personalizados, ou melhor, comandos personalizados, pois o Scratch à data da escrita deste livro não te permitia ainda criar novos repórteres ou predicados. Aprendes também como a definição de blocos personalizados é importante para podermos aplicar o princípio DRY da programação. Vês ainda que há uma diferença importante entre a invocação de um bloco e a execução do guião que o define, e que os valores que colocas nas ranhuras de um bloco ao invocá-lo, os argumentos, ficam acessíveis, durante a execução do guião que define o bloco, em repórteres correspondentes a cada ranhura, repórteres esses a que se chama parâmetros.

## Excerto do capítulo

Um dos princípios fundamentais da programação é o princípio DRY, que significa «don’t repeat yourself» (ou «não te repitas») e que consiste em evitar código igual ou mesmo apenas parecido, tentando, em vez disso, criar pedaços de código que possam ser reutilizados em diferentes circunstâncias. Ora, o guião de movimentação do jogador de squash que criámos no capítulo anterior viola o princípio DRY de forma clara: a cada combinação de teclas detectada correspondem três comandos praticamente iguais. Estas repetições têm muitos problemas:

…