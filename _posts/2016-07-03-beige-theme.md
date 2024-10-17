---
title: Electricos
layout: post
permalink: /beige/
theme: beige
 
slides:
 - title: Tipos
   slide-data: • Actuadores lineales. Proporcionan movimiento lineal. Ejemplo. cilindros electricos • Actuadores rotativos. Generan movimiento rotacional. Ejemplo. servomotores • Actuadores de paso a paso. Permiten movimientos precisos en pasos discretos • Actuadores piezoelectricos. Utilizan materiales piezoeléctricos para generar movimiento al aplicar voltaje.
     
 - title: Funcionamiento 
   slide-data: •	Recepción de señales. Reciben señales de control desde un sistema de control o un microcontrolador •	Conversión de energía. Utilizan motores eléctricos (DC, AC, servos) para transformar la energía eléctrica en movimiento •	Movimiento. Generan el movimiento deseado, ya sea lineal o rotacional, según su tipo

   
 - title: Características 
   slide-data: •	Torque. La fuerza de rotación que pueden generar. •	Velocidad. La rapidez con que pueden moverse. •	Precisión. La capacidad de realizar movimientos exactos, especialmente importante en actuadores de paso a paso •	Capacidad de carga. El peso o la carga que pueden mover •	Tamaño y forma. Varían según la aplicación y el diseño.


 - title: Modo de comunicación. 
   slide-data: •	Control analógico. Uso de voltajes o corrientes analógicas para controlar la posición o velocidad. •	Control digital. Utilizan señales digitales (on/off) para accionar el actuador •	Protocolos de comunicación. Como CAN, RS-485, Modbus, y EtherCAT, que permiten la comunicación en redes industriales •	Comunicación inalámbrica. Algunos actuadores modernos pueden integrarse en sistemas IoT, permitiendo el control remoto y la monitorización a través de redes inalámbricas.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
