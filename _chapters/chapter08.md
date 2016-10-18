---
layout: chapter
title: Raquetadas
number: "08"
page: 92
permalink: /livro1/cap8
comments: true
project: http://bit.ly/scratch-cap8
---
Neste capítulo aprendes três formas de fazer um actor rodar: uma absoluta, outra relativa e uma terceira fazendo-o apontar em direcção a outro actor. Também vês o que significa o centro de um actor e que implicações isso tem quando se roda um actor de modo a apontar para outro. Aprendes a simular uma raquetada usando sensores de toque, o operador de obtenção de um valor ao acaso, comandos condicionais e, sobretudo, comandos apropriados de alteração da direcção da bola. Vês, finalmente, que no Scratch os blocos arredondados são repórteres, servindo para reportar valores para utilização noutros blocos.

## Excerto do capítulo

Neste capítulo vamos ajudar o actor que faz de bola a desempenhar melhor o seu papel, reagindo a um toque do jogador como se tivesse levado uma raquetada. Afinal, não nos basta que a bola faça «Pop!» quando toca no jogador, especialmente quando passa por ele como se nada fosse…

Antes de o fazer, porém, vamos fazer uma melhoria. Na realidade, a bola que escolhemos não se parece nada com uma bola de squash. Pois, o problema é que escolhemos uma bola de ténis… Que fazer? Se andaste a explorar os recursos que fornecemos, viste que dentro da pasta «Recursos» temos uma bola de squash a sério. Vamos usá-la. Aliás, será a nossa primeira utilização de um recurso. Mas, como o fazer? Criando um novo actor? Não parece uma boa solução, pois não? Já tivemos tanto trabalho a criar guiões para a bola… Provavelmente já te ocorreu a solução: substituir o traje da bola existente. É o que vamos fazer.

…

##Sugestões

* Quando aprenderes sobre variáveis de actor, ou atributos, cria um dessas atributos no jogador chamado «a estâmina»para representar a estâmina ou energia dele. Inicialmente, a estâmina deve ter o valor de 100 (uma percentagem máxima). À medida que o jogador vai andando, a estâmina deve ir reduzindo, sem nunca descer abaixo de zero. Se ele parar, deve ir subindo lentamente, enquanto ele descança, até um máximo de 100. Depois de teres a estâmina do jogador a funcionar, tenta encontrar forma de fazer a «nabice» do jogador ao dar as raquetadas aumentar à medida que a sua estâmina vai descendo.