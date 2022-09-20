# Principipios del diseño digital # 
    - Funciones lógicas(true,false (0,1))
        - Funciones lógicas elementales(AND, OR, NOT)
            -Puertas lógicas que implementan las funciónes logicas
## Recursos ##
    - Ejercicios sin solución
    - Soluciones dadas
    - Entrenador de Karnaugh
    - Exámenes de años anteriores

## Introducción ##
    - En un circuito digital puede ser:
        - Combinacional
            - Las salidas sólo dependen del valor de las entradas del momento actual
            - S(t) = f(E(t))
        - Secuencial
            - Tienen memoria, porque son capaces de recordar entradas anteriores
            - S(t) != f (E(t))
## Función lógica ##
    - Expresión formal del comportamiento de un citcuito lógico 
    - Permite determinar la salida del circuito en función de las entradas
    - Aridad: número  de variables lógicas de entrada 
    - Valoración: una de las combinaciones de valores de entrada
    - Tablas de verdad
        - Es una tabla que representa la forma en la que las diferentes entradas
         y sus combinaciones afectan a la salida
            - Para cada combinación es una fila
            - Para las diferentes entradas y salida son las columnas
### Ejemplo ###
    - Con las dos entradas de la puerta derecha y la puerta izquierda se diseña un circuito que encienda la luz (l) cuando alguna de las puertas esté abierta
![]("assets\img\Ejemplo.verdad_coche.png")