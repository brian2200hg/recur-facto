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

![image](https://github.com/user-attachments/assets/bfe5d31b-bbc6-42f7-b946-a2f832c4e6c6)

La función factorial es una fórmula matemática representada por el signo de exclamación “!”. En la fórmula Factorial se deben multiplicar todos los números enteros y positivos que hay entre el número que aparece en la fórmula y el número 1.

ejemplo -
6! = 1x2x3x4x5x6 = 720

en este ejemlo el factorial es 6

´´´ fun main() {

// Número fijo para calcular el factorial

val numero - 6

// Calculamos el factorial usando la función recursiva val resultado factorial(mmero)

// leprimisos el resultadu println("El factorial de Snumero es $resultado") } // Función recursiva para calcular el factorial

fun factorial(n: Int): Int (

return if (n - 1) 1 elsen factorial(n-1) }

estructura de la funcion funcional:
fun factorial(: Int): Ist ( return if (n - 1) 1 eisen factorial(1) }

Definición:
Entrada: Una función funcional recibe una o más funciones como argumentos o devuelve una función como resultado.
Operación: La función opera utilizando las funciones que recibe como argumentos o las crea y las retorna.
Salida: El resultado es generalmente una nueva función o un valor computado basado en la combinación de funciones.



fun factorial(n: Int): Long {
return if (n == 0 || n == 1) {
    1
} else {
    n * factorial(n - 1)
}
}

fun main() { for (i in 1..5) { val resultado = factorial(i) println("El factorial de $i es: $resultado") } }



fun contarDescendente(n: Int) {
    if (n < 1) return  // Caso base: cuando n es menor a 1, termina la función
    println(n)  // Imprime el número actual
    contarDescendente(n - 1)  // Llama a la función con n - 1
}

// Llamada a la función comenzando desde 5
contarDescendente(5)


