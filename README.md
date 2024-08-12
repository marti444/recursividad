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
