# Propuesta TP DSW

## Grupo
### Integrantes
* 51467 - Martin Garcia
* 54238 - Ivan Slavkes
* 54299 - Antonella Minetti
* 47243 - Ignacio Anastasini

### Repositorios
* [Frontend app]()
* [Backend app]()

## Tema
### Descripción
Una aplicación para encontrar equipo o rival para un partido de futbol.
Un "Admin" crea la sala y los demas se pueden unir / solicitar unirse para jugar ese partido.

### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Admin<br>2. CRUD Jugador<br>3. CRUD Partido<br>4. CRUD Cancha|
|CRUD dependiente|1. CRUD Partido {depende de} CRUD Cancha<br>2. CRUD Partido {depende de} CRUD Admin|
|Listado<br>+<br>detalle| 1. Listado de partidos filtrados por localidad, posición, tipo, dia y hora => detalle CRUD Partido<br> 2. Listado de jugadores filtrados por calificación, favoritos, posicion y edad|
|CUU/Epic|1. Registro de un usuario.<br>2. Crear sala para un partido<br>3. Unirse a un partido|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Localidad<br>3. CRUD Partido<br>4. CRUD Cancha<br>5. CRUD Notificacion|
|CUU/Epic|1. Registro de un usuario.<br>2. Crear sala para un partido<br>3. Unirse a un partido<br>4. Calificar usuario<br>5. Cancelar un partido (host)<br>6. Abandonar un partido|
