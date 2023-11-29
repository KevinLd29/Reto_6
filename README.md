# Reto6

Primero que todo, buenos días, segundo, Millonarios JAJA.
Ya puesto en modo serio, por comodidad y más que todo porque eran programas sencillos con soluciones sencillas (Y para no seguir llegando mi PC con puros programas individuales) los hice en un cuadernillo, que siento que es lo mejorcito que se puede poner en estos casos.

Cada comentario explica que solucion se está dando ante que problematica, espero se logre entender.
(Como es de costumbr, pueden copiar y pegar el código mucho más fácil con esta función de Markdown que me salvó la vida)

# 1
````python
import math
# Tronco de cono
def volumenTroncoConico(r1, r2, h):
    return (math.pi * h * (r1**2 + r2**2 + r1*r2)) / 3

def areaTroncoConico(r1, r2, h):
    return math.pi * (r1 + r2) * math.sqrt((r2 - r1)**2 + h**2) + math.pi*r1**2 + math.pi*r2^2

````
# 2
```python
import math
# Círculo
def areaCirculo(r):
    return math.pi * r**2

def perimetroCirculo(r):
    return 2 * math.pi * r

````
# 3
```python
import math
# Función de carne de aves
def cantidadCarne(N, M, K):
    return N*6 + M*7 + K
````
# 4
```python
import math
# Vueltas de la compra
def vueltas(P, M, H, B):
    total = P*300 + M*3300 + H*350
    return B - total
````
# 5
```python
import math

# Valor de un préstamo
def prestamo(C, i, n):
    return C * ((1 + i)**n)
````
# 6
```python
import math
# Número total de contagiados
def contagiados(C, D):
    return C * (2**D)

````
# 7
```python
def promedio(nums):
    return sum(nums) / len(nums)

def mediana(nums):
    nums.sort()
    if len(nums) % 2 == 0:
        return (nums[len(nums)//2 - 1] + nums[len(nums)//2]) / 2
    else:
        return nums[len(nums)//2]

def promedioMultiplicativo(nums):
    prod = 1
    for n in nums:
        prod *= n
    return prod**(1/len(nums))

def ordenarAsc(nums):
    return sorted(nums)

def ordenarDesc(nums):
    return sorted(nums, reverse=True)

def potencia(nums):
    return max(nums)**min(nums)

def raizCubica(nums):
    return min(nums)**(1/3)

````
Afortunadamente, ya había trabajado este caso entonces fue tomar practicamente el mismo código y adecuarlo a este, esto sí es ingeniería Jaja.

# 8
```python
from funciones import *

# Aquí va el código que pide los números al usuario, y usa las funciones importadas.

````

# Punto 9
El `pip` es el administrador de paquetes de Python. Permite instalar, actualizar y eliminar paquetes y bibliotecas de Python de una manera sencilla y rapida por medio de un comando. Se puede usar pip install nombre_paquete para instalar un paquete.
Ejemplo:
```python
pip install matplotlib
````

# Punto 10

En python existen gran cantidad de bibliotecas, diccionarios, modulos, etc, aqí una pequeña lista de los módulos más populares y usados en python (son gratis, no pierdes nada con probarlos):

requests: que se usa para hacer solicitudes HTTP.

numpy: este es usado para computación numérica.

pandas: normalmente se usa para manipulación y análisis de datos y trabajar en entornos virtuales.

matplotlib: para visualización de datos, tratamiento de datos matematicos.

flask: es mayormente usado para desarrollo web.

tensorflow: para aprendizaje automático en bases de datos y códigos.


Para instalarlos, copia y pega el ejemplo 9 y le cambias por el nombre del paquete que se vaya a usar.


Gracias por su atención, muchas gracias!
¡Hasta una próxima! (si es que hay)
