---
title: Aplicaciones Web
layout: post
permalink: /beige/
theme: beige
 
slides:
 - title: Que son las aplicaciones web?
   slide-data: • Las aplicaciones web son programas o software que se ejecutan en un navegador web, en lugar de en el sistema operativo de un dispositivo como ocurre con las aplicaciones tradicionales. Estas aplicaciones requieren una conexión a Internet para funcionar, ya que se accede a ellas a través de la web.
      
 
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
