---
title: Portada
layout: post
permalink: /presentation-2/

 
slides:
 - title: Desarrollo de aplicaciones web
   slide-data: Ismael Jimenez Sanchez
   background: "#e74c3c"
     
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
