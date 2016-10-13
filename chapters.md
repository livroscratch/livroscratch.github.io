---
layout: page
title: Capítulos
permalink: /capítulos/
---

O livro *Cria o Teu Jogo de Computador* está dividido em 21 capítulos, cada um dos quais com a sua página web, na qual podes encontrar mais informação, sugestões, dicas e, sobretudo, uma ligação para o projecto do jogo de squash tal como se encontra no final desse capítulo (excepto nos capítulos iniciais, claro, pois neles ainda não há projecto criado):
{% for chapter in site.chapters %}
* {{ chapter.number }} [{{ chapter.title }}]({{ chapter.url }}) – página {{ chapter.page }}
{% endfor%}