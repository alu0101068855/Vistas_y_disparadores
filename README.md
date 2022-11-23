### Notas 23/11

Diferencias entre Explain y Explain analyze
"Uno solo lo explica y el otro explica y  ejecuta el comando"

Explain
Costo de inicio estimado (tiempo inicial que toma devolverse la primera tupla)
Costo total estimado (tiempo total para devolver todas las tuplas)
Numero de filas escaneadas (se cumple solamente si la ejecucion de la consulta es completa)
Cantidad estimada de filas de salida

Explain analyze
Permite visualizar el costo estimado de ejecucion en la sentencia
.
.
.

Sintaxis
pg_restore -x --no-owner -U postgress ....
