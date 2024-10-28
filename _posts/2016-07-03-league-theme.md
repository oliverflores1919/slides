---
title: Mecanicos
layout: post
permalink: /league/
theme: league
 
slides:
 - title: Tipos
   slide-data: Actuadores lineales. Mueven cargas en línea recta (ejes eléctricos, cilindros hidráulicos). 

 
     
 - title: Funcionamiento 
   slide-data: This is second slide

   
 - title: Caracteristicas
   slide-data: This is third slide


 - title: Modo de comuniacion
   slide-data: This is third slide

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
