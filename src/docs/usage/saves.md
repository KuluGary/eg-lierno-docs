---
title: Tiradas de salvación
description: Aprende a utilizar el comando `!save` de Lierno Bot.
---
## Módulo Save
### Tirada XdY
El comando `!save` se utiliza para hacer tiradas de salvación.

```
!roll <rollStr=1d20> [dc]
```
Lanza cualquier combinación de dados en formato XdY. (1d6, 2d8, etc)

#### Argumentos
* `rollStr` - Cualquier combinación de dados en formato XdY.
* `dc` (opcional) - Tirada de dados a superar.

### Tirada de iniciativa
```
!roll <saveStr="strength"> [dc]
```
Lanza una tirada de salvación obteniendo los datos del personaje activo.
#### Argumentos
* `saveStr` - La propiedad a usar. Una de:
    * `strength`
    * `dexterity`
    * `constitution`
    * `intelligence`
    * `wisdom`
    * `charisma`
* `dc` (optional) - Tirada de dados a superar.


### Listado de comandos
```
!save list
```
Devuelve un listado de los comandos disponibles en el módulo `!save`.