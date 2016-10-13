---
layout: default
title: Início
---

![Capa do livro](/images/cover-full.png)

Bem-vindo ao sítio web do livro *Cria o Teu Jogo de Computador*!

Queres aprender a programar? Dominar a programação? Fazer os teus próprios jogos, pensados e programados por ti? Então este livro é para ti! Tudo o que precisas é de um computador, ligação à internet e muita imaginação!

Manuel Menezes de Sequeira, fundador do clube de programação CoderDojo LX, primeiro CoderDojo português, e Nélio Codices, fundador do estúdio de videojogos Battlesheep, ensinam-te, passo a passo, a criares o teu próprio jogo de computador usando o Scratch, a linguagem de programação visual ideal para principiantes.

Ao longo deste guia visual irás aprender os princípios mais importantes da programação e desenvolverás, capítulo a capítulo, um jogo inspirado no squash, um desporto de raquetes que se joga entre quatro paredes. Este é apenas o princípio. Depois deste jogo, e com os conhecimentos adquiridos, poderás dar asas à tua criatividade explorando o mundo maravilhoso da programação!

Estás preparado para o desafio?

# Blogue

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>

      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">Subscrição <a href="{{ "/feed.xml" | prepend: site.baseurl }}">RSS</a></p>

</div>
