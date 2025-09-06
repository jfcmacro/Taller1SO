# Sistemas Operativos - Taller 1

Programar consiste en crear una implementación de una solución, lo
sufientemente genérica, que a través de parámetros, se puede cambiar
el comportamiento de dicha solución, sin tener que cambiar el código.

Normalmente, esto lo observamos la declaración de funciones, que
reciben parámetros que le permtien modificar consistente la solución,
por ejemplo tememos una funció de ordenamiento (`sort`), que además
recibe los datos a ordenar, puede tener recibir un parámetro que
representa la función de comparación, esto hace que el ordenamiento se
pueda hace utilizando diferentes criterios, sin tener que modificar
el programa.

En la programación actual, se requiere construir programas que
implementen la solución más general y que a través de los parámetros
se pueda cambiar su comportamiento. En el caso de los programas y los
guiones, esto se puede lograr a través de los argumentos de la línea
de comandos o las variables de ambiente.

Vamos a ver como hacerlo a través de Linux y Windows.

## Línea de Argumentos. En los programas de terminal más común de cambiar
el comportamiento de un programa es a través de la línea de comandos.


* [Linea de Argumentos](./src/LineaDeArgumentos.c): Se encarga de
  mostrar como un programa recibe argumentos del mundo exterior, a
  través del Shell y de la línea de comandos.