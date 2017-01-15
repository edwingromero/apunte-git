### git log
Muestra todo el historial de commits del proyecto. y una nueva modificacion

`git log --pretty=format:"%h - %an, %ar : %s"`

Muestra el historial con el formato que indicamos.

#### Limitar lal salida del historial

`git log -n`: cambiamos la n por cualquier numero entero, por ejemplo `git log -2` nos mostrara los 2 commits mas recientes.

`git log --after="2016-01-14 00:00:00"` : muestra los commits realizados despues de la fecha especificada.

`git log --before="2016-01-14 00:00:00"` : muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas segun convenga, por ejemplo `git log --after="2017-01-14 13:00:00" --before="2017-01-14 14:00:00"`