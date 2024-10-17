---
title: Portada
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: Sistemas programables
   slide-data: Ismael Jimenez Sanchez
     
 - title: Alumno
   slide-data: Flores Hernandez Oliver Benjamin

 - title: Unidad 2
   slide-data: Actuadores
  
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
