# ASO2024TPs
TP3:
1a:Hay una diferencia de un segundo entre el sinhilos y conhilos. Estos códigos no se pueden codificar porque los tiempos de respuesta son diferentes, incluso si los cambios son pequeños.
1b:Los tiempos de ejecución no son iguales por segundos.
1c:Lo que sucedió después es que el error se debe a que ambos subprocesos están usando la variable global, y tanto el subproceso que habla como el que no habla están haciendo dos cosas al mismo tiempo y se produce el Race condition. Esto se debe a que cuanto más tiempo lleve realizar una tarea, más probabilidades habrá de que se descubra el error.
