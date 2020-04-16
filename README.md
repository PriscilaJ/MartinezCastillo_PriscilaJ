# MartinezCastillo_PriscilaJ
Repositorio- Actividades del Club de Programación 2020


PROBLEMA #1:
Descripción: 
     Escribe un programa que calcule de la forma A+B, números dados en la entrada. Donde La única línea de 
     entrada contiene dos enteros separados por espacio: A,B(0<=A,B<=10).
        
Metodología de la solución: 
     Lo más importante en el problema es distinguir y obtener ambos números que han sido introducidos en una sola línea de entrada. 
     Para ello hacemos uso de la siguiente línea de código: num=list(map(int,numeros.split()))
     Donde:
     list():Creo una lista en python.
     map():Toma dos argumentos. El primer argumento es el método a aplicar y el segundo es el dato en donde se aplicará, es decir
           hacemos un casting a cada elemento de numeros.split()
     split():Divide los elementos de una variable al encontrar un espacio y los guarda en una lista.
