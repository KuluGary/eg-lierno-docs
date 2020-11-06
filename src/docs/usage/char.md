---
title: Manejo de personajes
description: Aprende a utilizar el comando `!char` de Lierno Bot.
---
## Módulo Char
El comando `!char` se utiliza para manipular el sistema de personajes. Permite seleccionar, mostrar y listar los personajes creados a través de [Lierno App](https://lierno.netlify.app/).
### Mostrar personajes

```
!char show [flavor | bonus actions | reactions | abilities | actions]
```
Muestra un pequeño resumen de los datos del personaje seleccionado.

#### Argumentos
* `flavor` - Muestra los datos no-mecánicos del personaje como las descripciones físicas y psicológicas.
* `bonus actions` - Muestra las acciones adicionales disponibles para el personaje.
* `reactions` - Muestra las reacciones disponibles para el personaje.
* `abilities` - Muestra las habilidades disponibles para el personaje.
* `actions` - Muestra las acciones disponibles para el personaje

### Seleccionar personaje
```
!char select
```
Selecciona uno de los personajes disponibles creados a través de [Lierno App](https://lierno.netlify.app/). Por defecto, Lierno Bot auto-selecciona el personaje asociado a la campaña en la que se está escribiendo.

### Listado de personajes
```
!char list
```
Devuelve un listado de todos los personajes disponibles creados a través de [Lierno App](https://lierno.netlify.app/).