---
title: Hidraulicos
layout: post
permalink: /moon/
theme: moon
 
slides:
 - title: Tipos
   slide-data: • Cilindros hidráulicos. Dispositivos que convierten la presión hidráulica en movimiento lineal. • Motores hidráulicos. Transforman la energía hidráulica en movimiento rotativo. • Actuadores de doble efecto. Permiten movimiento en ambas direcciones. • Actuadores de simple efecto. Funcionan en una sola dirección y utilizan un resorte para regresar.
 
     
 - title: Funcionaniento
   slide-data: Los actuadores hidráulicos funcionan mediante la presión de un fluido (normalmente aceite) que se envía a través de un sistema de tuberías. Cuando el fluido presurizado entra en el actuador, provoca el movimiento del cilindro o motor. Este movimiento puede ser lineal o rotativo, dependiendo del tipo de actuador.

   
 - title: Caracteristicas
   slide-data: • Fuerza. Pueden generar grandes fuerzas debido a la alta presión del fluido. • Precisión. Ofrecen un control preciso del movimiento. • Rapidez. Pueden moverse rápidamente dependiendo del sistema de control y la presión. • Durabilidad. Generalmente tienen una larga vida útil si se mantienen adecuadamente. • Flexibilidad. Se pueden diseñar para diversas aplicaciones industriales.


 - title: Modo de comunicacion
   slide-data: • Control manual. Operadores utilizan válvulas y palancas. • Control automático. Sensores y controladores electrónicos regulan la presión y el flujo. • Redes de comunicación. Integración con sistemas industriales a través de protocolos como CANopen, Modbus, o Profibus para monitorizar y controlar actuadores desde un sistema central.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
