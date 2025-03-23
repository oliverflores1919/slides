---
title: 
layout: Aplicaciones Web
permalink: /beige/
theme: beige
 
slides:
 - title: Que son las aplicaciones web?
   slide-data: • Las aplicaciones web son programas o software que se ejecutan en un navegador web, en lugar de en el sistema operativo de un dispositivo como ocurre con las aplicaciones tradicionales. Estas aplicaciones requieren una conexión a Internet para funcionar, ya que se accede a ellas a través de la web

Algunos ejemplos comunes de aplicaciones web incluyen
Correo electrónico (como Gmail o Outlook)
Redes sociales (como Facebook, Twitter o Instagram)
Procesadores de texto (como Google Docs)

Herramientas de colaboración (como Trello, Slack o Asana)
Las aplicaciones web suelen estar basadas en tecnologías como HTML, CSS y JavaScript, y se ejecutan en servidores remotos, lo que permite a los usuarios acceder a ellas desde cualquier lugar y en cualquier dispositivo con conexión a Internet, sin necesidad de instalar software adicional

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
