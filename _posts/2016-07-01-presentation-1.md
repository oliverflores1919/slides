---
title: Portada
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: DES- DE APLIC.WEB
   slide-data: Ismael Jimenez Sanchez
     
 - title: Alumno
   slide-data: Flores Hernandez Oliver Benjamin

 - title: Tarea #998
   slide-data: Crear una GitHub page a partir de un template de Jekyll
  
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
