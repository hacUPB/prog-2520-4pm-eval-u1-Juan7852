# taller 
## ejercicio 1 
1. **Verificación de peso de despegue**
    
    En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

inicio
    leer pesoini
    leer pesocombu
    leer pesocarga
    leer limitemax

    pesototal = pesoini + pesocombu + pesocarga

    si pesototal > limitemax 
        exceso = peso_total - limitemax
        mostrar no puede despegar, debe reducir carga o combustible
        mostrar exceso de peso 
    sino
        mostrar aeronave lista para despegar
        mostrar peso total
    fin si
fin


## ejercico 2 
2. **Registro de altitudes de vuelo**
    
    Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.

variables de entrada 
altutud 
variables de salida 
altitud
variables de control 
i 

inicio
i = 0
    mientras i < 6
        leer dato
        altitud[i] = dato
        i = i + 1
    fin mientras
    desde i = 0 hasta i = 5
        mostrar altitud[i]
    fin desde 
fin


   