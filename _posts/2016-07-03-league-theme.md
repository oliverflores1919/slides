---
title: Mecanicos
layout: post
permalink: /league/
theme: league
 
slides:
 - title: Tipos
   slide-data: • Actuadores lineales. Mueven cargas en línea recta (ejes eléctricos, cilindros hidráulicos). • Actuadores rotativos. Generan movimiento de rotación (motores eléctricos, servomotores). • Actuadores neumáticos. Utilizan aire comprimido para el movimiento. • Actuadores hidráulicos. Usan fluidos a presión para generar movimiento. 

 - title: Funcionamiento 
   slide-data: Los actuadores convierten energía (eléctrica, hidráulica, neumática) en movimiento mecánico. En los eléctricos, un motor convierte energía eléctrica en rotación; en los hidráulicos, un fluido presurizado impulsa un pistón.

   
 - title: Caracteristicas
   slide-data: 


 - title: Modo de comuniacion
   slide-data: 

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
