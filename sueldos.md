## Ejercicio 3

Realice un algorítmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

### Análisis

| Variable de entrada | Descripción |
|---------------------|-------------|
| cant_lapices | Cuántos lápices se compran|

| Variables de salida | Descripción |
|---------------------|-------------|
| precio | Valor que hay que pagar |

| Variables intermedias | Descripción |
|-----------------------|------------|
| valor_unitario | Usada dentro del código |

| Constantes | Descripción |
|------------|-------------|
| 1000 | Cantidad límite de lápices |
| $85, $90 | Valor individual según la cantidad |

## Pseudocódigo

```
Inicio
Leer cant_lapices
Si cant_lapices >= 1000
   valor_unidad = 85
Si no
   valor_unidad = 90
Fin Si
precio = valor_unidad * cant_lapices
Escribir "Valor total: ", precio
Fin
```

