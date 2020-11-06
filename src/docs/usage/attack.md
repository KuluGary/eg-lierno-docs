---
title: Ataques
description: Aprende a utilizar el comando `!attack` de Lierno Bot.
---
## Módulo Attack
### Tirada Genérica
El comando `!roll` se utiliza para hacer tiradas de dados genéricas. Comunmente cuando no se puede utilizar el módulo `!attack`, `!save` o `!heal`.

```
!roll <rollStr=1d20>
```
Lanza cualquier combinación de dados en formato XdY. (1d6, 2d8, etc)

#### Argumentos
* `rollStr` - Cualquier combinación de dados en formato XdY.

### Tirada de ataque
```
!roll <atkStr>
```
+ `atkStr` - Nombre del ataque a usar de entre el listado de los ataques disponibles del personaje. Utiliza el módulo `!char` para seleccionar el listado disponible de ataques de un personaje.

### Listado de comandos
```
!roll list
```
Devuelve un listado de los comandos disponibles en el módulo `!attack`.