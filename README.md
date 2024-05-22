![F1](img/F1-Logo-2018.png)
<br />

![HTML5](https://img.shields.io/badge/-HTML5-black?style=flat&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-black?style=flat&logo=css3)
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat&logo=javascript)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github)
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-black?style=flat&logo=visual-studio-code&logoColor=007ACC)


# Construccion de Sitio web F1

## Índice
- [Introducción](#Introducción)
- [Contexto](#Contexto)
- [Desarrollo](#Desarrollo)
- [Datos y Fuentes Externas](#Datos-y-Fuentes-Externas)
- [Tecnologías utilizadas](#Tecnologías-utilizadas)
- [Hosting y Deploy](#Hosting-y-Deploy)
- [Nosotros](#Nosotros)


## Introducción

En este proyecto se simula el rol de un Equipo de desarrolladores de una empresa desarrolladora a la cual la  **Federación Internacional del Automóvil(FIA)**, que es el arbitro que regula las competiciones de automovilismo más importantes, le pide el desarrollo de un sitio web para la competicion de la categoria F1.

El fin de este proyecto es generar una plataforma de informacion que le permita a los usuarios acercarse al deporte y mas especificamente tener a disposicion la informacion relevante mas actualizada o historica de la competencia de la formula 1 y su contexto. 

Se espera como producto final una plataforma con una interfaz amigable, con contenido historico y actual de la competencia y de la categoria, de los equipos y pilotos participantes, como tambien formulario de contacto con la institucion.

## Contexto

La Federación Internacional del Automóvil, también conocida como FIA, es una organización sin ánimo de lucro con sede en la plaza de la Concordia de París, Francia, que incluye 268 organizaciones automovilísticas de 143 países. Fundada en 1904, es mundialmente conocida por regular las competiciones de automovilismo más importantes del mundo, pero su ámbito de aplicación incluye todos los aspectos del automóvil, las carreteras, la movilidad, el medio ambiente o seguridad vial.

### Campeonato Mundial de Fórmula 1
Es la principal competición de automovilismo internacional y el campeonato de deportes de motor más popular y prestigioso del mundo. La entidad que la dirige es la Federación Internacional del Automóvil (FIA). Desde septiembre de 2016, tras la adquisición de Formula One Group, la empresa estadounidense Liberty Media es la responsable de gestionar y operar el campeonato.

A cada carrera se le denomina Gran Premio y el torneo que las agrupa es el Campeonato Mundial de Fórmula 1. La mayoría de los circuitos de carreras donde se celebran los Grandes Premios son autódromos, aunque también se utilizan circuitos callejeros y anteriormente se utilizaron circuitos ruteros. A su vez, los automóviles utilizados son monoplazas con la última tecnología disponible, siempre limitadas por un reglamento técnico; algunas mejoras que fueron desarrolladas en la Fórmula 1 terminaron siendo utilizadas en automóviles comerciales, como el freno de disco.

![Gran Premio](img/Galeria/image4.jpeg)
<br />
> _Gran Premio de Australia._


El inicio de la Fórmula 1 moderna se remonta al año 1950, en el que participaron escuderías como Ferrari, Alfa Romeo y Maserati. Algunas fueron reemplazadas por otras nuevas como McLaren, Williams, Red Bull y otras que volvieron como Mercedes se han alzado varias veces con el Campeonato Mundial de Constructores. Por su parte, los pilotos deben contar con la superlicencia de la FIA para competir, que se obtiene por los resultados en otros campeonatos.

## Desarrollo

Para un seguimiento INTEGRAL del proyecto, disponibilizamos la documentacion del proyecto [aquí](docs/DOCUMENTACION%20PROYECTO.docx)

El sitio web cuenta con 6 paginas desarrolladas con html (Index o pagina de inicio, Equipo, Calendario, Estadisticas, Galeria, Contacto)

![Pagina Principal](assets/img_maquetado.jpg)
<br />
> _Estructura del maquetado usado en el desarrollo del sitio._


### Página de inicio (Index)

Nuestra pagina de inicio brinda una interfaz amigable donde predomina un encabezado de colores fuertes, con los nombres de las secciones del sitio en el comienzo.

Siguiendo el recorrido, vemos que contiene en su parte central (cuerpo de la pagina) distintas imagenes y capturas de noticias importantes de los eventos sobre 
la temática de la F1, y del lado derecho podemos ver que hay 2 imagenes correspondientes al ranking de posiciones en el campeonato por pilotos y por constructores
(o sea por marca lider o equipo)

Llegando al final de la pagina, se pueden ver de manera dinamica las escuderias que participan en el actual campeonato, en conjunto con las distintas redes sociales del
sitio web sobre F1.

<details>
<summary>Ver más</summary>

|                       |
|-----------------------|
| ![Imagen 3](assets/principal1.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |


|                       |
|-----------------------|
| ![Imagen 3](assets/principal2.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |


|                       |                       |
|-----------------------|-----------------------|
| <img src="assets/responsive1.jpg" alt="Imagen 3" style="width:100%; height:auto;"> | <img src="assets/responsive3.jpg" alt="Imagen 3" style="width:100%; height:auto;"> |
| Educación de los padres de los examinados (en Cantidad de frecuencias) | Distribución de los valores de Puntuación Total de los examinados en relación al Nivel de Educación de sus padres |


|                       |
|-----------------------|
| ![Imagen 3](assets/principal3.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |

Puedes consultar el codigo de la pagina en el [script de la página](https://github.com/marco11235813/Proyecto-Codo_a_Codo/blob/main/index.html).
</details>

### Equipo

En esta seccion encontramos los equipos que participan en la categoría. Seleccionando un equipo nos lleva directamente a la seccion donde podemos ver los pilotos principales de cada equipo junto al coche correspondiente a la escuderia.

Tenemos la opcion de acceder a una reseña tanto de cada piloto como del modelo del auto con el que corren la competencia haciendo click sobre ellos.
En caso de querer regresar al inicio de la pagina donde estan los equipos para elegir, podemos hacerlo mediante el botón que se presenta del lado derecho de la pantalla con el logo de F1 en negro.

<details>
<summary>Ver más</summary>

|                       |
|-----------------------|
| ![Imagen 3](assets/equipos1.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |


|                       |
|-----------------------|
| ![Imagen 3](assets/equipos2.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |

  
Puedes consultar el codigo de la pagina en el [script de la página](https://github.com/marco11235813/Proyecto-Codo_a_Codo/blob/main/equipos.html).
</details>

### Cronograma

En esta seccion encontramos la informacion de las fechas de cada Gran Premio de la temporada en conjunto con el circuito correspondiente,
del cual podemos ver una vista del circuito con informacion preliminar.

También esta disponible la posibilidad de desplegar mas informacion seleccinando la opcion 'más info' donde se detalla informacion complementaria

<details>
<summary>Ver más</summary>

|                       |
|-----------------------|
| ![Imagen 3](assets/cronograma3.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |


|                       |
|-----------------------|
| ![Imagen 3](assets/cronograma1.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |

|                       |
|-----------------------|
| ![Imagen 3](assets/cronograma2.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |

  
Puedes consultar el codigo de la pagina en el [script de la página](https://github.com/marco11235813/Proyecto-Codo_a_Codo/blob/main/calendario.html).
</details>

### Estadisticas

Proximamente :D

<details>
<summary>Ver más</summary>
  
Puedes consultar el codigo de la pagina en el [script de la página](https://github.com/marco11235813/Proyecto-Codo_a_Codo/blob/main/estadisticas.html).
</details>

### Galeria

En esta seccion encontramos diferentes tomas de la temporada, en los distintos circuitos, en gradas y boxes, mostrando tanto la carrera como el despliegue de la organizacion, el contexto, los equipos, las diferentes secciones, las gradas y los fanáticos que van a apoyar a la escuderia de su preferencia

<details>
<summary>Ver más</summary>

|                       |
|-----------------------|
| ![Imagen 3](assets/img_galeria.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |

  
Puedes consultar el codigo de la pagina en el [script de la página](https://github.com/marco11235813/Proyecto-Codo_a_Codo/blob/main/galeria.html).
</details>

### Contacto

Esta seccion fue creada para que el usuario tenga la posibilidad de realizar un contacto con el equipo de la FIA por interes de alguna suscripcion, realizar distintas consultas, ofrecer recomendaciones sobre el sitio, y demás posibilidades.

<details>
<summary>Ver más</summary>

|                       |
|-----------------------|
| ![Imagen 3](assets/formulario_contacto1.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |


|                       |
|-----------------------|
| ![Imagen 3](assets/formulario_contacto2.jpg) |
| Distribucion de los valores de Puntuacion Total de los examinados en relacion al Nivel de Educacion de sus padres señalando el tipo de Institucion a la que el alumno asiste |

  
Puedes consultar el codigo de la pagina en el [script de la página](https://github.com/marco11235813/Proyecto-Codo_a_Codo/blob/main/contacto.html).
</details>

## Datos y Fuentes Externas

* Formula 1. https://es.wikipedia.org/wiki/F%C3%B3rmula_1
* Federación Internacional del Automóvil (FIA). https://es.wikipedia.org/wiki/Federaci%C3%B3n_Internacional_del_Autom%C3%B3vil 

## Tecnologías utilizadas
Para el desarrollo de nuestro proyecto, utilizamos los siguientes lenguajes:

* ![HTML5](https://img.shields.io/badge/-HTML5-black?style=flat&logo=html5)
* ![CSS3](https://img.shields.io/badge/-CSS3-black?style=flat&logo=css3)
* ![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat&logo=javascript)

Las herramientas y tecnologias utilizadas son:

* ![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
* ![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github)
* ![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-black?style=flat&logo=visual-studio-code&logoColor=007ACC)

## Hosting y Deploy

Para el hosting de nuestro sitio, utilizamos el servicio de Github Pages, que esta sincronizado directamente a nuestro repositorio Github y se actualiza automaticamente
en base a los cambio que le vayamos haciendo.
Como la idea es continuar el desarrollo de nuestro sitio de manera integral (es decir, continuar el desarrollo del backend y de los aspectos que nos parezcan pertinentes y necesarios),
nos parecio lo mas óptimo utilizar una funcionalidad de nuestro repositorio en un principio, aunque esto se verá supeditado a la disponibilidad de recursos para el despliegue de nuestro sitio 
por parte de la herramienta Github Pages (debemos tomar en cuenta la escalabilidad de nuestro proyecto).

Podemos ver el despliegue de nuestro sitio [aquí](https://marco11235813.github.io/Proyecto-Codo_a_Codo/)

## Nosotros

<div align="center">
  
|      |      |      |      |
| :--: | :--: | :--: | :--: |
| <img src="assets/Foto_perfil_Marco.jpg" width="200" height="200"><br>**Marco**<br>[<img src="assets/linkedin.png" style="width:20px;">](https://www.linkedin.com/in/marco-antonio-caro-22459711b) [<img src="assets/github.png" style="width:20px;">](https://github.com/marco11235813) | <img src="assets/Foto_perfil_Juan.jpg" width="200" height="200"><br>**Juan**<br>[<img src="assets/linkedin.png" style="width:20px;">](http://www.linkedin.com/in/juan-manuel-yunes-mor) [<img src="assets/github.png" style="width:20px;">](https://github.com/jyunesmor) | <img src="assets/Foto_perfil_Leandro.jpg" width="200" height="200"><br>**Leandro**<br>[<img src="assets/linkedin.png" style="width:20px;">](http://www.linkedin.com/in/leandro-mambelli-79834a6b) [<img src="assets/github.png" style="width:20px;">](LINK_GITHUB_INTEGRANTE3) | <img src="assets/Foto_perfil_Lourdes.jpg" width="200" height="200"><br>**Lourdes**<br>[<img src="assets/linkedin.png" style="width:20px;">](https://www.linkedin.com/in/lourdes-pomponio-68ba6a245) [<img src="assets/github.png" style="width:20px;">](LINK_GITHUB_IN)
  
</div>


