# TAREA-LINKEDLIST
# Sebastián Guevara
En primera instancía se intercambio los ArrayList con LinkedList.

Adicionalmente a esto, se implemento el método de updateStudent(), el cual tiene como funcionalidad encontrar un estudiante con el mismo ID y cambiarlo por el estudiante seleccionado, ademas este método tambien comprueba que si el estudiante existe, si no existe retorna null.

Esto se hizo con el LinkedList de students, cual por medio de un loop pusimos a iterar entre todos los objetos que estaban dentro de este LinkedList. Dentro de este loop se encontraba una condicional, la evalua si el id de el estudiante dado es igual al id del estudiante buscado, de ser cierto actualiza el nombre del estudiante por el nombre del estudiante dado y por lo tanto existe. De no ser asi el estudiante no existe y por lo tanto retornaría nulo.

Finalmente, el ejercicio se puede ejecutar corriendo las pruebas que se hicieron con anterioridad.
