# Guía Rápida de Comandos Vim

## Movimiento
- `h`, `j`, `k`, `l`: Izquierda, abajo, arriba, derecha
- `^`: Ir al inicio de la línea
- `$`: Ir al final de la línea
- `gg`: Ir a la primera línea
- `G`: Ir a la última línea
- `:n`: Ir a la línea n

## Reemplazar Texto
- `r`: Reemplazar carácter
- `cw`: Cambiar palabra
- `cc`: Cambiar línea
- `c{motion}`: Cambiar desde el cursor hasta {motion}

## Copiar/Pegar
- `y{motion}`: Copiar {motion}
- `yy`: Copiar línea
- `p`: Pegar después del cursor
- `P`: Pegar antes del cursor

## Buscar
- `/{pattern}`: Búsqueda hacia adelante de {pattern}
- `?{pattern}`: Búsqueda hacia atrás de {pattern}
- `n`: Repetir la última búsqueda
- `N`: Repetir la última búsqueda en la dirección opuesta

## Repetir Comandos
- `{num}{command}`: Repetir comando {num} veces
- `.`: Repetir el último cambio

## Insertar Texto
- `i`: Insertar en el cursor
- `I`: Insertar al inicio de la línea
- `a`: Añadir después del cursor
- `A`: Añadir al final de la línea
- `o`: Abrir una nueva línea debajo de la línea actual
- `O`: Abrir una nueva línea encima de la línea actual

## Borrar Texto
- `x`: Borrar carácter
- `dd`: Borrar línea
- `dw`: Borrar palabra
- `d{motion}`: Borrar {motion}

## Deshacer/Rehacer
- `u`: Deshacer
- `Ctrl-r`: Rehacer

## Guardar y Salir
- `:w`: Guardar
- `:wq`: Guardar y salir
- `:q`: Salir
- `:q!`: Forzar salida sin guardar cambios
- `:wq!`: Forzar guardado y salir

## Ayuda
- `:help [topic/command]`: Obtener ayuda sobre un tema o comando
- `vimtutor`: Tutorial

## Buscar y Reemplazar
- `:s/{old}/{new}/{options}`: Sustituir {new} por {old} en la línea actual
- `:%s/{old}/{new}/{options}`: Sustituir {new} por {old} en todo el documento

> La opción `g` sustituye todas las ocurrencias en una línea; de lo contrario, solo se cambia la primera ocurrencia por línea.

Para más información, visita [Linux Training Academy](http://www.LinuxTrainingAcademy.com).
