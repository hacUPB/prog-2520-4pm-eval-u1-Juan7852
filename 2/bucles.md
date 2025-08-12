# Bucles 
## ejercicio 1
Un profesor tiene un salario inicial de $1500, y recibe un incremento de 10 % anual durante 6 años. ¿Cuál es su salario al cabo de 6 
años? ¿Qué salario ha recibido en cada uno de los 6 años? Realice el algoritmo y represente la solución mediante el diagrama de flujo, el pseudocódigo 

## pseudocodigo

```
inicio 
año = 1 
sal = 1500
total = 0 
mientras año <= 6 
     anual =sal * 1.1
     total = total + anual 
     sal = anual 
     mostrar anual 
fin mientras 
mostrar total 
fin 

 ```
img 12/08 diagrma 

## ejercicio 2 

se requiere un algoritmo para determinar, de N cantidades, cuántas son cero, cuántas son menores a cero, y cuántas son mayores a cero. Realice el diagrama de flujo, el pseudocódigo 

input 
N, cant 
output 
cero, mayor, menor (contador)
control
i 

inicio 
n = "cantidad agregada" 
cero = 0 
menores = 0 
mayores = 0
