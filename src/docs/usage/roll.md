---
title: Tiradas de dados
description: Aprende a utilizar el comando `!roll` de Lierno Bot.
---
## Módulo Roll
### Tirada XdY
El comando `!roll` se utiliza para hacer tiradas de dados genéricas. Comunmente cuando no se puede utilizar el módulo `!attack`, `!save` o `!heal`.

```
!roll <rollStr=1d20> [dc]
```
Lanza cualquier combinación de dados en formato XdY. (1d6, 2d8, etc)

#### Argumentos
* `rollStr` - Cualquier combinación de dados en formato XdY.
* `dc` (opcional) - Tirada de dados a superar.

### Tirada de iniciativa
```
!roll initiative
```
Lanza una tirada de iniciativa. Utiliza el módulo `!char` para recoger los bonificadores del personaje asociado en ese momento.

### Listado de comandos
```
!roll list
```
Devuelve un listado de los comandos disponibles en el módulo `!roll`.