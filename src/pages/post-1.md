---
layout: ../layouts/Layout.astro
title: "Ciberseguridad"
author: "Catalina Castillo "
date: "09 July 2023"
---


*Tipos de Ciberseguridad:
Ofensiva y Defensiva**

Ciberseguridad ofensiva:
Irrumpir en los sistemas informáticos, explotar errores de software y encontrar lagunas en las aplicaciones para obtener acceso no autorizado.

*Para vencer a un pirata informatico debe comportarse como un pirata informatico!


La mayoría de las compañias utilizan un portal de administración.
Le entregan a su equipo credenciales para acceder a la administración y realizar tareas básicas.
En el caso de un banco los empleados necesian transferir dinero a la cuenta de los clientes.
La mayoría de estas páginas no son privadas permitiendo a los atacantes encontrar paginas que muestres o den acceso a los controles del administrador o información sensible. 

* * *
## Aplicaciones utilizadas: 

**GoBuster:
Command-line security aplication.**

*gobuster -u http://fakebank.com -w wordlist.txt dir*

Este comando nos permite encontrar potenciales páginas ocultas dentro de las páginas webs

-u: se utiliza para indicar el sitio web que estamos escaneando.

 -w: toma una lista de palabras para iterar y encontrar páginas ocultas.
 
 GoBuster escanea el sitio con cada palabra en la lista encontrando páginas que existen el sitio. Este muestra en una lista con nombres de páginas y directorios con status. 
 
 ![ec0710e7407c95a66cad2c46deec9ed1.png](:/e2401a245d4a4479b93f9fd6f6cef96e)
 
* * *

**Centro de Operaciones de Seguridad (SOC):** (Blue Team)

Es el equipo de profesionales de seguridad cibernética que monitorea la red y sus sistemas para detectar eventos maliciosos de seguridad.

**Vulnerabididades**: Aplicar actualizaciones y parche adecuado según la vulenarbilidad. 
 **Violaciones de política:** Conjuntos de reglas necesarias para la protección de red y los sistemas. *Ej: carga de datos confidenciales de una empresa en una nube*
 **Actividad no autorizada:** Robo de credenciales para iniciar sesión en red. **SOC** se encarga de detectar el evento y bloquearlo antes de que se produzcan más daños.
 Instrusiones en red: Siempre existe la posiblidad de una intrusión ya sea con un simple click a un enlace malicioso. De sebe detectar lo antes posible para evitar mayores daños.


**Inteligencias de Amenazas:** 
Información recopilada de enemigos reales y potenciales.
Una amenaza es cualquier acción que puede interrumpir o afectar negativamente a un sistema. La inteligencia de amenaza tiene como objetivo recopilar la mayor cantidad de información para ayudar a la empresa a prepararse mejor contra posibles adversarios.
*El propósito sería lograr una defensa informada por la amenaza*
Diferentes empresas tienen diferentes adversarios. 
Existen distintos tipos de adversarios con distintos objetivos, conseguir datos de clientes, detener la producción de una refinería de petroleo (más estratégico), ejercito cibernético estado-nación que trabaja por razones políticas. Según la empresa (objetivo), podemos esperar adversarios.

![63df37782f1328098bc21c700451ff65.png](:/101779faa5884c7d952fd7105ce275e2)

La inteligencia necesita datos. Los datos tienen que ser recopilados, procesados y analizados. La recopilación de datos se realiza a partir de fuentes locales, como registros de red, y fuentes públicas, como foros. El procesamiento de datos tiene como objetivo organizarlos en un formato adecuado para el análisis. La fase de análisis busca encontrar más información sobre los atacantes y sus motivos; además, tiene como objetivo crear una **lista de recomendaciones y pasos prácticos.**

Aprender sobre tus adversarios te permite conocer sus tácticas, técnicas y procedimientos. Como resultado de la inteligencia de amenazas, identificamos al actor de amenazas (adversario), predecimos su actividad y, en consecuencia, podremos mitigar sus ataques y preparar una estrategia de respuesta.




