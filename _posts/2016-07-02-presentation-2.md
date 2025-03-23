---
title: Portada
layout: post
permalink: /presentation-2/

 
slides:
 - title: Actuadores
   slide-data: Temas unidad 2
   background: "#e74c3c"
     
 - title: 1. Electricos
   slide-data: Tipos, Funcionamiento, Caracteristicas, Modo de comunicacion 
   background: '#f1c40f'
   
 - title: Mecanicos
   slide-data: Tipos, Funcionamiento, Caracteristicas, Modo de comunicacion 
   background: '#9b59b6'
   
 - title: Hidraulicos
   slide-data: Tipos, Funcionamiento, Caracteristicas, Modo de comunicacion 
   background: '#3498db'
   
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
