# Recursividad
La recursividad es una tecnica que permite a las funciones autoinvocarse para resolver problemas complejos.
~~~~
fun nDesecendentes(n:Int)
{
   if(n<=0)
   {
     return
   }
   print(n)
   nDesecendentes(n-1)
}
fun main()
}
  valnumero=5
  nDescendentes(numero)
}
~~~~
### Caso Base
Es una condicion,su funciones es terminar y de esta forma evitar que se forme el siclo infinito.
### Como funciona:
La funcion se va a llamar asi misma y se va restando hasta llegar a 1.
Luego se corta el ciclo.
### Explicación del Código
- Función nDesendentes
  ~~~
  fun nDesendentes(n: Int) {
  ~~~
  fun nDesendentes(n: Int): Define una función llamada nDesendentes que toma un argumento entero n. La función no devuelve ningún valor.
  ~~~
      if (n <= 0) {
        return
    }
 ~~~

- if (n <= 0): Evalúa si n es menor o igual a 0. Este es el caso base para la recursión.

   - return: Si n es menor o igual a 0, la función simplemente retorna sin hacer nada más. Esto detiene la recursión cuando n llega a 0 o a un número negativo.

~~~
  print(n)
~~~
