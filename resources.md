---
layout: page
title: Recursos
permalink: "/recursos/"
comments: true
---

Podes descarregar o ficheiro ZIP [`Recursos.zip`](/livro1/Recursos.zip) contendo todos os recursos. Também os podes descarregar abaixo:

{% for resource in site.resources %}
* [`{{ resource.name }}`]({{ resource.url }}): {{ resource.excerpt | remove: '<p>' | remove: '</p>' }}
{% endfor%}