---
title: Electricos
layout: post
permalink: /beige/
theme: beige
 
slides:
 - title: Tipos
   slide-data: Actuadores lineales. Proporcionan movimiento lineal. Ejemplo. cilindros electricos - Actuadores rotativos. Generan movimiento rotacional. Ejemplo. servomotores - Actuadores de paso a paso. Permiten movimientos precisos en pasos discretos - Actuadores piezoelectricos. Utilizan materiales piezoeléctricos para generar movimiento al aplicar voltaje.
     
 - title: Funcionamiento 
   slide-data: This is second slide

   
 - title: Características 
   slide-data: This is third slide


 - title: Modo de comunicación. 
   slide-data: This is third slide

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
