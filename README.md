# RETO-4_UNAL.
Se evidenciaran los proyectos del reto #4 el cual consiste en hacer el pseudocodigo y el diagrama de flujo del algoritmo para saber si n es un numero primo y el algoritmo para sacar una raíz cuadrada.

- Pseudocodigo numeros primos

         si n % x = 0 entonces
         [variables]
         n: entero
         x: entero
         i: entero
         inicio
            x = 1
               mientras que x <= n hacer
                  si n % x = 0 entonces
                    i = i + 1
                  fin si
                 x = x + 1
               fin mientras
         si i = 2 entonces
            escribir ("n" es un numero primo)
         si no
            escribir ("n" no es un numero primo)
         fin si
         fin


- Diagrama de flujo numeros primos

![diagrama de flujo numeros primos drawio](https://user-images.githubusercontent.com/124611099/223006047-cf5bc393-0a46-4ca9-9e2e-f7e69968a7f9.png)

- Pseudocodigo para hallar la raiz cuadrada.

Para hallar la raiz cuadrada de un numero primero tenemos que evidenciar si el radicando tiene más de dos cifras sxi es asi separamos las cifras en grupos de dos, empezando por la derecha. Luego calculamos la raíz cuadrada entera o exacta, del primer grupo de cifras por la izquierda. El cuadrado de la raíz obtenida se resta al primer grupo de cifras que aparecen en el radicando. despues bajamos el siguiente grupo de cifras del radicando, separando del número formado. La primera cifra a la derecha y dividiendo lo que resta entre el doble de la raíz.En otra fila debajo de la raíz colocamos el doble de la misma. A continuación, se coloca el cociente que se obtenga. Y luego el número obtenido se multiplica por dicho cociente. Después, se resta a la cantidad operable del radicando. El cociente obtenido es la segunda cifra de la raíz, quedando. Y para finalizar bajamos el siguiente par de cifras y repetimos los pasos anteriores.

       [variables]
       n: int
       x: int
       z: float
       i: int 
       inicio
          i = 1
             ingresar un numero"n"
               buscar un numero "x" que cumpla (x^2)≤n
                 mientras i <= 2  hacer
                   si z = (n / x) con 3 numeros despues de la ","
                      x =( x + z ) / 2
                      i = i + 1
                   si no
                     escribir (la raiz cuadrada de "n" es "x")
                   fin si
                 fin mientras
        fin


- Diagrama de flujo para hallar la raiz cuadrada.

![diagrama_raiz_cuadrada drawio](https://user-images.githubusercontent.com/124611099/223007373-49ceb3b9-4e5d-4d15-9bc7-5d46f7ff22f4.png)








