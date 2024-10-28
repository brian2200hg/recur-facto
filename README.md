# recur-facto

fun numerosDesc(n= int) { if (n<=0) { return } print(n) numerosDesc(n-1) } fun main() { val num=5 mumerosDesc(num) }

Caso Base:
El caso base en recursividad es el caso más simple de un problema que se puede resolver directamente, sin necesidad de llamar a la función recursiva nuevamente. Es el punto de parada de la recursividad, donde la función deja de llamarse a sí misma.

es importante porque:

Evita la recursividad infinita: sin un caso base, la función recursiva seguiría llamándose a sí misma indefinidamente, lo que provocaría un error de stack overflow.

Proporciona una solución trivial: el caso base proporciona una solución directa para el problema más simple, lo que permite que la función recursiva se construya sobre esta solución.

Permite la descomposición del problema: el caso base ayuda a descomponer el problema en subproblemas más pequeños, que se pueden resolver de manera recursiva.

Llamada recursiva
La llamada recursiva es un mecanismo mediante el cual una función se invoca a sí misma, directa o indirectamente, para resolver un problema. En esencia, una función recursiva se ejecuta de nuevo durante su proceso de ejecución.

Características de la llamada recursiva:

◈ Autoinvocación: La función se llama a sí misma, permitiendo que se ejecute nuevamente en el contexto de su propia ejecución.

◈ Parámetros variables: Cada invocación recursiva puede utilizar parámetros diferentes, lo que facilita el avance hacia la solución.

◈ Condiciones de finalización: Es crucial que la función tenga condiciones de parada bien definidas para prevenir ciclos de recursión infinita.

Proceso de la llamada recursiva:

◈ La función se invoca inicialmente con ciertos parámetros.

◈ Se ejecuta la función con los parámetros actuales, generando un resultado parcial.

◈ La función se llama de nuevo a sí misma con parámetros actualizados.

◈ Este ciclo se repite hasta que se cumple la condición de parada.

La llamada recursiva es especialmente útil para problemas que presentan estas características:

◈ Pueden descomponerse en subproblemas más simples.

◈ Los subproblemas guardan similitud con el problema original.

◈ La solución se puede construir a partir de las soluciones de los subproblemas.

# ¿que es la funcion factorial?
