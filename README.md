# SSOO-tarea02
## Estudiante: Alexis Loyola
## Correo: alexis.loyola@alumnos.uv.cl

#### Diseño de la solucion:

#### Utilizamos el comando curl para traer los datos del URL, luego con el comando "-s" para que no haya informacion del proceso de descarga.

#### Despues colocamos el comando jq para procesar los datos en formato JSON en conjunto con la funcion "del()" para eliminar los datos que no son solicitados en el JSON original, que son las key "thumb" y "url_name".

#### Luego utilizamos el simbolo ">" para redireccionar los datos al archivo "items.json" (el archivo "items.json" se crea al momento de ejecutar el script).

#### Finalmente utilizamos el comando "echo" para mostrar el mensaje "JSON CREADO CON EXITO".
