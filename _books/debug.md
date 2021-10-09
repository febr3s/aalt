---
title: Antología de manuscritos
layout: page
editorial: "Universidad de la República"
ciudad: "Montevideo"
edicion: 2008
year: 
author: 
- Jacinto Ventura de Molina
- Debug
nacionalidad: "Uruguay"
repositorio: "Conocimiento Libre Repositorio Institucional"
repurl: https://www.colibri.udelar.edu.uy/jspui/
img: antologia-manuscritos-jacinto-ventura.jpg
descarga: https://archive.org/download/seleccion-autores-afrolatinos/Jacinto%20Ventura%20de%20Molina.%20Antologia%20de%20Manuscritos.pdf
biblioteca: 
periodo: "Siglo XIX"
feature:
---



{% for author in page.author %}
<a href="{{ site.baseurl }}/autoras/{{ author | slugify | url_encode }}" title="">{{ author }}</a> + {% endfor %}



