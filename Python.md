# 📚 Compilación de Notebooks

# 📑 Tabla de Contenidos (Versión Alternativa)

- 🎨 [Directorios](#directorios)
- 🎨 [Classwork1](#classwork1)
- 🎨 [diccionarios](#diccionarios)
- 🎨 [Listas](#listas)
- 🎨 [Numpy](#numpy)
- 🎨 [Pilas](#pilas)
- 🎨 [Ejercicios Parcial 1](#ejercicios-parcial-1)
- 🎨 [Ejercicios Pre-Parcial](#ejercicios-pre-parcial)
- 🎨 [Ejercicios Pre-Parcial 2](#ejercicios-pre-parcial-2)
- 🎨 [Colas](#colas)
- 🎨 [Diccionarios (extra)](#diccionarios-(extra))
- 🎨 [Directorios](#directorios)
- 🎨 [Classwork1](#classwork1)
- 🎨 [diccionarios](#diccionarios)
- 🎨 [Listas](#listas)
- 🎨 [Numpy](#numpy)
- 🎨 [Pilas](#pilas)
- 🎨 [Ejercicios Parcial 1](#ejercicios-parcial-1)
- 🎨 [Ejercicios Pre-Parcial](#ejercicios-pre-parcial)
- 🎨 [Ejercicios Pre-Parcial 2](#ejercicios-pre-parcial-2)
- 🎨 [Colas](#colas)
- 🎨 [Diccionarios (extra)](#diccionarios-(extra))


> Este documento integra varios notebooks en un único archivo en formato Markdown, con explicaciones, código y salidas comentadas para mayor claridad.


---
# 📘 Directorios
---

> Este apartado corresponde al notebook **Directorios**, donde se desarrollan ejercicios y ejemplos prácticos.

### 💻 Ejemplo 1 (versión alternativa)

```python
import os
os.mkdir("carperta1")   # creacion de carpetas

print(os.listdir("."))
```

---


---
# 📘 Classwork1
---

> Este apartado corresponde al notebook **Classwork1**, donde se desarrollan ejercicios y ejemplos practicos.

### 💻 Ejemplo 1 (versión alternativa)

```python
a=["nike", "puma", "adidas", "new balance"]
#print(a[0])
#print(a[1])
#print(a[3])
print(a[-2])
```
📤 **Resultado mostrado:**

```
adidas

```
### 💻 Ejemplo 2 (versión alternativa)

```python
edades= [20, 41, 6, 18, 23]

for edad in edades:
  print(edad)

print("___________________")

for i in range(len(edades)):
  print(edades[i])
```
📤 **Resultado mostrado:**

```
20
41
6
18
23
___________________
20
41
6
18
23

```
### 💻 Ejemplo 3 (versión alternativa)

```python
mylist = ["adidas", "futbol", "skate"]
print (mylist)

for item in mylist:
  print(item)
```
📤 **Resultado mostrado:**

```
['adidas', 'futbol', 'skate']
adidas
futbol
skate

```
### 💻 Ejemplo 4 (versión alternativa)

```python
lista=[1,"alan", 2]

listin=list([24, 2, "adidas"])

print(lista)

print(listin)

for item in lista:
  print(item)

for item in listin:
  print(item)
```
### 💻 Ejemplo 5 (versión alternativa)

```python
edades =[20, 41, 6, 18, 23]
edades.append(10)
indice = 0

edades= edades + [16,21,11]
while indice < len(edades):
  print(edades[indice])
  indice += 1
```
📤 **Resultado mostrado:**

```
20
41
6
18
23
10
16
21
11

```

---


---
# 📘 diccionarios
---

> Este apartado corresponde al notebook **diccionarios**, donde se desarrollan ejercicios y ejemplos prácticos.

### 💻 Ejemplo 1 (versión alternativa)

```python
d1 ={
    "nombre": "sara",
    "edad": 27,
    "documento": 10010010
}

print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'sara', 'edad': 27, 'documento': 10010010}

```
### 💻 Ejemplo 2 (versión alternativa)

```python
d1 ={
    "nombre": "alan",
    "edad": 28,
    "documento": 10010010
}

print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'alan', 'edad': 28, 'documento': 10010010}

```
### 💻 Ejemplo 3 (versión alternativa)

```python
d2 = dict({
    ("nombre" ,"alan"),
    ("edad", 28),
    ("documento", 10010010),
})

print(d2)
```
📤 **Resultado mostrado:**

```
{'nombre': 'alan', 'documento': 10010010, 'edad': 28}

```
### 💻 Ejemplo 4 (versión alternativa)

```python
d3=dict(nombre="alan", edad=28, documento=10010010)
print(d3)
```
📤 **Resultado mostrado:**

```
{'nombre': 'alan', 'edad': 28, 'documento': 10010010}

```
### 💻 Ejemplo 5 (versión alternativa)

```python
print(d1['nombre']) #accerder a un elemento del diccionario
print(d1['edad'])
print(d1.get('nombre'))
print(d1.get('edad'))
```
📤 **Resultado mostrado:**

```
alan
28
alan
28

```
### 💻 Ejemplo 6 (versión alternativa)

```python
d1 ['nombre'] = "laura" #editar
print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'laura', 'edad': 28, 'documento': 10010010}

```
### 💻 Ejemplo 7 (versión alternativa)

```python
d1 ['dirección'] = "av sprindfiel cll 123 siempre viva" # agregar elemento
print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'laura', 'edad': 28, 'documento': 10010010, 'dirección': 'av sprindfiel cll 123 siempre viva'}

```
### 💻 Ejemplo 8 (versión alternativa)

```python
for x in d1: #es para iterar
  print(x)# imprime los key del diccionario
```
📤 **Resultado mostrado:**

```
nombre
edad
documento
dirección

```
### 💻 Ejemplo 9 (versión alternativa)

```python
for x in d1: #es para iterar
  print(d1[x])# imprime los valores
```
📤 **Resultado mostrado:**

```
laura
28
10010010
av sprindfiel cll 123 siempre viva

```
### 💻 Ejemplo 10 (versión alternativa)

```python
for x , y in d1.items():# imrimir key y value
  print(x,y)
```
📤 **Resultado mostrado:**

```
nombre laura
edad 28
documento 10010010
dirección av sprindfiel cll 123 siempre viva

```
### 💻 Ejemplo 11 (versión alternativa)

```python
anidado1={'a':1, 'b':2}
anidado2={'a':1, 'b':2}
d={ # el diccionario d contiene el anidado 1 y 2
    "anidado1": anidado1,
    "anidado2": anidado2
}
print(d)
```
📤 **Resultado mostrado:**

```
{'anidado1': {'a': 1, 'b': 2}, 'anidado2': {'a': 1, 'b': 2}}

```
### 💻 Ejemplo 12 (versión alternativa)

```python
# aplicamos el método clear , eliminna todo del diccionario
d={'a':1, 'b':2}
d.clear()
print(d)
```
📤 **Resultado mostrado:**

```
{}

```
### 💻 Ejemplo 13 (versión alternativa)

```python
#get nos permite consultar el valor  de uin key determinado
d={'a':1, 'b':2}
print(d.get('a'))
print(d.get('z', 'no encontrado'))
```
📤 **Resultado mostrado:**

```
1
no encontrado

```
### 💻 Ejemplo 14 (versión alternativa)

```python
# items

  d={'a':1, 'b':2}
  it =d.items()
  print(it)
  print(list(it))
  print(list(it)[0][0])
```
📤 **Resultado mostrado:**

```
dict_items([('a', 1), ('b', 2)])
[('a', 1), ('b', 2)]
a

```
### 💻 Ejemplo 15 (versión alternativa)

```python
#keys
 d={'a':1, 'b':2}
 k=d.keys()
 print(k)
 print(list(k))
```
📤 **Resultado mostrado:**

```
dict_keys(['a', 'b'])
['a', 'b']

```
### 💻 Ejemplo 16 (versión alternativa)

```python
#values
d={'a':1, 'b':2}
print(list(d.values()))
```
📤 **Resultado mostrado:**

```
[1, 2]

```
### 💻 Ejemplo 17 (versión alternativa)

```python
# quitamos un valor con pop, busca y elimina la key
d={'a':1, 'b':2}
d.pop('a')
print(d)
```
📤 **Resultado mostrado:**

```
{'b': 2}

```
### 💻 Ejemplo 18 (versión alternativa)

```python
d={'a':1, 'b':2}
d.pop('c' , -1)
print(d)
```
📤 **Resultado mostrado:**

```
{'a': 1, 'b': 2}

```
### 💻 Ejemplo 19 (versión alternativa)

```python
#pop item elimina de manera aleatoria cualquier elemento
d={'a':1, 'b':2}
d.popitem()
print(d)
```
📤 **Resultado mostrado:**

```
{'a': 1}

```
### 💻 Ejemplo 20 (versión alternativa)

```python
#update actualiza y si no esta lo añade
d1={'a':1, 'b':2}
d2={'a':0, 'd':400}
d1.update(d2)
print(d1)
```
📤 **Resultado mostrado:**

```
{'a': 0, 'b': 2, 'd': 400}

```


---
# 📘 Listas
---

> Este apartado corresponde al notebook **Listas**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
num =[]
num = num + [10, 5, 3]


print(num)
```
📤 **Resultado mostrado:**

```
[10, 5, 3]
```

### 💻 Ejemplo 2 (versión alternativa)

```python
palabras = ["adidas","colombia","argentina", "brasil", "alemania"]

palabras.pop(-2,) #se esta eliminado un elemento de la lista
palabras.pop(2,)

print(palabras)
```
📤 **Resultado mostrado:**

```
['adidas', 'colombia', 'alemania']
```

### 💻 Ejemplo 3 (versión alternativa)

```python
palabras = ["hola", "hello", "ciao", "salute", "hello"]

palabras.remove("hello") #se esta eliminado un elemento de la lista
palabras.remove("hola")

print(palabras)#con esto imprime las palabras o elementos que no fueron eliminados
```
📤 **Resultado mostrado:**

```
['ciao', 'salute', 'hello']
```

### 💻 Ejemplo 4 (versión alternativa)

```python
personas = [
    {"nombre": "Juan", "documento": "12345678"},
    {"nombre": "Ana", "documento": "23456789"},
    {"nombre": "Luis", "documento": "34567890"}
]


for persona in personas:
    print(f"Nombre: {persona['nombre']}, Documento: {persona['documento']}")
```
📤 **Resultado mostrado:**

```
Nombre: Juan, Documento: 12345678
Nombre: Ana, Documento: 23456789
Nombre: Luis, Documento: 34567890
```

### 💻 Ejemplo 5 (versión alternativa)

```python
nombres = []
identificaciones = []
direcciones = []

# Definir el tamaño de las listas
tamaño = 3

# Leemos datos y agregamos a las listas
for i in range(tamaño):
    print(f"Ingrese los datos de la persona {i + 1}")
    nombre = input("Nombre: ")
    identificacion = input("Identificación: ")
    direccion = input("Dirección: ")

    # Agregar a las listas correspondientes
    nombres.append(nombre)  # Aquí se usa la lista "nombres" correctamente
    identificaciones.append(identificacion)  # Usamos "identificaciones"
    direcciones.append(direccion)  # Usamos "direcciones"

# Ahora mostramos las listas
for i in range(tamaño):
    print(f"Mostrando los datos de la persona {i + 1}")
    print("Nombre:", nombres[i])
    print("Identificación:", identificaciones[i])
    print("Dirección:", direcciones[i])
```
📤 **Resultado mostrado:**

```
Ingrese los datos de la persona 1
Nombre: asdasd
Identificación: 12312
Dirección: asdasdas
Ingrese los datos de la persona 2
Nombre: asdasd
Identificación: 123321
Dirección: asdasd2
Ingrese los datos de la persona 3
Nombre: asdas
Identificación: 1445
Dirección: asdasd25
Mostrando los datos de la persona 1
Nombre: asdasd
Identificación: 12312
Dirección: asdasdas
Mostrando los datos de la persona 2
Nombre: asdasd
Identificación: 123321
Dirección: asdasd2
Mostrando los datos de la persona 3
Nombre: asdas
Identificación: 1445
Dirección: asdasd25
```

### 💻 Ejemplo 6 (versión alternativa)

```python
import numpy as np

# esta es una lista con los números correctamente separados por comas
lst = [10, 20, 30, 40, 50]

# Convertir la lista a un arreglo de NumPy
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[10 20 30 40 50]
```

### 💻 Ejemplo 7 (versión alternativa)

```python
import numpy as np

# esta es una lista con los números correctamente separados por comas
lst = ["DARIAN", "PAKA", "LORENA", "BRAYAN"]

# Convertir la lista a un arreglo de NumPy
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
['DARIAN' 'PAKA' 'LORENA' 'BRAYAN']
```

### 💻 Ejemplo 8 (versión alternativa)

```python
import numpy as np

# esta es una lista con los números correctamente separados por comas
lst = ["PERA", "BANANO","MANZANA"]

# Convertir la lista a un arreglo de NumPy
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
['PERA' 'BANANO' 'MANZANA']
```

### 💻 Ejemplo 9 (versión alternativa)

```python
import numpy as np
lst = [[10], [20], [30], [40], [50]]
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[[10]
 [20]
 [30]
 [40]
 [50]]
```

### 💻 Ejemplo 10 (versión alternativa)

```python
import numpy as np
lst = [["ITZZA"], ["NICOLAS"], ["VELANDIA"], ["DANIEL"], ["ARTEAGA"]]
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[['ITZZA']
 ['NICOLAS']
 ['VELANDIA']
 ['DANIEL']
 ['ARTEAGA']]
```

### 💻 Ejemplo 11 (versión alternativa)

```python
import numpy as np
lst = [["PIZZA"], ["SALCHIPAPA"], ["CHORIPERRO"], ["COMBINADO"], ["AGUA DE PANELA"]]
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[['PIZZA']
 ['SALCHIPAPA']
 ['CHORIPERRO']
 ['COMBINADO']
 ['AGUA DE PANELA']]
```

### 💻 Ejemplo 12 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la suma
vctr_add = vctr1+vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [11 22 33 44 55]
```

### 💻 Ejemplo 13 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50]
lista2=[ 1,2,3,4,5,6 ,7]
# en este caso nos dara sintax error por que el tamaño de las listas es diferente

vctr1 =np.array(lista1)
vctr2 =np.array(lista2)

print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)


vctr_add = vctr1+vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5 6 7]
```

### 💻 Ejemplo 14 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la resta
vctr_add = vctr1-vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [ 9 18 27 36 45]
```

### 💻 Ejemplo 15 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la multiplicación
vctr_add = vctr1*vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [ 10  40  90 160 250]
```

### 💻 Ejemplo 16 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la divicion
vctr_add = vctr1/vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [10. 10. 10. 10. 10.]
```

### 💻 Ejemplo 17 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,1,1,1,1]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la operación
vctr_dot = vctr1.dot(vctr2)
print("la respues es: " , vctr_dot)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 1 1 1 1]
la respues es:  150
```

### 💻 Ejemplo 18 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 2,2,2,2,2]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la operación
vctr_dot = vctr1.dot(vctr2)
print("la respues es: " , vctr_dot)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[2 2 2 2 2]
la respues es:  300
```




---
# 📘 Numpy
---

> Este apartado corresponde al notebook **Numpy**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
# importar numpy as np
import numpy as np
```

### 💻 Ejemplo 2 (versión alternativa)

```python
# aquí estamos creando lista con numeros primos
import numpy as np

primos = [2, 3, 5, 7, 11, 13, 17, 19, 23, 29] #Variables de numeros primos

primos = np.array(primos)

print(primos)
```
📤 **Resultado mostrado:**

```
[ 2  3  5  7 11 13 17 19 23 29]
```

### 💻 Ejemplo 3 (versión alternativa)

```python
# aquí estamos creando array a partir de lista

import numpy as np
lista = [1, 2, 3, 4, 5]
array = np.array(lista)
print(array)
```
📤 **Resultado mostrado:**

```
[1 2 3 4 5]
```

### 💻 Ejemplo 4 (versión alternativa)

```python
# aquí estamos creando arrays con ceros o cómo inicializar un arreglo de numpy
import numpy as np
array_zeros=np.zeros(10)
array_zeros
```
📤 **Resultado mostrado:**

```
array([0., 0., 0., 0., 0., 0., 0., 0., 0., 0.])
```

### 💻 Ejemplo 5 (versión alternativa)

```python
# aquí estamos creando arrays con números
import numpy as np
array_numeros=np.arange(10)
array_numeros
```
📤 **Resultado mostrado:**

```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```

### 💻 Ejemplo 6 (versión alternativa)

```python
# array con numeros sucesivos
import numpy as np
arrays_impares=np.arange(0,20,2)
arrays_impares
```
📤 **Resultado mostrado:**

```
array([ 0,  2,  4,  6,  8, 10, 12, 14, 16, 18])
```

### 💻 Ejemplo 7 (versión alternativa)

```python
# haciendo un reshape para dos dimensiones
import numpy as np

# aquí estamos creando un array con los primeros 10 números pares
array_pares = np.arange(0, 20, 2)  # [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]

# Cambiar su forma a 2 filas y 5 columnas
array_reshape = array_pares.reshape(2, 5)

print(array_reshape)
```
📤 **Resultado mostrado:**

```
[[ 0  2  4  6  8]
 [10 12 14 16 18]]
```

### 💻 Ejemplo 8 (versión alternativa)

```python
# operaciones aritmeticas sobre np array 1-dimension y 2-dimension
array_impares=array_pares +1
array_impares
```
📤 **Resultado mostrado:**

```
array([ 1,  3,  5,  7,  9, 11, 13, 15, 17, 19])
```

### 💻 Ejemplo 9 (versión alternativa)

```python
# multiplicar por 100
array_impares *100
```
📤 **Resultado mostrado:**

```
array([ 100,  300,  500,  700,  900, 1100, 1300, 1500, 1700, 1900])
```

### 💻 Ejemplo 10 (versión alternativa)

```python
# resta entre arrays
array_impares - array_pares
```
📤 **Resultado mostrado:**

```
array([1, 1, 1, 1, 1, 1, 1, 1, 1, 1])
```

### 💻 Ejemplo 11 (versión alternativa)

```python
# cuidado con la división entre cero
array_impares/array_pares
```
📤 **Resultado mostrado:**

```
/tmp/ipython-input-4036163409.py:2: RuntimeWarning: divide by zero encountered in divide
  array_impares/array_pares
array([       inf, 1.5       , 1.25      , 1.16666667, 1.125     ,
       1.1       , 1.08333333, 1.07142857, 1.0625    , 1.05555556])
```

### 💻 Ejemplo 12 (versión alternativa)

```python
# métodos asociados a estadística
# suma

array_pares.sum()
```
📤 **Resultado mostrado:**

```
np.int64(90)
```

### 💻 Ejemplo 13 (versión alternativa)

```python
# promedio
array_pares.mean()
```
📤 **Resultado mostrado:**

```
np.float64(9.0)
```

### 💻 Ejemplo 14 (versión alternativa)

```python
# varianza
array_pares.var()
```
📤 **Resultado mostrado:**

```
np.float64(33.0)
```

### 💻 Ejemplo 15 (versión alternativa)

```python
# como ordenar un np array
array_fibonacci=np.array([55, 0, 144, 1, 21, 89, 5, 8, 13, 1, 34, 3, 2])
array_fibonacci
```
📤 **Resultado mostrado:**

```
array([ 55,   0, 144,   1,  21,  89,   5,   8,  13,   1,  34,   3,   2])
```

### 💻 Ejemplo 16 (versión alternativa)

```python
# orden ascendente: de menor a mayor
np.sort(array_fibonacci)
```
📤 **Resultado mostrado:**

```
array([  0,   1,   1,   2,   3,   5,   8,  13,  21,  34,  55,  89, 144])
```

### 💻 Ejemplo 17 (versión alternativa)

```python
# orden descendente: de mayor a menor
-np.sort(-array_fibonacci)
```
📤 **Resultado mostrado:**

```
array([144,  89,  55,  34,  21,  13,   8,   5,   3,   2,   1,   1,   0])
```

### 💻 Ejemplo 18 (versión alternativa)

```python
# Como seleccionar elements
```

### 💻 Ejemplo 19 (versión alternativa)

```python
# Seleccionar un elemento
```

### 💻 Ejemplo 20 (versión alternativa)

```python
A = np.arange(0,20,2).reshape(2,5)
A
```
📤 **Resultado mostrado:**

```
array([[ 0,  2,  4,  6,  8],
       [10, 12, 14, 16, 18]])
```

### 💻 Ejemplo 21 (versión alternativa)

```python
# seleccionar el primer elemento
A[0,0]
```
📤 **Resultado mostrado:**

```
np.int64(0)
```

### 💻 Ejemplo 22 (versión alternativa)

```python
# seleccionar algún otro elemento
A[1,3]
```
📤 **Resultado mostrado:**

```
np.int64(16)
```

### 💻 Ejemplo 23 (versión alternativa)

```python
# Seleccionar varios elementos
```

### 💻 Ejemplo 24 (versión alternativa)

```python
# seleccionar por fila
A[1:]
```
📤 **Resultado mostrado:**

```
array([[10, 12, 14, 16, 18]])
```

### 💻 Ejemplo 25 (versión alternativa)

```python
# seleccionar por columna
A[:,3]
```
📤 **Resultado mostrado:**

```
array([ 6, 16])
```

### 💻 Ejemplo 26 (versión alternativa)

```python
# Utilizar filter
```

### 💻 Ejemplo 27 (versión alternativa)

```python

```

### 💻 Ejemplo 28 (versión alternativa)

```python
# conidicion para menores de 20
```

### 💻 Ejemplo 29 (versión alternativa)

```python
# filtrar menores de 20
```

### 💻 Ejemplo 30 (versión alternativa)

```python

```




---
# 📘 Pilas
---

> Este apartado corresponde al notebook **Pilas**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
pila =[]
# push
pila.append("a")
pila.append("b")
pila.append("c")
print(pila)
```
📤 **Resultado mostrado:**

```
['a', 'b', 'c']
```

### 💻 Ejemplo 2 (versión alternativa)

```python
pila =['a', 'b', 'c']
elenemto=pila.pop()
print(pila)
```
📤 **Resultado mostrado:**

```
['a', 'b']
```

### 💻 Ejemplo 3 (versión alternativa)

```python
pila =['a', 'b', 'c']

cima= pila[-1]
print(pila)
print(cima)
```
📤 **Resultado mostrado:**

```
['a', 'b', 'c']
c
```

### 💻 Ejemplo 4 (versión alternativa)

```python
pila =[]
if not pila:
  print("vacia")
else:
  print("con elementos")
```
📤 **Resultado mostrado:**

```
vacia
```

### 💻 Ejemplo 5 (versión alternativa)

```python
pila=[10,20,30,40]
tamaño=len(pila)
print(f"tamaño: {tamaño}")
```
📤 **Resultado mostrado:**

```
tamaño: 4
```

### 💻 Ejemplo 6 (versión alternativa)

```python
def invertir_palabra(palabra):
  pila = [ ]

  for letra in palabra:
    pila.append(letra)

  invertida = ""
  while pila:
      invertida+=pila.pop()

  return invertida

print(invertir_palabra("python"))
```
📤 **Resultado mostrado:**

```
nohtyp
```

### 💻 Ejemplo 7 (versión alternativa)

```python
# cambiar un decimal a binario
def decimal_a_binario(n):
    pila=[]
    while n>0:
      pila.append(n%2)
      n //= 2
    binario =""
    while pila:
        binario += str(pila.pop())
    return binario

print(decimal_a_binario(25))
```
📤 **Resultado mostrado:**

```
11001
```

### 💻 Ejemplo 8 (versión alternativa)

```python

```




---
# 📘 Ejercicios Parcial 1
---

> Este apartado corresponde al notebook **Ejercicios Parcial 1**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
usuarios_registrados = ["ana_dev", "luis_ux", "carlos_pm"]

usuarios_unicos =set(usuarios_registrados)

nuevos_usuarios = input("👉 Ingresa tu nombre de usuario: ")


if nuevos_usuarios in usuarios_unicos:
  print(f"el usuario {nuevos_usuarios} ya esta registrado")

else :
    usuarios_registrados.append(nuevos_usuarios)
    usuarios_unicos.add(nuevos_usuarios)

    print("lista de usuarios registrados ")
    print(usuarios_registrados)
    print("\n lista de usuarios unicos")
    print(usuarios_unicos)
```
📤 **Resultado mostrado:**

```
👉 Ingresa tu nombre de usuario: luis_ux
el usuario luis_ux ya esta registrado
```

### 💻 Ejemplo 2 (versión alternativa)

```python
ventas_precios = [15.50 , 20.00, 5.75 , 15.50, 30.00]
productos_vendidos= ["cafe", "torta", "galleta", "cafe", "almuezo"]

ingresos_totales = sum(ventas_precios)
productos_unicos = set(productos_vendidos)

print(f" los ingresos toales son {ingresos_totales}")
print(f" la cantidad de productos unicos es de {len(productos_unicos)}")
```
📤 **Resultado mostrado:**

```
los ingresos toales son 86.75
 la cantidad de productos unicos es de 4
```

### 💻 Ejemplo 3 (versión alternativa)

```python
tareas=["enviar reporte", "revisar correos"]
nueva_tarea="llamar al cliente"
tareas.append(nueva_tarea)

print(f" la lista actualizada de las tareas:\n {tareas}")
tareas[0]= "enviar reporte(completado)"
print(f"lista final de tareas: \n{tareas}")
```
📤 **Resultado mostrado:**

```
la lista actualizada de las tareas:
 ['enviar reporte', 'revisar correos', 'llamar al cliente']
lista final de tareas: 
['enviar reporte(completado)', 'revisar correos', 'llamar al cliente']
```

### 💻 Ejemplo 4 (versión alternativa)

```python
asistentes_ingresados = {"id_1122","id_3344"}
persona_llegando ="id_5566"

persona_consola= input("ingrese su id")
if persona_llegando in asistentes_ingresados:
  print(f"su id {persona_llegando} ya esta registrado, lo siento")

else:
  asistentes_ingresados.add(persona_llegando)
  asistentes_ingresados.add(persona_consola)

  print(f" lista final de asistentes ingresados  es: \n {asistentes_ingresados}")
```
📤 **Resultado mostrado:**

```
ingrese su idid_232323
 lista final de asistentes ingresados  es: 
 {'id_3344', 'id_5566', 'id_1122', 'id_232323'}
```




---
# 📘 Ejercicios Pre-Parcial
---

> Este apartado corresponde al notebook **Ejercicios Pre-Parcial**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
# 1
usuarios_registrados = ["ana_dev", "luis_ux", "carlos_pm"]

usuarios_unicos = set(usuarios_registrados)# Creamos un set para verificación rápida
nuevo_usuario = "luis_ux"# Llegada de un nuevo usuario

if nuevo_usuario in usuarios_unicos:
    print(f"El usuario '{nuevo_usuario}' ya existe.")
else:
    usuarios_registrados.append(nuevo_usuario)
    usuarios_unicos.add(nuevo_usuario)


nuevo_usuario = "sofia_qa"# Repetimos con otro usuario

if nuevo_usuario in usuarios_unicos:
    print(f"El usuario '{nuevo_usuario}' ya existe.")
else:
    usuarios_registrados.append(nuevo_usuario)
    usuarios_unicos.add(nuevo_usuario)

#  resultados
print("Lista final de usuarios registrados (ordenada)",usuarios_registrados)
print("Conjunto de usuarios únicos",usuarios_unicos)
```
📤 **Resultado mostrado:**

```
El usuario 'luis_ux' ya existe.
Lista final de usuarios registrados (ordenada) ['ana_dev', 'luis_ux', 'carlos_pm', 'sofia_qa']
Conjunto de usuarios únicos {'ana_dev', 'sofia_qa', 'carlos_pm', 'luis_ux'}
```

### 💻 Ejemplo 2 (versión alternativa)

```python
# 2

ventas_precios = [15.50, 20.00, 5.75, 15.50, 30.00]
productos_vendidos = ["cafe", "torta", "galleta", "cafe", "almuerzo"]

ingresos_totales = sum(ventas_precios)#Calcular total de ingresos a partir del metodo sum

productos_unicos = set(productos_vendidos)#Crear un conjunto para obtener productos únicos

# resultados
print(f"Ingresos totales del día: ${ingresos_totales:.2f}")
print(f"Número de productos únicos vendidos: {len(productos_unicos)}")
print(f"Productos únicos: {productos_unicos}")
```
📤 **Resultado mostrado:**

```
Ingresos totales del día: $86.75
Número de productos únicos vendidos: 4
Productos únicos: {'torta', 'almuerzo', 'galleta', 'cafe'}
```

### 💻 Ejemplo 3 (versión alternativa)

```python
# 3
tareas = ["Enviar reporte", "Revisar correos"]

nueva_tarea = "Llamar al cliente"#  se añade nueva tarea
tareas.append(nueva_tarea)
print("Lista de tareas actualizada:")# Mostramos lalista actualizada
print(tareas)

tareas[0] = tareas[0] + " (Completada)"# marcamos la primera tarea como completada

# esta es una lista final
print("Lista final de tareas:")
print(tareas)
```

### 💻 Ejemplo 4 (versión alternativa)

```python
#4
asistentes_ingresados = ["ID_1122", "ID_3344"]

asistentes_ingresados.append("ID_5566")# Persona que llega


persona_llegando = input("Ingresa el ID de la persona que llega: ")# en este paso definimos un input para solicitar el numero de id que va a ingresarar
if persona_llegando in asistentes_ingresados:# en este paso definimos un if para la condicion, si ya ingreso o si es un id nuevo ingreso
    print("Ya has ingresado.")
else:
    asistentes_ingresados.add(persona_llegando)
    print("Bienvenido")

print("Asistentes finales:", asistentes_ingresados)# se imprimen las lista con los id ingresados unicos
```
📤 **Resultado mostrado:**

```
Ingresa el ID de la persona que llega: ID_1122
Ya has ingresado.
Asistentes finales: ['ID_1122', 'ID_3344', 'ID_5566']
```

### 💻 Ejemplo 5 (versión alternativa)

```python
#5
calificaciones = [3.5, 4.0, 5.0, 2.5, 3.5, 4.0, 4.8]
promedio = sum(calificaciones) / len(calificaciones)# se realiza el promedio de las calificacion con la suma de ellas y saando al longitud de ellas (sum / len)
notas_unicas = set(calificaciones) # en este paso definimos el set de las notas unicas, esto sacara los duplicados cuando se imprima

print(f"Promedio: {promedio:.2f}")# el .2 es para darle . 2 decimales al resultado

print("Notas únicas:", notas_unicas)
```
📤 **Resultado mostrado:**

```
Promedio: 3.90
Notas únicas: {2.5, 3.5, 4.8, 4.0, 5.0}
```

### 💻 Ejemplo 6 (versión alternativa)

```python
#6
tallas_disponibles = ["S", "M", "L", "M"]# esta es una lista de tallas que tenemos (hay repetidas)
tallas_unicas = set(tallas_disponibles)# convertir la lista en conjunto para que no se repitan

nueva_talla = "XL"# llega una nueva talla y la metemos al conjunto
tallas_unicas.add(nueva_talla)

tallas_unicas.add("S")# probamos a meter otra vez la "S" (pero no se repite en conjuntos)

# mostramos cómo quedó el conjunto
print("Tallas únicas disponibles:", tallas_unicas)
```

### 💻 Ejemplo 7 (versión alternativa)

```python
#7
mis_sugerencias = ["París", "Roma", "Berlín"]# mis destinos sugeridos
sugerencias_amigo = ["Londres", "Roma", "Praga"]# lo que sugirió mi amigo

set_mis_sugerencias = set(mis_sugerencias)# paso 1: convertir las listas en conjuntos (así quitamos repetidos)
set_sugerencias_amigo = set(sugerencias_amigo)

destinos_finales = set_mis_sugerencias.union(set_sugerencias_amigo)# paso 2: unir los dos conjuntos para tener todos los destinos sin repetir

# paso 3: mostrar cómo quedó la lista final
print("Destinos finales únicos:", destinos_finales)
print("Cantidad total de destinos únicos:", len(destinos_finales))
```

### 💻 Ejemplo 8 (versión alternativa)

```python
# Caso 8: Análisis de Encuesta

respuestas = [5, 4, 3, 5, 5, 2, 4, 5, 1, 5]# esta es una lista con las respuestas de la encuesta (del 1 = muy insatisfecho, al 5 = muy satisfecho)


contador_max_satisfaccion = 0 # Variable para contar cuántas personas respondieron "5" (muy satisfecho)


for r in respuestas:# Recorremos la lista de respuestas
    if r == 5:  # Si la respuesta es 5, aumentamos el contador
        contador_max_satisfaccion += 1


respuestas_unicas = set(respuestas)# Usamos un conjunto (set) para ver solo las respuestas únicas que aparecieron

# Mostramos los resultados
print("Opciones únicas de respuesta en la encuesta:", respuestas_unicas)
print("Total de personas 'muy satisfechas' (5):", contador_max_satisfaccion)
```
📤 **Resultado mostrado:**

```
Opciones únicas de respuesta en la encuesta: {1, 2, 3, 4, 5}
Total de personas 'muy satisfechas' (5): 5
```

### 💻 Ejemplo 9 (versión alternativa)

```python
# Caso 9: Gestión de Ingredientes para una Receta
ingredientes_masa = ["harina", "mantequilla", "agua", "sal"]# esta es una lista de ingredientes para la masa
ingredientes_relleno = ["queso", "espinaca", "huevo", "sal"]# esta es una lista de ingredientes para el relleno


ingredientes_totales = ingredientes_masa + ingredientes_relleno #Combinamos ambas listas en una sola
ingredientes_unicos = set(ingredientes_totales)# usamos un conjunto (set) para eliminar duplicados
lista_compras_final = list(ingredientes_unicos)#Convertimos el set de nuevo a lista (opcional, para que se vea como lista)

# Mostramos el resultado
print("Lista de compras final (sin duplicados):", lista_compras_final)
```
📤 **Resultado mostrado:**

```
Lista de compras final (sin duplicados): ['espinaca', 'mantequilla', 'huevo', 'harina', 'sal', 'agua', 'queso']
```

### 💻 Ejemplo 10 (versión alternativa)

```python
# Caso 10: Filtrado de Correo Electrónico

spam_emails = {"spam1@example.com", "ofertas@mal.com", "dudoso@mail.net"}# Conjunto con los correos que están en la lista negra (spam)

correo_entrante = "usuario.normal@email.com" #Creamos una variable con un correo entrante (caso 1)
log_verificaciones = [] # esta es una lista para registrar los correos verificados

if correo_entrante in spam_emails: #Verificamos si el primer correo está en la lista de spam
    print("Alerta de SPAM:", correo_entrante)
else:
    print("Correo seguro:", correo_entrante)


log_verificaciones.append(correo_entrante)# Agregamos al log


correo_entrante = "ofertas@mal.com"  # Repetimos el proceso con otro correo (caso 2)

if correo_entrante in spam_emails:
    print("Alerta de SPAM:", correo_entrante)
else:
    print("Correo seguro:", correo_entrante)

log_verificaciones.append(correo_entrante)

# Mostramos el log de correos verificados
print("Registro de correos verificados:", log_verificaciones)
```
📤 **Resultado mostrado:**

```
Correo seguro: usuario.normal@email.com
Alerta de SPAM: ofertas@mal.com
Registro de correos verificados: ['usuario.normal@email.com', 'ofertas@mal.com']
```

### 💻 Ejemplo 11 (versión alternativa)

```python
# Integrantes jaja
integrantes = ["david Ballesteros", "Juan Castillo", " Mateo Franco", "Alan Melo Giraldo"]
print(integrantes)
```
📤 **Resultado mostrado:**

```
['david Ballesteros', 'Juan Castillo', ' Mateo Franco', 'Alan Melo Giraldo']
```

### 💻 Ejemplo 12 (versión alternativa)

```python

```
📤 **Resultado mostrado:**

```
sumar vector1 vector2
```

### 💻 Ejemplo 13 (versión alternativa)

```python
import numpy as np

# aquí estamos creando dos vectores
vector1 = np.array([1, 2, 3])
vector2 = np.array([4, 5, 6])

# Calcular el producto punto
producto_punto = np.dot(vector1, vector2)

# mostramos en pantalla el resultado
print(f"Vector 1: {vector1}")
print(f"Vector 2: {vector2}")
print(f"El producto punto es: {producto_punto}")
```
📤 **Resultado mostrado:**

```
Vector 1: [1 2 3]
Vector 2: [4 5 6]
El producto punto es: 32
```




---
# 📘 Ejercicios Pre-Parcial 2
---

> Este apartado corresponde al notebook **Ejercicios Pre-Parcial 2**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
#1
compras= ["leche", "pan"]
compras.append("huevos")# con append se agrega a la lista
print(compras)
```
📤 **Resultado mostrado:**

```
['leche', 'pan', 'huevos']
```

### 💻 Ejemplo 2 (versión alternativa)

```python
#2
perfil_usuario = {
    "nombre": input("Introduce el nombre del usuario: "),
    "edad": int(input("Introduce la edad del usuario: "))}

nueva_edad = int(input("Introduce la nueva edad del usuario: "))# Actualizar la edad del usuario
perfil_usuario["edad"] = nueva_edad
perfil_usuario["ciudad"] = input("Introduce la ciudad del usuario: ")# Añadir la clave "ciudad"
print(perfil_usuario)
```
📤 **Resultado mostrado:**

```
Introduce el nombre del usuario: alan
Introduce la edad del usuario: 78
Introduce la nueva edad del usuario: 98
Introduce la ciudad del usuario: bogota
{'nombre': 'alan', 'edad': 98, 'ciudad': 'bogota'}
```

### 💻 Ejemplo 3 (versión alternativa)

```python
#3
coordenadas =(40.7128, -74.0060) # creamos la tupla
lat , long = coordenadas # lo desempaquetamos
print(lat, long)# se imprime
```
📤 **Resultado mostrado:**

```
40.7128 -74.006
```

### 💻 Ejemplo 4 (versión alternativa)

```python
#4
temperaturas = [22.5, 24.0, 21.8, 25.1, 23.9, 22.7, 21.5]
prom= sum(temperaturas)/len(temperaturas) # se genera una variable para el promedio donde lleva la suma de las temperaturas y la longitud de ellas
print(prom)
```
📤 **Resultado mostrado:**

```
23.071428571428573
```

### 💻 Ejemplo 5 (versión alternativa)

```python
#5
diccionario ={'hi':'hola','tomorrow':'mañana','yesterday':'ayer','yellow':'amarillo','smart':'inteligente', 'goodbye':'adios','thanks':'gracias','sorry':'lo siento'}


busqueda=input("digite la palabra que desea buscar en ingles").lower()# se realiza un imput para solicitar la palabra al ususario

if busqueda in diccionario:# en este paso definimos un if para la condicion, en este caso con un .get para buscar la pabara y verificar si se encuentra
    print(diccionario.get(busqueda))
else:
    print("la palabra no se encuentra en el diccionario")
```
📤 **Resultado mostrado:**

```
digite la palabra que desea buscar en inglesplease
la palabra no se encuentra en el diccionario
```

### 💻 Ejemplo 6 (versión alternativa)

```python
#6
horario=(('matematicas','08:00am'),('fisica','10:00am'),('historia','12:00pm'))

#recorremoe el horarioy lo imprimimos cada clase
print('horariodeclases es:')
for materia, hora in horario:
  print(f"{materia} - {hora}")
```
📤 **Resultado mostrado:**

```
horariodeclases es:
matematicas - 08:00am
fisica - 10:00am
historia - 12:00pm
```

### 💻 Ejemplo 7 (versión alternativa)

```python
#7
invitados_dia = ["Ana", "Luis", "Marta", "Pedro"]
invitados_noche = ["Luis", "Sofía", "Ana", "Juan"]

invitadostotal= list(set(invitados_dia + invitados_noche))# creamos una variable para poder unir las listas con set
print(invitadostotal)
```
📤 **Resultado mostrado:**

```
['Marta', 'Ana', 'Luis', 'Sofía', 'Pedro', 'Juan']
```

### 💻 Ejemplo 8 (versión alternativa)

```python
#8
inventario = [
    {"nombre": "Laptop", "precio": 900, "stock": 15},{"nombre": "Teléfono", "precio": 500, "stock": 30},{"nombre": "Tablet", "precio": 250, "stock": 20},{"nombre": "Auriculares", "precio": 100, "stock": 50},
    {"nombre": "Cargador", "precio": 25, "stock": 100}]
producto_buscar = input("Introduce el nombre del producto: ").lower()# Pedir al usuario el nombre del producto a buscar
producto_encontrado = next((producto for producto in inventario if producto["nombre"].lower() == producto_buscar), None)# Buscar el producto en el inventario

if producto_encontrado:
    print(f"Producto encontrado: {producto_encontrado}")
else:
    print("Producto no encontrado.")
```
📤 **Resultado mostrado:**

```
Introduce el nombre del producto: celular
Producto no encontrado.
```

### 💻 Ejemplo 9 (versión alternativa)

```python
#9
estudiantes = {"Ana": 4.5, "Luis": 3.8, "Marta": 4.8, "Pedro": 3.9}

estudiantes["Pedro"] = 2.9# Actualizar la calificación de Pedro
print(estudiantes)
```
📤 **Resultado mostrado:**

```
{'Ana': 4.5, 'Luis': 3.8, 'Marta': 4.8, 'Pedro': 2.9}
```

### 💻 Ejemplo 10 (versión alternativa)

```python
# 10
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
pares = [numero for numero in numeros if numero % 2 == 0]# aquí estamos creando una nueva lista con solo los números pares utilizando lista por comprensión
print(pares)
```
📤 **Resultado mostrado:**

```
[2, 4, 6, 8, 10]
```

### 💻 Ejemplo 11 (versión alternativa)

```python
#11
estudiantes = [
    {"nombre": "Ana", "promedio": 4.5, "curso": "10A"},
    {"nombre": "Luis", "promedio": 3.8, "curso": "10B"},
    {"nombre": "Marta", "promedio": 4.8, "curso": "10A"},
    {"nombre": "Pedro", "promedio": 3.9, "curso": "10C"},
    {"nombre": "Sofía", "promedio": 4.2, "curso": "10B"}
]

buenprom= [estudiante["promedio"] for estudiante in estudiantes if estudiante["promedio"] >= 4.5]# en este paso definimos una variable para sacar el promedio de los estudiantes
print(buenprom)
nombres_estudiantes = [estudiante["nombre"] for estudiante in estudiantes]# en este paso definimos una variable para sacar el listado de el nombre  de los estudiantes
print(nombres_estudiantes)
```
📤 **Resultado mostrado:**

```
[4.5, 4.8]
['Ana', 'Luis', 'Marta', 'Pedro', 'Sofía']
```

### 💻 Ejemplo 12 (versión alternativa)

```python
#12
ventas = [
    ("Laptop", "Electrónica", 1500),
    ("Camisa", "Ropa", 80),
    ("Mouse", "Electrónica", 50),
    ("Pantalón", "Ropa", 120),
    ("Teclado", "Electrónica", 70)
]

# Diccionario para almacenar el total de ventas por categoría
total_ventas = {}

# Recorrer las ventas y sumar el monto a la categoría correspondiente
for producto, categoria, monto in ventas:
    if categoria in total_ventas:
        total_ventas[categoria] += monto  # Si la categoría ya existe, sumar el monto
    else:
        total_ventas[categoria] = monto  # Si la categoría no existe, crearla con el monto inicial

# Mostrar el total de ventas por categoría
print(total_ventas)
```
📤 **Resultado mostrado:**

```
{'Electrónica': 1620, 'Ropa': 200}
```

### 💻 Ejemplo 13 (versión alternativa)

```python
#13

libro = {
    "titulo": "Python para Todos",
    "año": 2024,
    "autores": [
        {"nombre": "Raúl", "nacionalidad": "Española"},
        {"nombre": "Laura", "nacionalidad": "Mexicana"}
    ],
    "editorial": "Ediciones Código"}
nombres_autores = [autor["nombre"] for autor in libro["autores"]]# aquí estamos creando una lista con los nombres de los autore
print(nombres_autores)# Mostrar la lista de nombres de los autores
```
📤 **Resultado mostrado:**

```
['Raúl', 'Laura']
```

### 💻 Ejemplo 14 (versión alternativa)

```python
#14
# Diccionario de productos y precios
productos = {
    101: "Leche",
    102: "Pan",
    103: "Huevos"
}

precios = {
    101: 4500,
    102: 2500,
    103: 8000
}

ventas_del_dia = [
    (101, 5),  # Se vendieron 5 unidades de Leche
    (102, 10), # Se vendieron 10 unidades de Pan
    (101, 3),  # Se vendieron otras 3 unidades de Leche
    (103, 2)   # Se vendieron 2 unidades de Huevos
]
ingreso_total = 0


for id_producto, cantidad in ventas_del_dia:# Recorrer las ventas del día
    precio = precios[id_producto]# Obtener el precio del producto usando su ID
    ingreso_total += precio * cantidad# Calcular el ingreso de esa venta y sumarlo al total
print(f"Ingreso total del día: {ingreso_total}")
```
📤 **Resultado mostrado:**

```
Ingreso total del día: 77000
```


# 📘 Parcial 2 - Programas en Python

Este documento contiene varios programas en Python desarrollados como parte del **Parcial 2**.  
Cada programa está comentado y estructurado para un mejor entendimiento.

---

## 🛒 1. Carrito de Compras

Este programa simula un carrito de compras en el que el usuario puede:

- Agregar productos  
- Eliminar productos  
- Ver el contenido del carrito  
- Salir del programa  

```python
# Programa que simula un carrito de compras
carrito = []

while True:
    print("\n--- Menú del Carrito de Compras ---")
    print("1. Agregar producto")
    print("2. Eliminar producto")
    print("3. Ver carrito")
    print("4. Salir")

    opcion = input("Elige una opción (1-4): ")

    if opcion == "1":
        producto = input("Ingresa el nombre del producto a agregar: ")
        carrito.append(producto)
        print(f"✅ '{producto}' fue agregado al carrito.")
    elif opcion == "2":
        if len(carrito) == 0:
            print("⚠️ El carrito está vacío.")
        else:
            producto = input("Ingresa el nombre del producto a eliminar: ")
            if producto in carrito:
                carrito.remove(producto)
                print(f"🗑️ '{producto}' fue eliminado.")
            else:
                print(f"⚠️ '{producto}' no está en el carrito.")
    elif opcion == "3":
        if len(carrito) == 0:
            print("🛒 El carrito está vacío.")
        else:
            print("🛒 Contenido del carrito:")
            for i, p in enumerate(carrito, start=1):
                print(f"{i}. {p}")
    elif opcion == "4":
        print("👋 Saliendo del programa. ¡Gracias por usar el carrito!")
        break
    else:
        print("❌ Opción no válida.")
```

---

## 👥 2. Registro de Usuarios con Roles

Este programa permite registrar usuarios con roles **fijos**:  
`admin`, `editor`, `visitante`.

```python
roles_validos = ["admin", "editor", "visitante"]
usuarios_registrados = []

while True:
    print("\n--- Registro de Usuarios ---")
    nombre = input("Ingresa el nombre (o 'salir' para terminar): ")

    if nombre.lower() == "salir":
        print("👋 Registro finalizado.")
        break

    rol = input("Ingresa el rol (admin, editor, visitante): ").lower()

    if rol in roles_validos:
        usuario = (nombre, rol)
        usuarios_registrados.append(usuario)
        print(f"✅ Usuario registrado: {usuario}")
    else:
        print("❌ Rol inválido.")

print("\n📋 Lista final de usuarios registrados:")
for u in usuarios_registrados:
    print(f"- Nombre: {u[0]}, Rol: {u[1]}")
```

---

## 📒 3. Agenda de Contactos

Usa un **diccionario** para guardar contactos en la forma `Nombre → Teléfono`.

```python
agenda = {}

while True:
    print("\n--- Menú de Agenda ---")
    print("1. Agregar contacto")
    print("2. Buscar teléfono por nombre")
    print("3. Mostrar todos los contactos")
    print("4. Salir")

    opcion = input("Elige una opción (1-4): ")

    if opcion == "1":
        nombre = input("Ingresa el nombre: ").capitalize()
        telefono = input("Ingresa el teléfono: ")
        agenda.update({nombre: telefono})
        print(f"✅ {nombre} - {telefono} agregado.")
    elif opcion == "2":
        nombre = input("Ingresa el nombre a buscar: ").capitalize()
        telefono = agenda.get(nombre)
        if telefono:
            print(f"📞 Teléfono de {nombre}: {telefono}")
        else:
            print(f"❌ {nombre} no está en la agenda.")
    elif opcion == "3":
        if len(agenda) == 0:
            print("📂 La agenda está vacía.")
        else:
            print("\n📋 Lista de contactos:")
            for nombre, telefono in agenda.items():
                print(f"- {nombre}: {telefono}")
    elif opcion == "4":
        print("👋 Saliendo de la agenda.")
        break
    else:
        print("❌ Opción no válida.")
```

---

## 🎨 4. Sistema de Votación de Colores

Los usuarios pueden votar por su color favorito.  
Los votos se almacenan en un **diccionario**.

```python
votos = {
    "rojo": 0,
    "azul": 0,
    "verde": 0,
    "amarillo": 0
}

while True:
    print("\n--- Votación de Colores ---")
    print("Opciones:", ", ".join(votos.keys()))
    print("Escribe 'salir' para terminar.")

    color = input("Ingresa tu color favorito: ").lower()

    if color == "salir":
        print("🗳️ Votación finalizada.")
        break
    if color in votos:
        votos[color] += 1
        print(f"✅ Voto registrado por '{color}'.")
    else:
        print("❌ Opción no válida.")

print("\n📊 Resultados finales:")
for color, cantidad in votos.items():
    print(f"- {color.capitalize()}: {cantidad} votos")
```

---

## 🌳 5. Árbol Binario de Búsqueda

Implementación de un **árbol binario de búsqueda (ABB)** con inserción, búsqueda y recorrido **inorden**.

```python
class Nodo:
    def __init__(self, valor):
        self.valor = valor
        self.izquierda = None
        self.derecha = None

class ArbolBinario:
    def __init__(self):
        self.raiz = None

    def insertar(self, valor):
        if self.raiz is None:
            self.raiz = Nodo(valor)
            print(f'Insertado {valor} como raíz')
        else:
            self._insertar_recursivo(self.raiz, valor)

    def _insertar_recursivo(self, nodo, valor):
        if valor < nodo.valor:
            if nodo.izquierda is None:
                nodo.izquierda = Nodo(valor)
                print(f'Insertado {valor} a la izquierda de {nodo.valor}')
            else:
                self._insertar_recursivo(nodo.izquierda, valor)
        else:
            if nodo.derecha is None:
                nodo.derecha = Nodo(valor)
                print(f'Insertado {valor} a la derecha de {nodo.valor}')
            else:
                self._insertar_recursivo(nodo.derecha, valor)

    def buscar(self, valor):
        return self._buscar_recursivo(self.raiz, valor)

    def _buscar_recursivo(self, nodo, valor):
        if nodo is None:
            return False
        if nodo.valor == valor:
            return True
        elif valor < nodo.valor:
            return self._buscar_recursivo(nodo.izquierda, valor)
        else:
            return self._buscar_recursivo(nodo.derecha, valor)

    def recorrido_inorden(self, nodo):
        resultado = []
        if nodo:
            resultado = self.recorrido_inorden(nodo.izquierda)
            resultado.append(nodo.valor)
            resultado = resultado + self.recorrido_inorden(nodo.derecha)
        return resultado

# === PROGRAMA DE EJEMPLO ===
print("=== Creando Árbol Binario de Búsqueda ===")
arbol = ArbolBinario()
valores = [10, 5, 15, 3, 7, 12, 20]
for valor in valores:
    arbol.insertar(valor)

print("\n=== Recorrido Inorden (valores ordenados) ===")
print(arbol.recorrido_inorden(arbol.raiz))

print("\n=== Buscando valores ===")
print(f'¿Existe 7? {arbol.buscar(7)}')
print(f'¿Existe 25? {arbol.buscar(25)}')
```


---
# 📘 Colas
---

> Este apartado corresponde al notebook **Colas**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
from collections import deque

eventos=deque()

while True:
  print("\n menu de la agenda")
  print("1 agregar un evento")
  print("2 ver eventos")
  print("3 eliminar primer evento")
  print("4 salir")

  op=input("digite la opción ")

  if op=="1":
    evento=input("escriba el evento: ")
    eventos.append(evento)
    print(f"el evento {evento} fue agregado")

  elif op=="2":
    if eventos:
      print(" eventos en la agenda")
      for i, e in enumerate(eventos, start=1):
        print(f"\n {i}. {e}")
    else:
      print("no hay eventos que mostrar")

  elif op=="3":
    if eventos:
      eliminado=eventos.popleft()
      print(f"el evento {eliminado} fue eliminado")
    else:
      print("no hay eventos para eliminar")

  elif op=="4":
    print("saliendo de la agenda")
    break
  else:
    print("opcion invalida, intente otra vez")
```
📤 **Resultado mostrado:**

```
menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
digite la opción 1
escriba el evento: salir
el evento salir fue agregado

 menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
digite la opción 1
escriba el evento: comer
el evento comer fue agregado

 menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
digite la opción 2
 eventos en la agenda
1. salir
2. comer

 menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
```

### 💻 Ejemplo 2 (versión alternativa)

```python
()
```




---
# 📘 Diccionarios (extra)
---

> Este apartado corresponde al notebook **Diccionarios (extra)**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
#Crea un diccionario persona con tu nombre, edad y ciudad. Luego imprime solo el valor de la ciudad.
persona = {'nombre':'lan' , 'edad':'28', 'ciudad':'bogota'}
print(persona['ciudad'])
```
📤 **Resultado mostrado:**

```
bogota
```

### 💻 Ejemplo 2 (versión alternativa)

```python
#A un diccionario frutas = {"manzana": 10, "pera": 5, "naranja": 8} agrega la fruta "sandía" con valor 3
frutas= {"manzana": 10, "pera": 5, "naranja": 8}
frutas['sandia']=3
print(frutas)
```
📤 **Resultado mostrado:**

```
{'manzana': 10, 'pera': 5, 'naranja': 8, 'sandia': 3}
```

### 💻 Ejemplo 3 (versión alternativa)

```python
#Cambia el valor de "pera" a 12 en el diccionario anterior.
frutas['pera']=12
print(frutas)
```
📤 **Resultado mostrado:**

```
{'manzana': 10, 'pera': 12, 'naranja': 8, 'sandia': 3}
```

### 💻 Ejemplo 4 (versión alternativa)

```python
colores = {"rojo": "#FF0000", "verde": "#00FF00", "azul": "#0000FF"}
for x in colores:
  print(colores[x])
```
📤 **Resultado mostrado:**

```
#FF0000
#00FF00
#0000FF
```

### 💻 Ejemplo 5 (versión alternativa)

```python
dato={'nombre':'camila', 'edad':'25','documento':'1234567'}
print(dato['nombre'])
print(dato['edad'])
```
📤 **Resultado mostrado:**

```
camila
25
```

### 💻 Ejemplo 6 (versión alternativa)

```python
dato['nombre']='marco'
print(dato)
```
📤 **Resultado mostrado:**

```
{'nombre': 'marco', 'edad': '25', 'documento': '1234567'}
```

### 💻 Ejemplo 7 (versión alternativa)

```python
for x in dato:
  print(x)
```
📤 **Resultado mostrado:**

```
nombre
edad
documento
```

### 💻 Ejemplo 8 (versión alternativa)

```python
for x , y in dato.items():
  print(x,y)
```
📤 **Resultado mostrado:**

```
nombre marco
edad 25
documento 1234567
```

### 💻 Ejemplo 9 (versión alternativa)

```python
dic1 = {"x": 10, "y": 20}
dic2 = {"m": 100, "n": 200}

dic3 = { "dic1":dic1, "dic2":dic2 }
print(dic3)
```
📤 **Resultado mostrado:**

```
{'dic1': {'x': 10, 'y': 20}, 'dic2': {'m': 100, 'n': 200}}
```

### 💻 Ejemplo 10 (versión alternativa)

```python
dicci={"a":1,"b":2}
dicci.clear()
print(dicci)
```
📤 **Resultado mostrado:**

```
{}
```

### 💻 Ejemplo 11 (versión alternativa)

```python
diccio={"a":1,"b":2}
print(diccio.get("a"))
print(diccio.get("c",'no encontrado'))
```
📤 **Resultado mostrado:**

```
1
no encontrado
```

### 💻 Ejemplo 12 (versión alternativa)

```python
dicci={"a":1,"b":2}
it=dicci.items()
print(it)
print(list(it))
print(list(it)[0][0])
```
📤 **Resultado mostrado:**

```
dict_items([('a', 1), ('b', 2)])
[('a', 1), ('b', 2)]
a
```

### 💻 Ejemplo 13 (versión alternativa)

```python
auto = {'marca': 'toyota', 'modelo':'corolla','año':'2020'}
print(auto.get('marca'))
```
📤 **Resultado mostrado:**

```
toyota
```

### 💻 Ejemplo 14 (versión alternativa)

```python
auto['color']='rojo'
print(auto)
```
📤 **Resultado mostrado:**

```
{'marca': 'toyota', 'modelo': 'corolla', 'año': '2020', 'color': 'rojo'}
```

### 💻 Ejemplo 15 (versión alternativa)

```python
for x in auto:
  print(auto[x])
```
📤 **Resultado mostrado:**

```
toyota
corolla
2020
rojo
```

### 💻 Ejemplo 16 (versión alternativa)

```python
it=auto.items()
print(list(it))
```
📤 **Resultado mostrado:**

```
[('marca', 'toyota'), ('modelo', 'corolla'), ('año', '2020'), ('color', 'rojo')]
```

### 💻 Ejemplo 17 (versión alternativa)

```python
d1={"x":1,"y":2}
d2={"y":10,"z":30}
d1.update(d2)
print(d1)
```
📤 **Resultado mostrado:**

```
{'x': 1, 'y': 10, 'z': 30}
```

### 💻 Ejemplo 18 (versión alternativa)

```python
d={"a":100,"b":200,"c":300}
d.pop("b")
print(d)
```
📤 **Resultado mostrado:**

```
{'a': 100, 'c': 300}
```

### 💻 Ejemplo 19 (versión alternativa)

```python
notas={"mate":5,"prog":4,"ingles":3}

K= notas.keys()
print(list(K))
v=notas.values()
print(list(v))
```
📤 **Resultado mostrado:**

```
['mate', 'prog', 'ingles']
[5, 4, 3]
```

### 💻 Ejemplo 20 (versión alternativa)

```python
hijo1 = {"nombre": "ana", "edad": 12}
hijo2 = {"nombre": "pedro", "edad": 15}
familia = {"hijo1": hijo1, "hijo2": hijo2}
print(familia)
```
📤 **Resultado mostrado:**

```
{'hijo1': {'nombre': 'ana', 'edad': 12}, 'hijo2': {'nombre': 'pedro', 'edad': 15}}
```

### 💻 Ejemplo 21 (versión alternativa)

```python
print(hijo2['nombre'])
```
📤 **Resultado mostrado:**

```
pedro
```

### 💻 Ejemplo 22 (versión alternativa)

```python
curso={'nombre':'python', 'duración':'3meses', 'estudiantes':'25'}
print(curso)
```
📤 **Resultado mostrado:**

```
{'nombre': 'python', 'duración': '3meses', 'estudiantes': '25'}
```

### 💻 Ejemplo 23 (versión alternativa)

```python
print(curso['duración'])
```
📤 **Resultado mostrado:**

```
3meses
```

### 💻 Ejemplo 24 (versión alternativa)

```python
curso['estudiantes']=30
print(curso)
```
📤 **Resultado mostrado:**

```
{'nombre': 'python', 'duración': '3meses', 'estudiantes': 30}
```

### 💻 Ejemplo 25 (versión alternativa)

```python
curso['profesor']='carlos'
print(curso)
```
📤 **Resultado mostrado:**

```
{'nombre': 'python', 'duración': '3meses', 'estudiantes': 30, 'profesor': 'carlos'}
```

### 💻 Ejemplo 26 (versión alternativa)

```python
for x in curso:
  print(x)
```
📤 **Resultado mostrado:**

```
nombre
duración
estudiantes
profesor
```

### 💻 Ejemplo 27 (versión alternativa)

```python
for x in curso:
  print(curso[x])
```
📤 **Resultado mostrado:**

```
python
3meses
30
carlos
```

### 💻 Ejemplo 28 (versión alternativa)

```python
for x,y in curso.items():
  print(x,y)
```
📤 **Resultado mostrado:**

```
nombre python
duración 3meses
estudiantes 30
profesor carlos
```

### 💻 Ejemplo 29 (versión alternativa)

```python
d4 = {"id": 1, "ciudad": "Bogotá"}
d5 = {"pais": "Colombia", "id": 2}
d4.update(d5)
print(d4)
```
📤 **Resultado mostrado:**

```
{'id': 2, 'ciudad': 'Bogotá', 'pais': 'Colombia'}
```

### 💻 Ejemplo 30 (versión alternativa)

```python
dictionario= {"nombre":"Laura","edad":22,"carrera":"software"}
dictionario.pop("edad")
print(dictionario)
```
📤 **Resultado mostrado:**

```
{'nombre': 'Laura', 'carrera': 'software'}
```

### 💻 Ejemplo 31 (versión alternativa)

```python
dictionario.popitem()
print(dictionario)
```
📤 **Resultado mostrado:**

```
{'nombre': 'Laura'}
```

### 💻 Ejemplo 32 (versión alternativa)

```python
d={"x":1,"y":2,"z":3}
print(d.get('y'))
```
# Documentación Consolidada de Notebooks

## Set.ipynb

``` python
s= set([5, 4,8,8,1])
print(s) #{1,4,5,6,8}
print(type(s))
```

``` python
s= {5, 4, 6, 8, 8, 1 }
print(s) #{1,4,5,6,8}
print(type(s))
```

``` python
s= set([5, 6, 7, 8 ])
```

``` python
lista = ["peru", "aegentina"]
s= set(["mexico", "españa", lista])
```

``` python
lista = ["peru", "aegentina"]
lista.append("mexico")
lista.append("españa")
print(lista)
```

``` python
s= set([5, 6, 7, 8])
for ss in s:
  print(ss)
```

``` python
s= set([1,2,2,3,4])
print(len(s))
```

``` python
s={"alan","paka","darian", "darian"}
print(len(s))
print(type(s))
```

``` python
s=set(["guitarra", "bajo"])
print("guitarra" in s)
```

``` python
s=set(["guitarra", "bajo"])
print("bateria" in s)
```

``` python
s1=set([1,2,3])
s2=set([3,4,5,])
print(s1 | s2)
```

``` python
l=set([1,2])
l.add(3)
print(l)
```

``` python
s=set ([1,2])
s.remove(2)
print(s)
```

``` python
s=set ([1,2])
s.discard(2)
print(s)
```

``` python
s=set ([1,2])
s.pop()
print(s)
```

``` python
s=set ([1,2])
s.clear()
print(s)
```

``` python
s1={1,2,3}
s2={3,4,5}
print(s1.union(s2))
```

``` python
s1={1,2,3}
s2={3,4,5}
print(s1.intersection(s2))
```

``` python
frontnd = set(["html", "css", "js", "react"])
backnd = set(["python", "sql", "js", "django"])
frontnd.add("vue.js")
backnd.remove("django")
diferencia = frontnd.difference(backnd)
print(frontnd | backnd)
print(frontnd.intersection(backnd))
print(diferencia)



```

------------------------------------------------------------------------

## esto es una tupla (no se puede modificar)s.ipynb

``` python
mi_tupla =(1,2,3,"hola", True) #acepta como una lista cualquier tipo de datos, inmutable sin añadir o eliminar elementos
print(mi_tupla)
```

``` python
t=(1,1,2,3,3,3) # admite valores repetidos
print(t)
```

``` python
#lista
listas =[1,2,3]

#tupla
tupla=(1,2,3)


#en lista se puede modificar
listas[0] =10

#en tupla no se puede
tupla[0] =10

```

``` python
coordenadas =(40.7128, -74.0060) #lat y lon (new york)
# coordenadas [0] =41.0 - esto daria error por que es inmutable
```

``` python
t1=(1,2,3) # con enteros
t2=("a","b","c") #cadenas de texto
t3=(1, "hola", 3.5) # esto es una tupla (no se puede modificar) con tipos mixtos
t4= ()# vacia
t5=(5,)# esto es una tupla (no se puede modificar) con un solo elemento

```

``` python
#acceso por indice

tupla=("python", 2025, True)
print(tupla[0])
print(tupla[1])
print(tupla[-1])
```

``` python
#slicing

tupla =(10,20,30,40,50)
print(tupla[1:4]) # del indice 1 al 3
print(tupla[:3]) # desde el inicio hasta el indice 2
print(tupla[::2]) # saltando de 2 en 2
```

``` python
#itrerar

colores= ("rojo", "verde", "azul")
for color in colores: # recorre acda element de la tupla
    print(color)
```

``` python
#anidadas

t=((1,2), (3,4), (5,6))
print(t[0]) # par acceder  a la primer tupla interna
print(t[0][1]) # accede al segundo elemento de la primer tupla
```

``` python
t1 = (1,2,3)
t2= (4,5,6)
resultado = t1+t2
print(resultado)
```

``` python
t= ("python",) * 3
print(t)
```

``` python
#Pertenencia
t=(10,20,30,40)
print(20 in t) # true si esta enla tupla
print(50 not in t) # true si no esta en la tupla
```

``` python
# desempaquetado
persona=("darian", 22, "colombia")
nombre , edad, pais = persona
print(nombre)
print(edad)
print(pais)
```

``` python
#metodos deisponibles, pocos metodos

t=(1,2,2,3,4)
print(t.count(2)) # cuenta cuantas veces aparee un elemento
print(t.index(3)) # devuelve el indice de la primera aparición
```

``` python
#funciones utiles
t = (5,1,7,3)
print(len(t)) # numero de elementos
print(max(t)) #valor maximo
print(min(t)) #valor minimo
print(sum(t)) #suma de los elementos
print(sorted(t)) # devuelve una nueva lista ordenada
```

``` python
# conversion entre lista y tupla

lista = [1,2,3]
tupla = tuple(lista)
print(tupla)

nueva_lista =list(tupla)
print(nueva_lista)
```

``` python
# usos practicos

personas= ("darian", 22, "colombia")
# acceder a cada atributo usando indices
print("nombre:", personas[0])
print("edad:", personas[1])
print("pais:", personas[2])
```

``` python
#claves en diccionario

coordenadas ={}
punto =(10,20)
coordenadas[punto] = "ubicacion A "
print(coordenadas)
```

``` python
#devolciendo multiples valores

def operaciones(a,b):
  return a+b, a-b, a*b, a/b

suma, resta, multiplicacion, division = operaciones(5,3)
print(suma, resta, multiplicacion, division)
```

``` python
#iteracion

frutas= ("manzana", "pera", "uva")
for i, fruta in enumerate(frutas):
  print(i, fruta)
```

``` python
#intercambio de valores
a,b =10,20
a,b = b,a
print(a,b)
```

``` python
# Ejercicio 1 – Crear una tupla
t = (1, 2, 3, 4, 5)
print(t) # (1, 2, 3, 4, 5)
```

``` python
# Ejercicio 2 – Acceder al tercer elemento
t = (10, 20, 30, 40, 50)
print(t[2]) # 30
```

``` python
# Ejercicio 3 – Tupla con nombre y edad
info = ("Nicolás", 22)
print("Nombre:", info[0], "Edad:", info[1])
```

``` python
# Ejercicio 4 – Concatenar tuplas
t1 = (1, 2, 3)
t2 = (4, 5, 6)
print(t1 + t2) # (1, 2, 3, 4, 5, 6)
```

``` python
# Ejercicio 5 – Repetir una tupla
t = ("Python",) * 3
print(t) # ('Python', 'Python', 'Python')
```

``` python
# Ejercicio 6 – Verificar pertenencia
t = (5, 10, 15, 20, 25)
print(20 in t) # True
```

``` python
# Ejercicio 7 – Desempaquetar tupla
paises = ("Colombia", "México", "Argentina")
a, b, c = paises
print(a, b, c) # Colombia México Argentina
```

``` python
# Ejercicio 8 – Tupla anidada
t = ((1, 2), (3, 4))
print(t[1][1]) # 4
```

``` python
# Ejercicio 9 – Función con suma y producto
def operaciones(a, b):
    return a+b, a*b
print(operaciones(3, 5)) # (8, 15)
```

``` python
# Ejercicio 10 – Intercambio de valores
a, b = 7, 9
a, b = b, a
print(a, b) # 9 7
```

``` python
# Ejercicio 11 – Contar apariciones
t = (2, 4, 6, 2, 8, 2)
print(t.count(2)) # 3
```

``` python
# Ejercicio 12 – Índice de un valor
t = (10, 20, 30, 40, 50)
print(t.index(50)) # 4
```

``` python
# Ejercicio 13 – Funciones integradas
t = (4, 7, 1, 9, 3)
print(max(t)) # 9
print(min(t)) # 1
print(sum(t)) # 24
```

``` python
# Ejercicio 14 – Convertir lista a tupla
lista = [10, 20, 30]
t = tuple(lista)
print(t) # (10, 20, 30)
```

``` python
# Ejercicio 15 – Enumerate con tuplas
colores = ("rojo", "verde", "azul")
for i, color in enumerate(colores):
    print(i, color)
```

------------------------------------------------------------------------

## Untitled0.ipynb

``` python
# Árbol binario representado con listas
# Estructura: [valor, Hijo_izquierdo, Hijo_derecho]

# aquí estamos creando el árbol
#
#     1
#    / \
#   2   3
#  / \
# 4   5

def crear_nodo(valor, izquierdo=None, derecho=None):
    # Función para crear un nodo con valor e hijos opcionales
    return [valor, izquierdo, derecho]

# Construir el árbol de abajo hacia arriba
nodo2 = crear_nodo(2, crear_nodo(4), crear_nodo(5))
nodo3 = crear_nodo(3)
raiz = crear_nodo(1, nodo2, nodo3)

# Función para recorrer el árbol en preorder (raíz, izquierdo, derecho)
def recorrer_preorden(nodo):
    if nodo is None:  # Caso base: nodo vacío
        return
    print(nodo[0], end=" ")  # mostramos en pantalla valor del nodo
    recorrer_preorden(nodo[1])  # Recorrer subárbol izquierdo
    recorrer_preorden(nodo[2])  # Recorrer subárbol derecho

print("Recorrido en preorden:")
recorrer_preorden(raiz)  # Salida: 1 2 4 5 3
```

``` python
# Árbol de expresiones matemáticas con tuplas (inmutables)
# Estructura: (operador, operando_izq, operando_der)
# Representa la expresión: (3 + 5) * (2 - 1)

# aquí estamos creando subexpresión: 3 + 5
suma = ('+', 3, 5)

# aquí estamos creando subexpresión: 2 - 1
resta = ('-', 2, 1)

# Combinar en expresión principal: (3 + 5) * (2 - 1)
expresion = ('*', suma, resta)

# Función para evaluar el árbol de expresiones
def evaluar(nodo):
    # Si el nodo es un número, devolverlo directamente
    if isinstance(nodo, (int, float)):
        return nodo

    # Extraer operador y operandos
    operador, izq, der = nodo
      # Evaluar recursivamente los operandos
    valor_izq = evaluar(izq)
    valor_der = evaluar(der)

    # Aplicar la operación según el operador
    if operador == '+':
        return valor_izq + valor_der
    elif operador == '-':
        return valor_izq - valor_der
    elif operador == '*':
        return valor_izq * valor_der
    elif operador == '/':
        return valor_izq / valor_der

# Evaluar la expresión completa
resultado = evaluar(expresion)
print(f"Resultado de (3 + 5) * (2 - 1) = {resultado}")  # Salida: 8
```

``` python
# Árbol Binario de Búsqueda (BST) con clases
# Los valores menores van a la izquierda, mayores a la derecha

class Nodo:
    # Clase que representa un nodo individual del árbol
    def __init__(self, valor):
        self.valor = valor  # Dato almacenado en el nodo
        self.izquierdo = None  # Referencia al hijo izquierdo
        self.derecho = None  # Referencia al hijo derecho

class ArbolBinarioBusqueda:
    # Clase que representa el árbol completo
    def __init__(self):
        self.raiz = None  # Inicialmente el árbol está vacío

    def insertar(self, valor):
        # Método público para insertar un valor
        if self.raiz is None:
            self.raiz = Nodo(valor)  # Si el árbol está vacío, crear raíz
        else:
            self._insertar_recursivo(self.raiz, valor)  # Insertar recursivamente

    def _insertar_recursivo(self, nodo, valor):
        # Método privado para insertar recursivamente
        if valor < nodo.valor:  # Si es menor, va a la izquierda
            if nodo.izquierdo is None:
                nodo.izquierdo = Nodo(valor)  # aquí estamos creando nuevo nodo
            else:
                self._insertar_recursivo(nodo.izquierdo, valor)  # Seguir buscando
        else:  # Si es mayor o igual, va a la derecha
            if nodo.derecho is None:
                nodo.derecho = Nodo(valor)  # aquí estamos creando nuevo nodo
            else:
                self._insertar_recursivo(nodo.derecho, valor)  # Seguir buscando

    def buscar(self, valor):
        # Buscar un valor en el árbol
        return self._buscar_recursivo(self.raiz, valor)

    def _buscar_recursivo(self, nodo, valor):
        # Método privado para buscar recursivamente
        if nodo is None:
            return False  # No se encontró el valor
        if nodo.valor == valor:
            return True  # Se encontró el valor
        elif valor < nodo.valor:
            return self._buscar_recursivo(nodo.izquierdo, valor)  # Buscar a la izquierda
        else:
            return self._buscar_recursivo(nodo.derecho, valor)  # Buscar a la derecha

    def inorden(self):
        # Recorrido inorden: izquierda-raíz-derecha (muestra valores ordenados)
        resultado = []
        self._inorden_recursivo(self.raiz, resultado)
        return resultado

    def _inorden_recursivo(self, nodo, resultado):
        # Método privado para recorrido inorden
        if nodo:
            self._inorden_recursivo(nodo.izquierdo, resultado)  # Visitar izquierda
            resultado.append(nodo.valor)  # Visitar raíz
            self._inorden_recursivo(nodo.derecho, resultado)  # Visitar derecha

# aquí estamos creando y usar el árbol
arbol = ArbolBinarioBusqueda()
valores = [50, 30, 70, 20, 40, 60, 80]

# Insertar valores en el árbol
for valor in valores:
    arbol.insertar(valor)

# Mostrar valores ordenados
print("Valores en orden:", arbol.inorden())  # [20, 30, 40, 50, 60, 70, 80]

# Buscar valores
print("¿Está el 40?", arbol.buscar(40))  # True
print("¿Está el 100?", arbol.buscar(100))  # False
```

``` python
# Árbol N-ario (cada nodo puede tener múltiples hijos) con diccionarios
# Representa un sistema de archivos

# aquí estamos creando estructura de carpetas y archivos
sistema_archivos = {
    'nombre': 'raiz',  # Nombre del directorio
    'tipo': 'carpeta',  # Tipo de nodo
    'hijos': [  # esta es una lista de hijos (subcarpetas y archivos)
        {
            'nombre': 'documentos',
            'tipo': 'carpeta',
            'hijos': [
                {'nombre': 'trabajo.pdf', 'tipo': 'archivo', 'tamaño': 150},
                {'nombre': 'personal.docx', 'tipo': 'archivo', 'tamaño': 80}
            ]
        },
        {
            'nombre': 'imagenes',
            'tipo': 'carpeta',
            'hijos': [
                {'nombre': 'foto1.jpg', 'tipo': 'archivo', 'tamaño': 200},
                {'nombre': 'foto2.png', 'tipo': 'archivo', 'tamaño': 300}
            ]
        },
        {'nombre': 'readme.txt', 'tipo': 'archivo', 'tamaño': 10}
    ]
}

# Función para mostrar la estructura del árbol con indentación
def mostrar_arbol(nodo, nivel=0):
    # aquí estamos creando indentación según el nivel de profundidad
    indentacion = "  " * nivel

    # Mostrar información del nodo actual
    if nodo['tipo'] == 'carpeta':
        print(f"{indentacion}📁 {nodo['nombre']}/")
    else:
        print(f"{indentacion}📄 {nodo['nombre']} ({nodo['tamaño']} KB)")

    # Recorrer recursivamente los hijos si existen
    if 'hijos' in nodo:
        for hijo in nodo['hijos']:
            mostrar_arbol(hijo, nivel + 1)

# Función para calcular el tamaño total del árbol
def calcular_tamaño(nodo):
    # Si es un archivo, devolver su tamaño
    if nodo['tipo'] == 'archivo':
        return nodo['tamaño']

    # Si es carpeta, sumar el tamaño de todos los hijos
    tamaño_total = 0
    if 'hijos' in nodo:
        for hijo in nodo['hijos']:
            tamaño_total += calcular_tamaño(hijo)

    return tamaño_total

# Mostrar la estructura del sistema de archivos
print("Estructura del sistema de archivos:")
mostrar_arbol(sistema_archivos)

# Calcular y mostrar el tamaño total
tamaño = calcular_tamaño(sistema_archivos)
print(f"\nTamaño total: {tamaño} KB")  # Salida: 740 KB
```

``` python
# Árbol de decisión para clasificar animales usando conjuntos
# Los conjuntos permiten verificaciones rápidas de pertenencia

class NodoDecision:
    # Clase para nodos de decisión con conjuntos de respuestas válidas
    def __init__(self, pregunta, respuestas_validas):
        self.pregunta = pregunta  # Pregunta a realizar
        self.respuestas_validas = set(respuestas_validas)  # Conjunto de respuestas válidas
        self.hijos = {}  # Diccionario: respuesta -> siguiente nodo
        self.resultado = None  # Resultado final si es nodo hoja

    def agregar_hijo(self, respuesta, nodo):
        # Agregar un hijo al árbol de decisión
        if respuesta in self.respuestas_validas:
            self.hijos[respuesta] = nodo
        else:
            print(f"⚠️ Error: '{respuesta}' no es una respuesta válida")

    def es_hoja(self):
        # Verificar si es un nodo hoja (nodo final con resultado)
        return self.resultado is not None

# Construir el árbol de decisión para clasificar animales
# Estructura del árbol:
#                   ¿Tiene pelo?
#                   /         \
#                 Sí          No
#                 /            \
#         ¿Es grande?      ¿Puede volar?
#          /    \            /      \
#        Sí     No         Sí       No
#        |      |          |        |
#      Oso   Gato      Pájaro   Serpiente

# aquí estamos creando nodos hoja (resultados finales)
nodo_oso = NodoDecision("", [])
nodo_oso.resultado = "🐻 Es un oso"

nodo_gato = NodoDecision("", [])
nodo_gato.resultado = "🐱 Es un gato"

nodo_pajaro = NodoDecision("", [])
nodo_pajaro.resultado = "🐦 Es un pájaro"

nodo_serpiente = NodoDecision("", [])
nodo_serpiente.resultado = "🐍 Es una serpiente"

# aquí estamos creando nodos de decisión intermedios
nodo_grande = NodoDecision("¿Es grande?", {'si', 'no'})
nodo_grande.agregar_hijo('si', nodo_oso)
nodo_grande.agregar_hijo('no', nodo_gato)

nodo_volar = NodoDecision("¿Puede volar?", {'si', 'no'})
nodo_volar.agregar_hijo('si', nodo_pajaro)
nodo_volar.agregar_hijo('no', nodo_serpiente)

# aquí estamos creando nodo raíz
raiz = NodoDecision("¿Tiene pelo?", {'si', 'no'})
raiz.agregar_hijo('si', nodo_grande)
raiz.agregar_hijo('no', nodo_volar)

# Función para recorrer el árbol y clasificar
def clasificar(nodo):
    # Si llegamos a un nodo hoja, mostrar resultado
    if nodo.es_hoja():
        print(f"\n🎯 Resultado: {nodo.resultado}")
        return

    # Hacer la pregunta y obtener respuesta
    print(f"\n❓ {nodo.pregunta}")
    print(f"   Respuestas válidas: {', '.join(nodo.respuestas_validas)}")
    respuesta = input("   Tu respuesta: ").lower().strip()

    # Validar respuesta usando el conjunto
    if respuesta not in nodo.respuestas_validas:
        print(f"   ⚠️ Respuesta inválida. Por favor usa: {nodo.respuestas_validas}")
        return clasificar(nodo)  # Volver a preguntar

    # Continuar con el siguiente nodo según la respuesta
    siguiente_nodo = nodo.hijos.get(respuesta)
    if siguiente_nodo:
        clasificar(siguiente_nodo)

# Ejecutar el clasificador
print("=== 🔍 Clasificador de Animales ===")
print("Responde las preguntas para identificar el animal\n")
# clasificar(raiz)  # Descomentar para ejecutar de forma interactiva

# Demostración con respuestas predefinidas
print("Ejemplo 1: Animal con pelo, grande")
print("Resultado esperado: Oso")
```

------------------------------------------------------------------------

## Untitled1.ipynb

``` python
vector1 = []
vector2 = []
vector1=len(input("digite el valor del elemeto"))
vector2=len(input("digite el valor del elemento"))

vector1.len


print(vector1)
print(vector2)

```

------------------------------------------------------------------------

## Untitled7.ipynb

``` python
# Árbol binario representado con listas
# Estructura: [valor, hijo_izquierdo, hijo_derecho]

# aquí estamos creando el árbol
#       1
#      / \
#     2   3
#    / \
#   4   5

def crear_nodo(valor, izquierdo=None, derecho=None):
    # Función para crear un nodo con valor e hijos opcionales
    return [valor, izquierdo, derecho]

# Construir el árbol de abajo hacia arriba
nodo4 = crear_nodo(4)  # Hoja izquierda
nodo5 = crear_nodo(5)  # Hoja derecha
nodo2 = crear_nodo(2, nodo4, nodo5)  # Nodo con dos hijos
nodo3 = crear_nodo(3)  # Hoja derecha de la raíz
raiz = crear_nodo(1, nodo2, nodo3)  # Raíz del árbol
```

``` python
# Función para recorrer el árbol en preorden (raíz-izquierda-derecha)
def recorrer_preorden(nodo):
    if nodo is None:  # Caso base: nodo vacío
        return
    print(nodo[0], end=" ")  # mostramos en pantalla valor del nodo
    recorrer_preorden(nodo[1])  # Recorrer subárbol izquierdo
    recorrer_preorden(nodo[2])  # Recorrer subárbol derecho

print("Recorrido en preorden:")
recorrer_preorden(raiz)  # Salida: 1 2 4 5 3
```

``` python
# Árbol de expresiones matemáticas con tuplas (inmutables)
# Estructura: (operador, operando_izq, operando_der)
# Representa la expresión: (3 + 5) * (2 - 1)

# aquí estamos creando subexpresión: 3 + 5
suma = ('+', 3, 5)

# aquí estamos creando subexpresión: 2 - 1
resta = ('-', 2, 1)

# Combinar en expresión principal: (3 + 5) * (2 - 1)
expresion = ('*', suma, resta)

# Función para evaluar el árbol de expresiones
def evaluar(nodo):
    # Si el nodo es un número, devolverlo directamente
    if isinstance(nodo, (int, float)):
        return nodo

    # Extraer operador y operandos
    operador, izq, der = nodo
```

``` python
 # Evaluar recursivamente los operandos
    valor_izq = evaluar(izq)
    valor_der = evaluar(der)

    # Aplicar la operación según el operador
    if operador == '+':
        return valor_izq + valor_der
    elif operador == '-':
        return valor_izq - valor_der
    elif operador == '*':
        return valor_izq * valor_der
    elif operador == '/':
        return valor_izq / valor_der

# Evaluar la expresión completa
resultado = evaluar(expresion)
print(f"Resultado de (3 + 5) * (2 - 1) = {resultado}")  # Salida: 8
```

``` python
# Árbol Binario de Búsqueda (BST) con clases
# Los valores menores van a la izquierda, mayores a la derecha

class Nodo:
    # Clase que representa un nodo individual del árbol
    def __init__(self, valor):
        self.valor = valor  # Dato almacenado en el nodo
        self.izquierdo = None  # Referencia al hijo izquierdo
        self.derecho = None  # Referencia al hijo derecho

class ArbolBinarioBusqueda:
    # Clase que representa el árbol completo
    def __init__(self):
        self.raiz = None  # Inicialmente el árbol está vacío

    def insertar(self, valor):
        # Método público para insertar un valor
        if self.raiz is None:
            self.raiz = Nodo(valor)  # Si el árbol está vacío, crear raíz
        else:
            self._insertar_recursivo(self.raiz, valor)  # Insertar recursivamente

    def _insertar_recursivo(self, nodo, valor):
        # Método privado para insertar recursivamente
        if valor < nodo.valor:  # Si es menor, va a la izquierda
```

``` python
def _buscar_recursivo(self, nodo, valor):
        # Método privado para buscar recursivamente
        if nodo is None:
            return False  # No se encontró el valor
        if nodo.valor == valor:
            return True  # Se encontró el valor
        elif valor < nodo.valor:
            return self._buscar_recursivo(nodo.izquierdo, valor)  # Buscar a la izquierda
        else:
            return self._buscar_recursivo(nodo.derecho, valor)  # Buscar a la derecha

    def inorden(self):
        # Recorrido inorden: izquierda-raíz-derecha (muestra valores ordenados)
        resultado = []
        self._inorden_recursivo(self.raiz, resultado)
        return resultado
```

``` python
def _inorden_recursivo(self, nodo, resultado):
        # Método privado para recorrido inorden
        if nodo:
            self._inorden_recursivo(nodo.izquierdo, resultado)  # Visitar izquierda
            resultado.append(nodo.valor)  # Visitar raíz
            self._inorden_recursivo(nodo.derecho, resultado)  # Visitar derecha

# aquí estamos creando y usar el árbol
arbol = ArbolBinarioBusqueda()
valores = [50, 30, 70, 20, 40, 60, 80]

# Insertar valores en el árbol
for valor in valores:
    arbol.insertar(valor)

# Mostrar valores ordenados
print("Valores en orden:", arbol.inorden())  # [20, 30, 40, 50, 60, 70, 80]

# Buscar valores
print("¿Está el 40?", arbol.buscar(40))  # True
print("¿Está el 100?", arbol.buscar(100))  # False
```

``` python
# Mostrar la estructura del sistema de archivos
print("Estructura del sistema de archivos:")
mostrar_arbol(sistema_archivos)

# Calcular y mostrar el tamaño total
tamaño = calcular_tamaño(sistema_archivos)
print(f"\nTamaño total: {tamaño} KB")  # Salida: 740 KB
```

------------------------------------------------------------------------

## workclass3.ipynb

``` python
#1
saludo="hola mundo :/"  #se declara la variable
print (saludo) # se imprime el mensaje de la variable
```

``` python
#2
nombre = input("escribe tu nombre:") # se usa input para poder que el usuario escriba por consola
print("hola " + nombre) #se usa el print para enviar la respuesta concatenada con el mensaje
```

``` python
#3
num1 = int(input("Escribe el 1er numero:")) # se declaran las variables
num2 = int(input("Escribe el 2do numero:"))

# se genran las operaciones básicas
suma = num1+num2
resta = num1- num2
multi = num1 * num2
if num2!= 0: # se usa un if para evitar error si el usuario digita 0
  divi = num1 / num2
else:
  divi = "No se puede dividir entre 0"

print("suma", suma )# se inmprime las respuestas
print("resta", resta )
print("multiplicación", multi )
print("division", divi )
```

``` python
#4
hrt = int(input("Escribe el numero de horas trabajadas:")) # se solicita al usuario y se almacena en una variable
pgt =int(input("Escribe el pago por hora"))

#se realiza la operacion para sacar el apago
multi = hrt*pgt
print("el valor que corresponde al pago es", multi) # se imprime el resultado
```

``` python
#5
n =int(input("Escribe un numero entero")) # se solicita el numero para almacenarlo en la variable


#se genera un for para hacer un la suma de losnumeros
for  i in range (1, n+1):
  suma +=i

print(" la suma de los numero del 1 hasta",n , "es", suma)# se imprime el resultado
```

``` python
#6
peso =float(input("Escribe tu peso en kg"))# se solicita al cliente que digite lo valores para ser almacenados
est =float(input("Escribe tu estatura en metros"))

imc = peso / (est ** 2) # se realiza la operación para sacar el resultado  se almacena en otra variable

print("el índice de masa corporal calculado es ", imc) # se imprime el resultado
```

``` python
#7
n = int(input("Escribe el primer numero n"))
m = int(input("Escribe el primer numero m"))# se solicita al cliente que digite lo valores para ser almacenados

cos = n//m# se realiza la operación para sacar el resultado  se almacena en otra variable
res = n%m

print(f"{n} entre {m} da un cosiente {cos} y un resto {res} ")# se imprime el resultado
```

``` python
#8
inver = float(input("Escribe la cantidad a invertir"))# se solicita al cliente que digite lo valores para ser almacenados
inter = float(input("Escribe el interes anual "))
años= int(input("Escribe la cantidad de años "))

cap = inver*(1+inter / 100 )** años # se realiza la operación para sacar el resultado  se almacena en otra variable

print(f"El capital obtenido es {round(cap,2)}"))# se imprime el resultado
```

``` python
#9
clown = int(input("Escribe la cantidad de payasosn vendidos"))# se solicita al cliente que digite lo valores para ser almacenados
doll = int(input("Escribe la cantidad de muñecas vendidos"))

pclown = 112
pdoll = 75

pest= (pclown * clown) + (pdoll * doll)#se realiza la operación para sacar el resultado  se almacena en otra variable

print(f" el peso total del paquete es {pest} gramops")# se imprime el resultado
```

``` python
#11
prebar = 4000
desc =0.60

barranof =int(input(" numero de barras que no son del dia "))

predesc = prebar * (1 - desc)
costt = barranof * predesc

print(f"precio habitual de una barra es ${prebar}")
print(f"descuento aplicado es {int(desc * 100)}%")
print(f"costo total por ${barranof} barras no frescas $ {round(costt, 2)}")
```

``` python
#10
ahor = float(input("introduce la cantidad despositada en la cuenta"))

inter = 0.40

primeraño = ahor * (1+ inter) ** 1
segunaño = ahor * (1+ inter) ** 2
terceraño = ahor * (1+ inter) ** 3

print(f"ahorros tras 1er año {round(primeraño,2)}")
print(f"ahorros tras 2do año {round(segunaño,2)}")
print(f"ahorros tras 3er año {round(terceraño,2)}")
```

``` python
#12
n= int (input(" cuantas palabras deseas agregar en la lista?"))

palabras= []

for i in range(n):
  palabra = input (f"ingrese la palabra {i+1}")
  palabras.append(palabra)

  print("la lista de palabras es:")
  print(palabras)
```

``` python
#13
n= int (input(" cuantas palabras deseas agregar en la lista?"))
palabras= []
for i in range(n):
  palabra = input (f"ingrese la palabra {i+1}")
  palabras.append(palabra)

  print("\nla lista de palabras es:", palabras)

  buscar = input("\n ingrese la palabra que desea buscar")
  contador = palabras.count(buscar)



  print(f"la palabra '{buscar}' apareces {contador} veces en la lista")

```

------------------------------------------------------------------------
# 📚 Compilación de Notebooks

> Este documento integra varios notebooks en un único archivo en formato Markdown, con explicaciones, código y salidas comentadas para mayor claridad.


---
# 📘 Directorios
---

> Este apartado corresponde al notebook **Directorios**, donde se desarrollan ejercicios y ejemplos prácticos.

### 💻 Ejemplo 1 (versión alternativa)

```python
import os
os.mkdir("carperta1")   # creacion de carpetas

print(os.listdir("."))
```

---


---
# 📘 Classwork1
---

> Este apartado corresponde al notebook **Classwork1**, donde se desarrollan ejercicios y ejemplos practicos.

### 💻 Ejemplo 1 (versión alternativa)

```python
a=["nike", "puma", "adidas", "new balance"]
#print(a[0])
#print(a[1])
#print(a[3])
print(a[-2])
```
📤 **Resultado mostrado:**

```
adidas

```
### 💻 Ejemplo 2 (versión alternativa)

```python
edades= [20, 41, 6, 18, 23]

for edad in edades:
  print(edad)

print("___________________")

for i in range(len(edades)):
  print(edades[i])
```
📤 **Resultado mostrado:**

```
20
41
6
18
23
___________________
20
41
6
18
23

```
### 💻 Ejemplo 3 (versión alternativa)

```python
mylist = ["adidas", "futbol", "skate"]
print (mylist)

for item in mylist:
  print(item)
```
📤 **Resultado mostrado:**

```
['adidas', 'futbol', 'skate']
adidas
futbol
skate

```
### 💻 Ejemplo 4 (versión alternativa)

```python
lista=[1,"alan", 2]

listin=list([24, 2, "adidas"])

print(lista)

print(listin)

for item in lista:
  print(item)

for item in listin:
  print(item)
```
### 💻 Ejemplo 5 (versión alternativa)

```python
edades =[20, 41, 6, 18, 23]
edades.append(10)
indice = 0

edades= edades + [16,21,11]
while indice < len(edades):
  print(edades[indice])
  indice += 1
```
📤 **Resultado mostrado:**

```
20
41
6
18
23
10
16
21
11

```

---


---
# 📘 diccionarios
---

> Este apartado corresponde al notebook **diccionarios**, donde se desarrollan ejercicios y ejemplos prácticos.

### 💻 Ejemplo 1 (versión alternativa)

```python
d1 ={
    "nombre": "sara",
    "edad": 27,
    "documento": 10010010
}

print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'sara', 'edad': 27, 'documento': 10010010}

```
### 💻 Ejemplo 2 (versión alternativa)

```python
d1 ={
    "nombre": "alan",
    "edad": 28,
    "documento": 10010010
}

print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'alan', 'edad': 28, 'documento': 10010010}

```
### 💻 Ejemplo 3 (versión alternativa)

```python
d2 = dict({
    ("nombre" ,"alan"),
    ("edad", 28),
    ("documento", 10010010),
})

print(d2)
```
📤 **Resultado mostrado:**

```
{'nombre': 'alan', 'documento': 10010010, 'edad': 28}

```
### 💻 Ejemplo 4 (versión alternativa)

```python
d3=dict(nombre="alan", edad=28, documento=10010010)
print(d3)
```
📤 **Resultado mostrado:**

```
{'nombre': 'alan', 'edad': 28, 'documento': 10010010}

```
### 💻 Ejemplo 5 (versión alternativa)

```python
print(d1['nombre']) #accerder a un elemento del diccionario
print(d1['edad'])
print(d1.get('nombre'))
print(d1.get('edad'))
```
📤 **Resultado mostrado:**

```
alan
28
alan
28

```
### 💻 Ejemplo 6 (versión alternativa)

```python
d1 ['nombre'] = "laura" #editar
print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'laura', 'edad': 28, 'documento': 10010010}

```
### 💻 Ejemplo 7 (versión alternativa)

```python
d1 ['dirección'] = "av sprindfiel cll 123 siempre viva" # agregar elemento
print(d1)
```
📤 **Resultado mostrado:**

```
{'nombre': 'laura', 'edad': 28, 'documento': 10010010, 'dirección': 'av sprindfiel cll 123 siempre viva'}

```
### 💻 Ejemplo 8 (versión alternativa)

```python
for x in d1: #es para iterar
  print(x)# imprime los key del diccionario
```
📤 **Resultado mostrado:**

```
nombre
edad
documento
dirección

```
### 💻 Ejemplo 9 (versión alternativa)

```python
for x in d1: #es para iterar
  print(d1[x])# imprime los valores
```
📤 **Resultado mostrado:**

```
laura
28
10010010
av sprindfiel cll 123 siempre viva

```
### 💻 Ejemplo 10 (versión alternativa)

```python
for x , y in d1.items():# imrimir key y value
  print(x,y)
```
📤 **Resultado mostrado:**

```
nombre laura
edad 28
documento 10010010
dirección av sprindfiel cll 123 siempre viva

```
### 💻 Ejemplo 11 (versión alternativa)

```python
anidado1={'a':1, 'b':2}
anidado2={'a':1, 'b':2}
d={ # el diccionario d contiene el anidado 1 y 2
    "anidado1": anidado1,
    "anidado2": anidado2
}
print(d)
```
📤 **Resultado mostrado:**

```
{'anidado1': {'a': 1, 'b': 2}, 'anidado2': {'a': 1, 'b': 2}}

```
### 💻 Ejemplo 12 (versión alternativa)

```python
# aplicamos el método clear , eliminna todo del diccionario
d={'a':1, 'b':2}
d.clear()
print(d)
```
📤 **Resultado mostrado:**

```
{}

```
### 💻 Ejemplo 13 (versión alternativa)

```python
#get nos permite consultar el valor  de uin key determinado
d={'a':1, 'b':2}
print(d.get('a'))
print(d.get('z', 'no encontrado'))
```
📤 **Resultado mostrado:**

```
1
no encontrado

```
### 💻 Ejemplo 14 (versión alternativa)

```python
# items

  d={'a':1, 'b':2}
  it =d.items()
  print(it)
  print(list(it))
  print(list(it)[0][0])
```
📤 **Resultado mostrado:**

```
dict_items([('a', 1), ('b', 2)])
[('a', 1), ('b', 2)]
a

```
### 💻 Ejemplo 15 (versión alternativa)

```python
#keys
 d={'a':1, 'b':2}
 k=d.keys()
 print(k)
 print(list(k))
```
📤 **Resultado mostrado:**

```
dict_keys(['a', 'b'])
['a', 'b']

```
### 💻 Ejemplo 16 (versión alternativa)

```python
#values
d={'a':1, 'b':2}
print(list(d.values()))
```
📤 **Resultado mostrado:**

```
[1, 2]

```
### 💻 Ejemplo 17 (versión alternativa)

```python
# quitamos un valor con pop, busca y elimina la key
d={'a':1, 'b':2}
d.pop('a')
print(d)
```
📤 **Resultado mostrado:**

```
{'b': 2}

```
### 💻 Ejemplo 18 (versión alternativa)

```python
d={'a':1, 'b':2}
d.pop('c' , -1)
print(d)
```
📤 **Resultado mostrado:**

```
{'a': 1, 'b': 2}

```
### 💻 Ejemplo 19 (versión alternativa)

```python
#pop item elimina de manera aleatoria cualquier elemento
d={'a':1, 'b':2}
d.popitem()
print(d)
```
📤 **Resultado mostrado:**

```
{'a': 1}

```
### 💻 Ejemplo 20 (versión alternativa)

```python
#update actualiza y si no esta lo añade
d1={'a':1, 'b':2}
d2={'a':0, 'd':400}
d1.update(d2)
print(d1)
```
📤 **Resultado mostrado:**

```
{'a': 0, 'b': 2, 'd': 400}

```


---
# 📘 Listas
---

> Este apartado corresponde al notebook **Listas**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
num =[]
num = num + [10, 5, 3]


print(num)
```
📤 **Resultado mostrado:**

```
[10, 5, 3]
```

### 💻 Ejemplo 2 (versión alternativa)

```python
palabras = ["adidas","colombia","argentina", "brasil", "alemania"]

palabras.pop(-2,) #se esta eliminado un elemento de la lista
palabras.pop(2,)

print(palabras)
```
📤 **Resultado mostrado:**

```
['adidas', 'colombia', 'alemania']
```

### 💻 Ejemplo 3 (versión alternativa)

```python
palabras = ["hola", "hello", "ciao", "salute", "hello"]

palabras.remove("hello") #se esta eliminado un elemento de la lista
palabras.remove("hola")

print(palabras)#con esto imprime las palabras o elementos que no fueron eliminados
```
📤 **Resultado mostrado:**

```
['ciao', 'salute', 'hello']
```

### 💻 Ejemplo 4 (versión alternativa)

```python
personas = [
    {"nombre": "Juan", "documento": "12345678"},
    {"nombre": "Ana", "documento": "23456789"},
    {"nombre": "Luis", "documento": "34567890"}
]


for persona in personas:
    print(f"Nombre: {persona['nombre']}, Documento: {persona['documento']}")
```
📤 **Resultado mostrado:**

```
Nombre: Juan, Documento: 12345678
Nombre: Ana, Documento: 23456789
Nombre: Luis, Documento: 34567890
```

### 💻 Ejemplo 5 (versión alternativa)

```python
nombres = []
identificaciones = []
direcciones = []

# Definir el tamaño de las listas
tamaño = 3

# Leemos datos y agregamos a las listas
for i in range(tamaño):
    print(f"Ingrese los datos de la persona {i + 1}")
    nombre = input("Nombre: ")
    identificacion = input("Identificación: ")
    direccion = input("Dirección: ")

    # Agregar a las listas correspondientes
    nombres.append(nombre)  # Aquí se usa la lista "nombres" correctamente
    identificaciones.append(identificacion)  # Usamos "identificaciones"
    direcciones.append(direccion)  # Usamos "direcciones"

# Ahora mostramos las listas
for i in range(tamaño):
    print(f"Mostrando los datos de la persona {i + 1}")
    print("Nombre:", nombres[i])
    print("Identificación:", identificaciones[i])
    print("Dirección:", direcciones[i])
```
📤 **Resultado mostrado:**

```
Ingrese los datos de la persona 1
Nombre: asdasd
Identificación: 12312
Dirección: asdasdas
Ingrese los datos de la persona 2
Nombre: asdasd
Identificación: 123321
Dirección: asdasd2
Ingrese los datos de la persona 3
Nombre: asdas
Identificación: 1445
Dirección: asdasd25
Mostrando los datos de la persona 1
Nombre: asdasd
Identificación: 12312
Dirección: asdasdas
Mostrando los datos de la persona 2
Nombre: asdasd
Identificación: 123321
Dirección: asdasd2
Mostrando los datos de la persona 3
Nombre: asdas
Identificación: 1445
Dirección: asdasd25
```

### 💻 Ejemplo 6 (versión alternativa)

```python
import numpy as np

# esta es una lista con los números correctamente separados por comas
lst = [10, 20, 30, 40, 50]

# Convertir la lista a un arreglo de NumPy
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[10 20 30 40 50]
```

### 💻 Ejemplo 7 (versión alternativa)

```python
import numpy as np

# esta es una lista con los números correctamente separados por comas
lst = ["DARIAN", "PAKA", "LORENA", "BRAYAN"]

# Convertir la lista a un arreglo de NumPy
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
['DARIAN' 'PAKA' 'LORENA' 'BRAYAN']
```

### 💻 Ejemplo 8 (versión alternativa)

```python
import numpy as np

# esta es una lista con los números correctamente separados por comas
lst = ["PERA", "BANANO","MANZANA"]

# Convertir la lista a un arreglo de NumPy
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
['PERA' 'BANANO' 'MANZANA']
```

### 💻 Ejemplo 9 (versión alternativa)

```python
import numpy as np
lst = [[10], [20], [30], [40], [50]]
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[[10]
 [20]
 [30]
 [40]
 [50]]
```

### 💻 Ejemplo 10 (versión alternativa)

```python
import numpy as np
lst = [["ITZZA"], ["NICOLAS"], ["VELANDIA"], ["DANIEL"], ["ARTEAGA"]]
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[['ITZZA']
 ['NICOLAS']
 ['VELANDIA']
 ['DANIEL']
 ['ARTEAGA']]
```

### 💻 Ejemplo 11 (versión alternativa)

```python
import numpy as np
lst = [["PIZZA"], ["SALCHIPAPA"], ["CHORIPERRO"], ["COMBINADO"], ["AGUA DE PANELA"]]
vctr = np.array(lst)

# Mostrar el vector creado
print("Vector creado desde una lista:")
print(vctr)
```
📤 **Resultado mostrado:**

```
Vector creado desde una lista:
[['PIZZA']
 ['SALCHIPAPA']
 ['CHORIPERRO']
 ['COMBINADO']
 ['AGUA DE PANELA']]
```

### 💻 Ejemplo 12 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la suma
vctr_add = vctr1+vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [11 22 33 44 55]
```

### 💻 Ejemplo 13 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50]
lista2=[ 1,2,3,4,5,6 ,7]
# en este caso nos dara sintax error por que el tamaño de las listas es diferente

vctr1 =np.array(lista1)
vctr2 =np.array(lista2)

print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)


vctr_add = vctr1+vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5 6 7]
```

### 💻 Ejemplo 14 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la resta
vctr_add = vctr1-vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [ 9 18 27 36 45]
```

### 💻 Ejemplo 15 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la multiplicación
vctr_add = vctr1*vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [ 10  40  90 160 250]
```

### 💻 Ejemplo 16 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,2,3,4,5]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la divicion
vctr_add = vctr1/vctr2
print("la respues es: " , vctr_add)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 2 3 4 5]
la respues es:  [10. 10. 10. 10. 10.]
```

### 💻 Ejemplo 17 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 1,1,1,1,1]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la operación
vctr_dot = vctr1.dot(vctr2)
print("la respues es: " , vctr_dot)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[1 1 1 1 1]
la respues es:  150
```

### 💻 Ejemplo 18 (versión alternativa)

```python
import numpy as np

lista1 = [10,20,30,40,50] # en este paso definimosn las listas
lista2=[ 2,2,2,2,2]

vctr1 =np.array(lista1)
vctr2 =np.array(lista2) # en este paso definimosn los vectores

#se imprime los valores de cada vector segun las lista
print("vector creado de la lista 1:")
print(vctr1)
print("vector creado de la lista 2:")
print(vctr2)

# se  realiza la operación
vctr_dot = vctr1.dot(vctr2)
print("la respues es: " , vctr_dot)
```
📤 **Resultado mostrado:**

```
vector creado de la lista 1:
[10 20 30 40 50]
vector creado de la lista 2:
[2 2 2 2 2]
la respues es:  300
```




---
# 📘 Numpy
---

> Este apartado corresponde al notebook **Numpy**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
# importar numpy as np
import numpy as np
```

### 💻 Ejemplo 2 (versión alternativa)

```python
# aquí estamos creando lista con numeros primos
import numpy as np

primos = [2, 3, 5, 7, 11, 13, 17, 19, 23, 29] #Variables de numeros primos

primos = np.array(primos)

print(primos)
```
📤 **Resultado mostrado:**

```
[ 2  3  5  7 11 13 17 19 23 29]
```

### 💻 Ejemplo 3 (versión alternativa)

```python
# aquí estamos creando array a partir de lista

import numpy as np
lista = [1, 2, 3, 4, 5]
array = np.array(lista)
print(array)
```
📤 **Resultado mostrado:**

```
[1 2 3 4 5]
```

### 💻 Ejemplo 4 (versión alternativa)

```python
# aquí estamos creando arrays con ceros o cómo inicializar un arreglo de numpy
import numpy as np
array_zeros=np.zeros(10)
array_zeros
```
📤 **Resultado mostrado:**

```
array([0., 0., 0., 0., 0., 0., 0., 0., 0., 0.])
```

### 💻 Ejemplo 5 (versión alternativa)

```python
# aquí estamos creando arrays con números
import numpy as np
array_numeros=np.arange(10)
array_numeros
```
📤 **Resultado mostrado:**

```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```

### 💻 Ejemplo 6 (versión alternativa)

```python
# array con numeros sucesivos
import numpy as np
arrays_impares=np.arange(0,20,2)
arrays_impares
```
📤 **Resultado mostrado:**

```
array([ 0,  2,  4,  6,  8, 10, 12, 14, 16, 18])
```

### 💻 Ejemplo 7 (versión alternativa)

```python
# haciendo un reshape para dos dimensiones
import numpy as np

# aquí estamos creando un array con los primeros 10 números pares
array_pares = np.arange(0, 20, 2)  # [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]

# Cambiar su forma a 2 filas y 5 columnas
array_reshape = array_pares.reshape(2, 5)

print(array_reshape)
```
📤 **Resultado mostrado:**

```
[[ 0  2  4  6  8]
 [10 12 14 16 18]]
```

### 💻 Ejemplo 8 (versión alternativa)

```python
# operaciones aritmeticas sobre np array 1-dimension y 2-dimension
array_impares=array_pares +1
array_impares
```
📤 **Resultado mostrado:**

```
array([ 1,  3,  5,  7,  9, 11, 13, 15, 17, 19])
```

### 💻 Ejemplo 9 (versión alternativa)

```python
# multiplicar por 100
array_impares *100
```
📤 **Resultado mostrado:**

```
array([ 100,  300,  500,  700,  900, 1100, 1300, 1500, 1700, 1900])
```

### 💻 Ejemplo 10 (versión alternativa)

```python
# resta entre arrays
array_impares - array_pares
```
📤 **Resultado mostrado:**

```
array([1, 1, 1, 1, 1, 1, 1, 1, 1, 1])
```

### 💻 Ejemplo 11 (versión alternativa)

```python
# cuidado con la división entre cero
array_impares/array_pares
```
📤 **Resultado mostrado:**

```
/tmp/ipython-input-4036163409.py:2: RuntimeWarning: divide by zero encountered in divide
  array_impares/array_pares
array([       inf, 1.5       , 1.25      , 1.16666667, 1.125     ,
       1.1       , 1.08333333, 1.07142857, 1.0625    , 1.05555556])
```

### 💻 Ejemplo 12 (versión alternativa)

```python
# métodos asociados a estadística
# suma

array_pares.sum()
```
📤 **Resultado mostrado:**

```
np.int64(90)
```

### 💻 Ejemplo 13 (versión alternativa)

```python
# promedio
array_pares.mean()
```
📤 **Resultado mostrado:**

```
np.float64(9.0)
```

### 💻 Ejemplo 14 (versión alternativa)

```python
# varianza
array_pares.var()
```
📤 **Resultado mostrado:**

```
np.float64(33.0)
```

### 💻 Ejemplo 15 (versión alternativa)

```python
# como ordenar un np array
array_fibonacci=np.array([55, 0, 144, 1, 21, 89, 5, 8, 13, 1, 34, 3, 2])
array_fibonacci
```
📤 **Resultado mostrado:**

```
array([ 55,   0, 144,   1,  21,  89,   5,   8,  13,   1,  34,   3,   2])
```

### 💻 Ejemplo 16 (versión alternativa)

```python
# orden ascendente: de menor a mayor
np.sort(array_fibonacci)
```
📤 **Resultado mostrado:**

```
array([  0,   1,   1,   2,   3,   5,   8,  13,  21,  34,  55,  89, 144])
```

### 💻 Ejemplo 17 (versión alternativa)

```python
# orden descendente: de mayor a menor
-np.sort(-array_fibonacci)
```
📤 **Resultado mostrado:**

```
array([144,  89,  55,  34,  21,  13,   8,   5,   3,   2,   1,   1,   0])
```

### 💻 Ejemplo 18 (versión alternativa)

```python
# Como seleccionar elements
```

### 💻 Ejemplo 19 (versión alternativa)

```python
# Seleccionar un elemento
```

### 💻 Ejemplo 20 (versión alternativa)

```python
A = np.arange(0,20,2).reshape(2,5)
A
```
📤 **Resultado mostrado:**

```
array([[ 0,  2,  4,  6,  8],
       [10, 12, 14, 16, 18]])
```

### 💻 Ejemplo 21 (versión alternativa)

```python
# seleccionar el primer elemento
A[0,0]
```
📤 **Resultado mostrado:**

```
np.int64(0)
```

### 💻 Ejemplo 22 (versión alternativa)

```python
# seleccionar algún otro elemento
A[1,3]
```
📤 **Resultado mostrado:**

```
np.int64(16)
```

### 💻 Ejemplo 23 (versión alternativa)

```python
# Seleccionar varios elementos
```

### 💻 Ejemplo 24 (versión alternativa)

```python
# seleccionar por fila
A[1:]
```
📤 **Resultado mostrado:**

```
array([[10, 12, 14, 16, 18]])
```

### 💻 Ejemplo 25 (versión alternativa)

```python
# seleccionar por columna
A[:,3]
```
📤 **Resultado mostrado:**

```
array([ 6, 16])
```

### 💻 Ejemplo 26 (versión alternativa)

```python
# Utilizar filter
```

### 💻 Ejemplo 27 (versión alternativa)

```python

```

### 💻 Ejemplo 28 (versión alternativa)

```python
# conidicion para menores de 20
```

### 💻 Ejemplo 29 (versión alternativa)

```python
# filtrar menores de 20
```

### 💻 Ejemplo 30 (versión alternativa)

```python

```

# 📂 Ejercicios de Manejo de Archivos y Directorios en Python

Este conjunto de ejercicios muestra cómo trabajar con archivos y directorios en Python utilizando los módulos **os**, **pathlib** y **shutil**.  

---

## 🔹 Ejercicio 1
**Crear una carpeta con `os`**
```python
import os
os.mkdir("nueva_carpeta")
print(os.listdir("."))
```
👉 Se crea una carpeta llamada **`nueva_carpeta`** y luego se listan los elementos en el directorio actual.

---

## 🔹 Ejercicio 2
**Crear una carpeta con `pathlib`**
```python
from pathlib import Path
Path("nueva_carpeta1").mkdir()
print(list(Path(".").iterdir()))
```
👉 Se crea la carpeta **`nueva_carpeta1`** y se muestran los elementos del directorio actual.

---

## 🔹 Ejercicio 7
**Crear un archivo de texto con `os`**
```python
import os
with open("nuevo.txt", "w") as f:
    f.write("Hola mundo")
```
👉 Se genera el archivo **`nuevo.txt`** con el contenido:  
```
Hola mundo
```

---

## 🔹 Ejercicio 8
**Crear un archivo de texto con `pathlib`**
```python
from pathlib import Path
Path("nuevo1txt").write_text("Hola mundo")
```
👉 Se crea el archivo **`nuevo1txt`** (nota: le falta el punto en la extensión) con el texto:  
```
Hola mundo
```

---

## 🔹 Ejercicio 27
**Crear subdirectorios con `os`**
```python
import os
os.makedirs("carpeta1/carpeta2/carpeta3", exist_ok=True)
```
👉 Se construye una estructura anidada de carpetas:  
```
carpeta1/
 └── carpeta2/
      └── carpeta3/
```

---

## 🔹 Ejercicio 28
**Crear subdirectorios con `pathlib`**
```python
from pathlib import Path
Path("carpeta1.0/carpeta2.0/carpeta3.0").mkdir(parents=True, exist_ok=True)
```
👉 Se genera la estructura de carpetas anidadas:  
```
carpeta1.0/
 └── carpeta2.0/
      └── carpeta3.0/
```

---

## 🔹 Ejercicio 29
**Eliminar directorios con `os` y `shutil`**
```python
import os
import shutil
shutil.rmtree("carpeta1")
```
👉 Se elimina de forma recursiva la carpeta **`carpeta1`** y su contenido.

---

## 🔹 Ejercicio 30
**Eliminar directorios con `pathlib` y `shutil`**
```python
from pathlib import Path
import shutil
shutil.rmtree(Path("carpeta1.0"))
```
👉 Se elimina recursivamente la carpeta **`carpeta1.0`** y todo su contenido.

---

# ✅ Conclusión
Estos ejercicios muestran la diferencia entre el uso de **`os`** y **`pathlib`** para operaciones comunes de manejo de archivos y directorios en Python, así como la utilidad de **`shutil`** para la eliminación recursiva de carpetas.

# Ejercicios de Manejo de Archivos y Directorios en Python

Este conjunto de scripts demuestra el uso de los módulos **`os`** y **`pathlib`** en Python para realizar operaciones básicas sobre archivos y directorios.

---

## 📂 Listar Archivos y Directorios

### `ejercicio5.py`
```python
import os
print(os.listdir('.'))
```
➡️ Lista los archivos y carpetas del directorio actual utilizando **`os.listdir()`**.

### `ejercicio6.py`
```python
from pathlib import Path
for f in Path('.').iterdir():
    print(f)
```
➡️ Lista los archivos y carpetas del directorio actual usando **`pathlib.Path.iterdir()`**.

---

## 📝 Escritura de Archivos

### `ejercicio19.py`
```python
import os
with open("nuevo.txt", "w") as f:
    f.write("hello world")
```
➡️ Crea (o sobrescribe) el archivo **`nuevo.txt`** y escribe *"hello world"* en él.

### `ejercicio20.py`
```python
from pathlib import Path
Path("nuevo1.txt").write_text("Darian")
```
➡️ Crea (o sobrescribe) el archivo **`nuevo1.txt`** con el texto *"Darian"* utilizando **`pathlib`**.

---

## 📖 Lectura de Archivos

### `ejercicio17.py`
```python
import os
with open("nuevo.txt", "r") as f:
    print(f.read())
```
➡️ Abre el archivo **`nuevo.txt`** y muestra su contenido en consola.

### `ejercicio18.py`
```python
from pathlib import Path
print(Path("nuevo1.txt").read_text())
```
➡️ Lee y muestra el contenido del archivo **`nuevo1.txt`** mediante **`pathlib`**.

---

## 🗑️ Eliminación de Archivos

### `ejercicio11.py`
```python
import os
os.remove("nuevo.txt")
```
➡️ Elimina el archivo **`nuevo.txt`** si existe.

### `ejercicio12.py`
```python
from pathlib import Path
Path("nuevo1.txt").unlink()
```
➡️ Elimina el archivo **`nuevo1.txt`** con **`pathlib`**.

---

## 🗂️ Eliminación de Directorios

### `ejercicio13.py`
```python
import os
os.rmdir("nueva_carpeta")
```
➡️ Elimina la carpeta **`nueva_carpeta`** (si está vacía).

### `ejercicio14.py`
```python
from pathlib import Path
Path("nueva_carpeta1").rmdir()
```
➡️ Elimina la carpeta **`nueva_carpeta1`** usando **`pathlib`**.

---

## 📌 Resumen

- **`os`** → ofrece funciones clásicas del sistema operativo para manejar archivos y directorios.  
- **`pathlib`** → proporciona una interfaz más moderna y orientada a objetos.  
- Ambos permiten realizar operaciones similares: crear, leer, escribir, listar y eliminar archivos o directorios.

# Ejercicios de Manejo de Archivos y Directorios en Python

Este conjunto de scripts muestra ejemplos prácticos del uso de los módulos **`os`** y **`pathlib`** en Python para manipular archivos y carpetas.

---

## 📂 Listar Archivos y Directorios

- **`ejercicio33.py`** (con `os`)
  ```python
  import os
  print(os.listdir("."))           # esta es una listar lo que hay en la carpeta actual
  print(os.listdir("carpeta1"))    # esta es una listar lo que hay en una carpeta específica
  ```

- **`ejercicio34.py`** (con `pathlib`)
  ```python
  from pathlib import Path
  print(list(Path(".").iterdir()))          # esta es una listar lo que hay en la carpeta actual
  print(list(Path("carpeta1.0").iterdir())) # esta es una listar lo que hay en una carpeta específica
  ```

---

## 🔄 Renombrar y Mover Carpetas

- **`carpeta31.py`** (con `os`)
  ```python
  import os
  os.rename("carpeta1", "carpeta_renombrada")                     # Renombrar carpeta
  os.rename("carpeta_renombrada", "otra_carpeta/carpeta_renombrada") # Mover carpeta
  ```

- **`carpeta32.py`** (con `pathlib`)
  ```python
  from pathlib import Path
  Path("carpeta1.0").rename("carpeta_renombrada1.0")                        # Renombrar carpeta
  Path("carpeta_renombrada1.0").rename("otra_carpeta1/carpeta_renombrada1.0") # Mover carpeta
  ```

---

## 📍 Rutas Absolutas

- **`ejercicio21.py`** (con `os`)
  ```python
  import os
  print(os.path.abspath("nuevo.txt"))   # Obtener ruta absoluta
  ```

- **`ejercicio22.py`** (con `pathlib`)
  ```python
  from pathlib import Path
  print(Path("nuevo1.txt").absolute())  # Obtener ruta absoluta
  ```

---

## ✏️ Renombrar Archivos

- **`ejercicio15.py`** (con `os`)
  ```python
  import os
  os.rename("nuevo.txt", "renombrado.txt")   # Renombrar archivo
  ```

- **`ejercicio16.py`** (con `pathlib`)
  ```python
  from pathlib import Path
  Path("nuevo1.txt").rename("renombrado1.txt")  # Renombrar archivo
  ```

---

## ✅ Verificar Existencia de Archivos

- **`ejercicio9.py`** (con `os`)
  ```python
  import os
  print(os.path.exists("nuevo.txt"))    # Verificar si existe
  print(os.path.exists("archivo.txt"))
  ```

- **`ejercicio10.py`** (con `pathlib`)
  ```python
  from pathlib import Path
  print(Path("archivo.txt").exists())   # Verificar si existe
  print(Path("nuevo.txt").exists())
  ```

---

## 📌 Conclusión

- **`os`** → Más tradicional, se usa ampliamente pero menos orientado a objetos.  
- **`pathlib`** → Introducido en Python 3.4, ofrece una sintaxis más limpia y orientada a objetos para trabajar con rutas y archivos.  

Este conjunto de ejercicios permite comparar ambas formas de realizar operaciones comunes en el sistema de archivos.


---




---
# 📘 Pilas
---

> Este apartado corresponde al notebook **Pilas**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
pila =[]
# push
pila.append("a")
pila.append("b")
pila.append("c")
print(pila)
```
📤 **Resultado mostrado:**

```
['a', 'b', 'c']
```

### 💻 Ejemplo 2 (versión alternativa)

```python
pila =['a', 'b', 'c']
elenemto=pila.pop()
print(pila)
```
📤 **Resultado mostrado:**

```
['a', 'b']
```

### 💻 Ejemplo 3 (versión alternativa)

```python
pila =['a', 'b', 'c']

cima= pila[-1]
print(pila)
print(cima)
```
📤 **Resultado mostrado:**

```
['a', 'b', 'c']
c
```

### 💻 Ejemplo 4 (versión alternativa)

```python
pila =[]
if not pila:
  print("vacia")
else:
  print("con elementos")
```
📤 **Resultado mostrado:**

```
vacia
```

### 💻 Ejemplo 5 (versión alternativa)

```python
pila=[10,20,30,40]
tamaño=len(pila)
print(f"tamaño: {tamaño}")
```
📤 **Resultado mostrado:**

```
tamaño: 4
```

### 💻 Ejemplo 6 (versión alternativa)

```python
def invertir_palabra(palabra):
  pila = [ ]

  for letra in palabra:
    pila.append(letra)

  invertida = ""
  while pila:
      invertida+=pila.pop()

  return invertida

print(invertir_palabra("python"))
```
📤 **Resultado mostrado:**

```
nohtyp
```

### 💻 Ejemplo 7 (versión alternativa)

```python
# cambiar un decimal a binario
def decimal_a_binario(n):
    pila=[]
    while n>0:
      pila.append(n%2)
      n //= 2
    binario =""
    while pila:
        binario += str(pila.pop())
    return binario

print(decimal_a_binario(25))
```
📤 **Resultado mostrado:**

```
11001
```

### 💻 Ejemplo 8 (versión alternativa)

```python

```




---
# 📘 Ejercicios Parcial 1
---

> Este apartado corresponde al notebook **Ejercicios Parcial 1**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
usuarios_registrados = ["ana_dev", "luis_ux", "carlos_pm"]

usuarios_unicos =set(usuarios_registrados)

nuevos_usuarios = input("👉 Ingresa tu nombre de usuario: ")


if nuevos_usuarios in usuarios_unicos:
  print(f"el usuario {nuevos_usuarios} ya esta registrado")

else :
    usuarios_registrados.append(nuevos_usuarios)
    usuarios_unicos.add(nuevos_usuarios)

    print("lista de usuarios registrados ")
    print(usuarios_registrados)
    print("\n lista de usuarios unicos")
    print(usuarios_unicos)
```
📤 **Resultado mostrado:**

```
👉 Ingresa tu nombre de usuario: luis_ux
el usuario luis_ux ya esta registrado
```

### 💻 Ejemplo 2 (versión alternativa)

```python
ventas_precios = [15.50 , 20.00, 5.75 , 15.50, 30.00]
productos_vendidos= ["cafe", "torta", "galleta", "cafe", "almuezo"]

ingresos_totales = sum(ventas_precios)
productos_unicos = set(productos_vendidos)

print(f" los ingresos toales son {ingresos_totales}")
print(f" la cantidad de productos unicos es de {len(productos_unicos)}")
```
📤 **Resultado mostrado:**

```
los ingresos toales son 86.75
 la cantidad de productos unicos es de 4
```

### 💻 Ejemplo 3 (versión alternativa)

```python
tareas=["enviar reporte", "revisar correos"]
nueva_tarea="llamar al cliente"
tareas.append(nueva_tarea)

print(f" la lista actualizada de las tareas:\n {tareas}")
tareas[0]= "enviar reporte(completado)"
print(f"lista final de tareas: \n{tareas}")
```
📤 **Resultado mostrado:**

```
la lista actualizada de las tareas:
 ['enviar reporte', 'revisar correos', 'llamar al cliente']
lista final de tareas: 
['enviar reporte(completado)', 'revisar correos', 'llamar al cliente']
```

### 💻 Ejemplo 4 (versión alternativa)

```python
asistentes_ingresados = {"id_1122","id_3344"}
persona_llegando ="id_5566"

persona_consola= input("ingrese su id")
if persona_llegando in asistentes_ingresados:
  print(f"su id {persona_llegando} ya esta registrado, lo siento")

else:
  asistentes_ingresados.add(persona_llegando)
  asistentes_ingresados.add(persona_consola)

  print(f" lista final de asistentes ingresados  es: \n {asistentes_ingresados}")
```
📤 **Resultado mostrado:**

```
ingrese su idid_232323
 lista final de asistentes ingresados  es: 
 {'id_3344', 'id_5566', 'id_1122', 'id_232323'}
```




---
# 📘 Ejercicios Pre-Parcial
---

> Este apartado corresponde al notebook **Ejercicios Pre-Parcial**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
# 1
usuarios_registrados = ["ana_dev", "luis_ux", "carlos_pm"]

usuarios_unicos = set(usuarios_registrados)# Creamos un set para verificación rápida
nuevo_usuario = "luis_ux"# Llegada de un nuevo usuario

if nuevo_usuario in usuarios_unicos:
    print(f"El usuario '{nuevo_usuario}' ya existe.")
else:
    usuarios_registrados.append(nuevo_usuario)
    usuarios_unicos.add(nuevo_usuario)


nuevo_usuario = "sofia_qa"# Repetimos con otro usuario

if nuevo_usuario in usuarios_unicos:
    print(f"El usuario '{nuevo_usuario}' ya existe.")
else:
    usuarios_registrados.append(nuevo_usuario)
    usuarios_unicos.add(nuevo_usuario)

#  resultados
print("Lista final de usuarios registrados (ordenada)",usuarios_registrados)
print("Conjunto de usuarios únicos",usuarios_unicos)
```
📤 **Resultado mostrado:**

```
El usuario 'luis_ux' ya existe.
Lista final de usuarios registrados (ordenada) ['ana_dev', 'luis_ux', 'carlos_pm', 'sofia_qa']
Conjunto de usuarios únicos {'ana_dev', 'sofia_qa', 'carlos_pm', 'luis_ux'}
```

### 💻 Ejemplo 2 (versión alternativa)

```python
# 2

ventas_precios = [15.50, 20.00, 5.75, 15.50, 30.00]
productos_vendidos = ["cafe", "torta", "galleta", "cafe", "almuerzo"]

ingresos_totales = sum(ventas_precios)#Calcular total de ingresos a partir del metodo sum

productos_unicos = set(productos_vendidos)#Crear un conjunto para obtener productos únicos

# resultados
print(f"Ingresos totales del día: ${ingresos_totales:.2f}")
print(f"Número de productos únicos vendidos: {len(productos_unicos)}")
print(f"Productos únicos: {productos_unicos}")
```
📤 **Resultado mostrado:**

```
Ingresos totales del día: $86.75
Número de productos únicos vendidos: 4
Productos únicos: {'torta', 'almuerzo', 'galleta', 'cafe'}
```

### 💻 Ejemplo 3 (versión alternativa)

```python
# 3
tareas = ["Enviar reporte", "Revisar correos"]

nueva_tarea = "Llamar al cliente"#  se añade nueva tarea
tareas.append(nueva_tarea)
print("Lista de tareas actualizada:")# Mostramos lalista actualizada
print(tareas)

tareas[0] = tareas[0] + " (Completada)"# marcamos la primera tarea como completada

# esta es una lista final
print("Lista final de tareas:")
print(tareas)
```

### 💻 Ejemplo 4 (versión alternativa)

```python
#4
asistentes_ingresados = ["ID_1122", "ID_3344"]

asistentes_ingresados.append("ID_5566")# Persona que llega


persona_llegando = input("Ingresa el ID de la persona que llega: ")# en este paso definimos un input para solicitar el numero de id que va a ingresarar
if persona_llegando in asistentes_ingresados:# en este paso definimos un if para la condicion, si ya ingreso o si es un id nuevo ingreso
    print("Ya has ingresado.")
else:
    asistentes_ingresados.add(persona_llegando)
    print("Bienvenido")

print("Asistentes finales:", asistentes_ingresados)# se imprimen las lista con los id ingresados unicos
```
📤 **Resultado mostrado:**

```
Ingresa el ID de la persona que llega: ID_1122
Ya has ingresado.
Asistentes finales: ['ID_1122', 'ID_3344', 'ID_5566']
```

### 💻 Ejemplo 5 (versión alternativa)

```python
#5
calificaciones = [3.5, 4.0, 5.0, 2.5, 3.5, 4.0, 4.8]
promedio = sum(calificaciones) / len(calificaciones)# se realiza el promedio de las calificacion con la suma de ellas y saando al longitud de ellas (sum / len)
notas_unicas = set(calificaciones) # en este paso definimos el set de las notas unicas, esto sacara los duplicados cuando se imprima

print(f"Promedio: {promedio:.2f}")# el .2 es para darle . 2 decimales al resultado

print("Notas únicas:", notas_unicas)
```
📤 **Resultado mostrado:**

```
Promedio: 3.90
Notas únicas: {2.5, 3.5, 4.8, 4.0, 5.0}
```

### 💻 Ejemplo 6 (versión alternativa)

```python
#6
tallas_disponibles = ["S", "M", "L", "M"]# esta es una lista de tallas que tenemos (hay repetidas)
tallas_unicas = set(tallas_disponibles)# convertir la lista en conjunto para que no se repitan

nueva_talla = "XL"# llega una nueva talla y la metemos al conjunto
tallas_unicas.add(nueva_talla)

tallas_unicas.add("S")# probamos a meter otra vez la "S" (pero no se repite en conjuntos)

# mostramos cómo quedó el conjunto
print("Tallas únicas disponibles:", tallas_unicas)
```

### 💻 Ejemplo 7 (versión alternativa)

```python
#7
mis_sugerencias = ["París", "Roma", "Berlín"]# mis destinos sugeridos
sugerencias_amigo = ["Londres", "Roma", "Praga"]# lo que sugirió mi amigo

set_mis_sugerencias = set(mis_sugerencias)# paso 1: convertir las listas en conjuntos (así quitamos repetidos)
set_sugerencias_amigo = set(sugerencias_amigo)

destinos_finales = set_mis_sugerencias.union(set_sugerencias_amigo)# paso 2: unir los dos conjuntos para tener todos los destinos sin repetir

# paso 3: mostrar cómo quedó la lista final
print("Destinos finales únicos:", destinos_finales)
print("Cantidad total de destinos únicos:", len(destinos_finales))
```

### 💻 Ejemplo 8 (versión alternativa)

```python
# Caso 8: Análisis de Encuesta

respuestas = [5, 4, 3, 5, 5, 2, 4, 5, 1, 5]# esta es una lista con las respuestas de la encuesta (del 1 = muy insatisfecho, al 5 = muy satisfecho)


contador_max_satisfaccion = 0 # Variable para contar cuántas personas respondieron "5" (muy satisfecho)


for r in respuestas:# Recorremos la lista de respuestas
    if r == 5:  # Si la respuesta es 5, aumentamos el contador
        contador_max_satisfaccion += 1


respuestas_unicas = set(respuestas)# Usamos un conjunto (set) para ver solo las respuestas únicas que aparecieron

# Mostramos los resultados
print("Opciones únicas de respuesta en la encuesta:", respuestas_unicas)
print("Total de personas 'muy satisfechas' (5):", contador_max_satisfaccion)
```
📤 **Resultado mostrado:**

```
Opciones únicas de respuesta en la encuesta: {1, 2, 3, 4, 5}
Total de personas 'muy satisfechas' (5): 5
```

### 💻 Ejemplo 9 (versión alternativa)

```python
# Caso 9: Gestión de Ingredientes para una Receta
ingredientes_masa = ["harina", "mantequilla", "agua", "sal"]# esta es una lista de ingredientes para la masa
ingredientes_relleno = ["queso", "espinaca", "huevo", "sal"]# esta es una lista de ingredientes para el relleno


ingredientes_totales = ingredientes_masa + ingredientes_relleno #Combinamos ambas listas en una sola
ingredientes_unicos = set(ingredientes_totales)# usamos un conjunto (set) para eliminar duplicados
lista_compras_final = list(ingredientes_unicos)#Convertimos el set de nuevo a lista (opcional, para que se vea como lista)

# Mostramos el resultado
print("Lista de compras final (sin duplicados):", lista_compras_final)
```
📤 **Resultado mostrado:**

```
Lista de compras final (sin duplicados): ['espinaca', 'mantequilla', 'huevo', 'harina', 'sal', 'agua', 'queso']
```

### 💻 Ejemplo 10 (versión alternativa)

```python
# Caso 10: Filtrado de Correo Electrónico

spam_emails = {"spam1@example.com", "ofertas@mal.com", "dudoso@mail.net"}# Conjunto con los correos que están en la lista negra (spam)

correo_entrante = "usuario.normal@email.com" #Creamos una variable con un correo entrante (caso 1)
log_verificaciones = [] # esta es una lista para registrar los correos verificados

if correo_entrante in spam_emails: #Verificamos si el primer correo está en la lista de spam
    print("Alerta de SPAM:", correo_entrante)
else:
    print("Correo seguro:", correo_entrante)


log_verificaciones.append(correo_entrante)# Agregamos al log


correo_entrante = "ofertas@mal.com"  # Repetimos el proceso con otro correo (caso 2)

if correo_entrante in spam_emails:
    print("Alerta de SPAM:", correo_entrante)
else:
    print("Correo seguro:", correo_entrante)

log_verificaciones.append(correo_entrante)

# Mostramos el log de correos verificados
print("Registro de correos verificados:", log_verificaciones)
```
📤 **Resultado mostrado:**

```
Correo seguro: usuario.normal@email.com
Alerta de SPAM: ofertas@mal.com
Registro de correos verificados: ['usuario.normal@email.com', 'ofertas@mal.com']
```

### 💻 Ejemplo 11 (versión alternativa)

```python
# Integrantes jaja
integrantes = ["david Ballesteros", "Juan Castillo", " Mateo Franco", "Alan Melo Giraldo"]
print(integrantes)
```
📤 **Resultado mostrado:**

```
['david Ballesteros', 'Juan Castillo', ' Mateo Franco', 'Alan Melo Giraldo']
```

### 💻 Ejemplo 12 (versión alternativa)

```python

```
📤 **Resultado mostrado:**

```
sumar vector1 vector2
```

### 💻 Ejemplo 13 (versión alternativa)

```python
import numpy as np

# aquí estamos creando dos vectores
vector1 = np.array([1, 2, 3])
vector2 = np.array([4, 5, 6])

# Calcular el producto punto
producto_punto = np.dot(vector1, vector2)

# mostramos en pantalla el resultado
print(f"Vector 1: {vector1}")
print(f"Vector 2: {vector2}")
print(f"El producto punto es: {producto_punto}")
```
📤 **Resultado mostrado:**

```
Vector 1: [1 2 3]
Vector 2: [4 5 6]
El producto punto es: 32
```




---
# 📘 Ejercicios Pre-Parcial 2
---

> Este apartado corresponde al notebook **Ejercicios Pre-Parcial 2**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
#1
compras= ["leche", "pan"]
compras.append("huevos")# con append se agrega a la lista
print(compras)
```
📤 **Resultado mostrado:**

```
['leche', 'pan', 'huevos']
```

### 💻 Ejemplo 2 (versión alternativa)

```python
#2
perfil_usuario = {
    "nombre": input("Introduce el nombre del usuario: "),
    "edad": int(input("Introduce la edad del usuario: "))}

nueva_edad = int(input("Introduce la nueva edad del usuario: "))# Actualizar la edad del usuario
perfil_usuario["edad"] = nueva_edad
perfil_usuario["ciudad"] = input("Introduce la ciudad del usuario: ")# Añadir la clave "ciudad"
print(perfil_usuario)
```
📤 **Resultado mostrado:**

```
Introduce el nombre del usuario: alan
Introduce la edad del usuario: 78
Introduce la nueva edad del usuario: 98
Introduce la ciudad del usuario: bogota
{'nombre': 'alan', 'edad': 98, 'ciudad': 'bogota'}
```

### 💻 Ejemplo 3 (versión alternativa)

```python
#3
coordenadas =(40.7128, -74.0060) # creamos la tupla
lat , long = coordenadas # lo desempaquetamos
print(lat, long)# se imprime
```
📤 **Resultado mostrado:**

```
40.7128 -74.006
```

### 💻 Ejemplo 4 (versión alternativa)

```python
#4
temperaturas = [22.5, 24.0, 21.8, 25.1, 23.9, 22.7, 21.5]
prom= sum(temperaturas)/len(temperaturas) # se genera una variable para el promedio donde lleva la suma de las temperaturas y la longitud de ellas
print(prom)
```
📤 **Resultado mostrado:**

```
23.071428571428573
```

### 💻 Ejemplo 5 (versión alternativa)

```python
#5
diccionario ={'hi':'hola','tomorrow':'mañana','yesterday':'ayer','yellow':'amarillo','smart':'inteligente', 'goodbye':'adios','thanks':'gracias','sorry':'lo siento'}


busqueda=input("digite la palabra que desea buscar en ingles").lower()# se realiza un imput para solicitar la palabra al ususario

if busqueda in diccionario:# en este paso definimos un if para la condicion, en este caso con un .get para buscar la pabara y verificar si se encuentra
    print(diccionario.get(busqueda))
else:
    print("la palabra no se encuentra en el diccionario")
```
📤 **Resultado mostrado:**

```
digite la palabra que desea buscar en inglesplease
la palabra no se encuentra en el diccionario
```

### 💻 Ejemplo 6 (versión alternativa)

```python
#6
horario=(('matematicas','08:00am'),('fisica','10:00am'),('historia','12:00pm'))

#recorremoe el horarioy lo imprimimos cada clase
print('horariodeclases es:')
for materia, hora in horario:
  print(f"{materia} - {hora}")
```
📤 **Resultado mostrado:**

```
horariodeclases es:
matematicas - 08:00am
fisica - 10:00am
historia - 12:00pm
```

### 💻 Ejemplo 7 (versión alternativa)

```python
#7
invitados_dia = ["Ana", "Luis", "Marta", "Pedro"]
invitados_noche = ["Luis", "Sofía", "Ana", "Juan"]

invitadostotal= list(set(invitados_dia + invitados_noche))# creamos una variable para poder unir las listas con set
print(invitadostotal)
```
📤 **Resultado mostrado:**

```
['Marta', 'Ana', 'Luis', 'Sofía', 'Pedro', 'Juan']
```

### 💻 Ejemplo 8 (versión alternativa)

```python
#8
inventario = [
    {"nombre": "Laptop", "precio": 900, "stock": 15},{"nombre": "Teléfono", "precio": 500, "stock": 30},{"nombre": "Tablet", "precio": 250, "stock": 20},{"nombre": "Auriculares", "precio": 100, "stock": 50},
    {"nombre": "Cargador", "precio": 25, "stock": 100}]
producto_buscar = input("Introduce el nombre del producto: ").lower()# Pedir al usuario el nombre del producto a buscar
producto_encontrado = next((producto for producto in inventario if producto["nombre"].lower() == producto_buscar), None)# Buscar el producto en el inventario

if producto_encontrado:
    print(f"Producto encontrado: {producto_encontrado}")
else:
    print("Producto no encontrado.")
```
📤 **Resultado mostrado:**

```
Introduce el nombre del producto: celular
Producto no encontrado.
```

### 💻 Ejemplo 9 (versión alternativa)

```python
#9
estudiantes = {"Ana": 4.5, "Luis": 3.8, "Marta": 4.8, "Pedro": 3.9}

estudiantes["Pedro"] = 2.9# Actualizar la calificación de Pedro
print(estudiantes)
```
📤 **Resultado mostrado:**

```
{'Ana': 4.5, 'Luis': 3.8, 'Marta': 4.8, 'Pedro': 2.9}
```

### 💻 Ejemplo 10 (versión alternativa)

```python
# 10
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
pares = [numero for numero in numeros if numero % 2 == 0]# aquí estamos creando una nueva lista con solo los números pares utilizando lista por comprensión
print(pares)
```
📤 **Resultado mostrado:**

```
[2, 4, 6, 8, 10]
```

### 💻 Ejemplo 11 (versión alternativa)

```python
#11
estudiantes = [
    {"nombre": "Ana", "promedio": 4.5, "curso": "10A"},
    {"nombre": "Luis", "promedio": 3.8, "curso": "10B"},
    {"nombre": "Marta", "promedio": 4.8, "curso": "10A"},
    {"nombre": "Pedro", "promedio": 3.9, "curso": "10C"},
    {"nombre": "Sofía", "promedio": 4.2, "curso": "10B"}
]

buenprom= [estudiante["promedio"] for estudiante in estudiantes if estudiante["promedio"] >= 4.5]# en este paso definimos una variable para sacar el promedio de los estudiantes
print(buenprom)
nombres_estudiantes = [estudiante["nombre"] for estudiante in estudiantes]# en este paso definimos una variable para sacar el listado de el nombre  de los estudiantes
print(nombres_estudiantes)
```
📤 **Resultado mostrado:**

```
[4.5, 4.8]
['Ana', 'Luis', 'Marta', 'Pedro', 'Sofía']
```

### 💻 Ejemplo 12 (versión alternativa)

```python
#12
ventas = [
    ("Laptop", "Electrónica", 1500),
    ("Camisa", "Ropa", 80),
    ("Mouse", "Electrónica", 50),
    ("Pantalón", "Ropa", 120),
    ("Teclado", "Electrónica", 70)
]

# Diccionario para almacenar el total de ventas por categoría
total_ventas = {}

# Recorrer las ventas y sumar el monto a la categoría correspondiente
for producto, categoria, monto in ventas:
    if categoria in total_ventas:
        total_ventas[categoria] += monto  # Si la categoría ya existe, sumar el monto
    else:
        total_ventas[categoria] = monto  # Si la categoría no existe, crearla con el monto inicial

# Mostrar el total de ventas por categoría
print(total_ventas)
```
📤 **Resultado mostrado:**

```
{'Electrónica': 1620, 'Ropa': 200}
```

### 💻 Ejemplo 13 (versión alternativa)

```python
#13

libro = {
    "titulo": "Python para Todos",
    "año": 2024,
    "autores": [
        {"nombre": "Raúl", "nacionalidad": "Española"},
        {"nombre": "Laura", "nacionalidad": "Mexicana"}
    ],
    "editorial": "Ediciones Código"}
nombres_autores = [autor["nombre"] for autor in libro["autores"]]# aquí estamos creando una lista con los nombres de los autore
print(nombres_autores)# Mostrar la lista de nombres de los autores
```
📤 **Resultado mostrado:**

```
['Raúl', 'Laura']
```

### 💻 Ejemplo 14 (versión alternativa)

```python
#14
# Diccionario de productos y precios
productos = {
    101: "Leche",
    102: "Pan",
    103: "Huevos"
}

precios = {
    101: 4500,
    102: 2500,
    103: 8000
}

ventas_del_dia = [
    (101, 5),  # Se vendieron 5 unidades de Leche
    (102, 10), # Se vendieron 10 unidades de Pan
    (101, 3),  # Se vendieron otras 3 unidades de Leche
    (103, 2)   # Se vendieron 2 unidades de Huevos
]
ingreso_total = 0


for id_producto, cantidad in ventas_del_dia:# Recorrer las ventas del día
    precio = precios[id_producto]# Obtener el precio del producto usando su ID
    ingreso_total += precio * cantidad# Calcular el ingreso de esa venta y sumarlo al total
print(f"Ingreso total del día: {ingreso_total}")
```
📤 **Resultado mostrado:**

```
Ingreso total del día: 77000
```




---
# 📘 Colas
---

> Este apartado corresponde al notebook **Colas**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
from collections import deque

eventos=deque()

while True:
  print("\n menu de la agenda")
  print("1 agregar un evento")
  print("2 ver eventos")
  print("3 eliminar primer evento")
  print("4 salir")

  op=input("digite la opción ")

  if op=="1":
    evento=input("escriba el evento: ")
    eventos.append(evento)
    print(f"el evento {evento} fue agregado")

  elif op=="2":
    if eventos:
      print(" eventos en la agenda")
      for i, e in enumerate(eventos, start=1):
        print(f"\n {i}. {e}")
    else:
      print("no hay eventos que mostrar")

  elif op=="3":
    if eventos:
      eliminado=eventos.popleft()
      print(f"el evento {eliminado} fue eliminado")
    else:
      print("no hay eventos para eliminar")

  elif op=="4":
    print("saliendo de la agenda")
    break
  else:
    print("opcion invalida, intente otra vez")
```
📤 **Resultado mostrado:**

```
menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
digite la opción 1
escriba el evento: salir
el evento salir fue agregado

 menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
digite la opción 1
escriba el evento: comer
el evento comer fue agregado

 menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
digite la opción 2
 eventos en la agenda
1. salir
2. comer

 menu de la agenda
1 agregar un evento
2 ver eventos
3 eliminar primer evento
4 salir
```

### 💻 Ejemplo 2 (versión alternativa)

```python
()
```




---
# 📘 Diccionarios (extra)
---

> Este apartado corresponde al notebook **Diccionarios (extra)**, con ejemplos comentados.

### 💻 Ejemplo 1 (versión alternativa)

```python
#Crea un diccionario persona con tu nombre, edad y ciudad. Luego imprime solo el valor de la ciudad.
persona = {'nombre':'lan' , 'edad':'28', 'ciudad':'bogota'}
print(persona['ciudad'])
```
📤 **Resultado mostrado:**

```
bogota
```

### 💻 Ejemplo 2 (versión alternativa)

```python
#A un diccionario frutas = {"manzana": 10, "pera": 5, "naranja": 8} agrega la fruta "sandía" con valor 3
frutas= {"manzana": 10, "pera": 5, "naranja": 8}
frutas['sandia']=3
print(frutas)
```
📤 **Resultado mostrado:**

```
{'manzana': 10, 'pera': 5, 'naranja': 8, 'sandia': 3}
```

### 💻 Ejemplo 3 (versión alternativa)

```python
#Cambia el valor de "pera" a 12 en el diccionario anterior.
frutas['pera']=12
print(frutas)
```
📤 **Resultado mostrado:**

```
{'manzana': 10, 'pera': 12, 'naranja': 8, 'sandia': 3}
```

### 💻 Ejemplo 4 (versión alternativa)

```python
colores = {"rojo": "#FF0000", "verde": "#00FF00", "azul": "#0000FF"}
for x in colores:
  print(colores[x])
```
📤 **Resultado mostrado:**

```
#FF0000
#00FF00
#0000FF
```

### 💻 Ejemplo 5 (versión alternativa)

```python
dato={'nombre':'camila', 'edad':'25','documento':'1234567'}
print(dato['nombre'])
print(dato['edad'])
```
📤 **Resultado mostrado:**

```
camila
25
```

### 💻 Ejemplo 6 (versión alternativa)

```python
dato['nombre']='marco'
print(dato)
```
📤 **Resultado mostrado:**

```
{'nombre': 'marco', 'edad': '25', 'documento': '1234567'}
```

### 💻 Ejemplo 7 (versión alternativa)

```python
for x in dato:
  print(x)
```
📤 **Resultado mostrado:**

```
nombre
edad
documento
```

### 💻 Ejemplo 8 (versión alternativa)

```python
for x , y in dato.items():
  print(x,y)
```
📤 **Resultado mostrado:**

```
nombre marco
edad 25
documento 1234567
```

### 💻 Ejemplo 9 (versión alternativa)

```python
dic1 = {"x": 10, "y": 20}
dic2 = {"m": 100, "n": 200}

dic3 = { "dic1":dic1, "dic2":dic2 }
print(dic3)
```
📤 **Resultado mostrado:**

```
{'dic1': {'x': 10, 'y': 20}, 'dic2': {'m': 100, 'n': 200}}
```

### 💻 Ejemplo 10 (versión alternativa)

```python
dicci={"a":1,"b":2}
dicci.clear()
print(dicci)
```
📤 **Resultado mostrado:**

```
{}
```

### 💻 Ejemplo 11 (versión alternativa)

```python
diccio={"a":1,"b":2}
print(diccio.get("a"))
print(diccio.get("c",'no encontrado'))
```
📤 **Resultado mostrado:**

```
1
no encontrado
```

### 💻 Ejemplo 12 (versión alternativa)

```python
dicci={"a":1,"b":2}
it=dicci.items()
print(it)
print(list(it))
print(list(it)[0][0])
```
📤 **Resultado mostrado:**

```
dict_items([('a', 1), ('b', 2)])
[('a', 1), ('b', 2)]
a
```

### 💻 Ejemplo 13 (versión alternativa)

```python
auto = {'marca': 'toyota', 'modelo':'corolla','año':'2020'}
print(auto.get('marca'))
```
📤 **Resultado mostrado:**

```
toyota
```

### 💻 Ejemplo 14 (versión alternativa)

```python
auto['color']='rojo'
print(auto)
```
📤 **Resultado mostrado:**

```
{'marca': 'toyota', 'modelo': 'corolla', 'año': '2020', 'color': 'rojo'}
```

### 💻 Ejemplo 15 (versión alternativa)

```python
for x in auto:
  print(auto[x])
```
📤 **Resultado mostrado:**

```
toyota
corolla
2020
rojo
```

### 💻 Ejemplo 16 (versión alternativa)

```python
it=auto.items()
print(list(it))
```
📤 **Resultado mostrado:**

```
[('marca', 'toyota'), ('modelo', 'corolla'), ('año', '2020'), ('color', 'rojo')]
```

### 💻 Ejemplo 17 (versión alternativa)

```python
d1={"x":1,"y":2}
d2={"y":10,"z":30}
d1.update(d2)
print(d1)
```
📤 **Resultado mostrado:**

```
{'x': 1, 'y': 10, 'z': 30}
```

### 💻 Ejemplo 18 (versión alternativa)

```python
d={"a":100,"b":200,"c":300}
d.pop("b")
print(d)
```
📤 **Resultado mostrado:**

```
{'a': 100, 'c': 300}
```

### 💻 Ejemplo 19 (versión alternativa)

```python
notas={"mate":5,"prog":4,"ingles":3}

K= notas.keys()
print(list(K))
v=notas.values()
print(list(v))
```
📤 **Resultado mostrado:**

```
['mate', 'prog', 'ingles']
[5, 4, 3]
```

### 💻 Ejemplo 20 (versión alternativa)

```python
hijo1 = {"nombre": "ana", "edad": 12}
hijo2 = {"nombre": "pedro", "edad": 15}
familia = {"hijo1": hijo1, "hijo2": hijo2}
print(familia)
```
📤 **Resultado mostrado:**

```
{'hijo1': {'nombre': 'ana', 'edad': 12}, 'hijo2': {'nombre': 'pedro', 'edad': 15}}
```

### 💻 Ejemplo 21 (versión alternativa)

```python
print(hijo2['nombre'])
```
📤 **Resultado mostrado:**

```
pedro
```

### 💻 Ejemplo 22 (versión alternativa)

```python
curso={'nombre':'python', 'duración':'3meses', 'estudiantes':'25'}
print(curso)
```
📤 **Resultado mostrado:**

```
{'nombre': 'python', 'duración': '3meses', 'estudiantes': '25'}
```

### 💻 Ejemplo 23 (versión alternativa)

```python
print(curso['duración'])
```
📤 **Resultado mostrado:**

```
3meses
```

### 💻 Ejemplo 24 (versión alternativa)

```python
curso['estudiantes']=30
print(curso)
```
📤 **Resultado mostrado:**

```
{'nombre': 'python', 'duración': '3meses', 'estudiantes': 30}
```

### 💻 Ejemplo 25 (versión alternativa)

```python
curso['profesor']='carlos'
print(curso)
```
📤 **Resultado mostrado:**

```
{'nombre': 'python', 'duración': '3meses', 'estudiantes': 30, 'profesor': 'carlos'}
```

### 💻 Ejemplo 26 (versión alternativa)

```python
for x in curso:
  print(x)
```
📤 **Resultado mostrado:**

```
nombre
duración
estudiantes
profesor
```

### 💻 Ejemplo 27 (versión alternativa)

```python
for x in curso:
  print(curso[x])
```
📤 **Resultado mostrado:**

```
python
3meses
30
carlos
```

### 💻 Ejemplo 28 (versión alternativa)

```python
for x,y in curso.items():
  print(x,y)
```
📤 **Resultado mostrado:**

```
nombre python
duración 3meses
estudiantes 30
profesor carlos
```

### 💻 Ejemplo 29 (versión alternativa)

```python
d4 = {"id": 1, "ciudad": "Bogotá"}
d5 = {"pais": "Colombia", "id": 2}
d4.update(d5)
print(d4)
```
📤 **Resultado mostrado:**

```
{'id': 2, 'ciudad': 'Bogotá', 'pais': 'Colombia'}
```

### 💻 Ejemplo 30 (versión alternativa)

```python
dictionario= {"nombre":"Laura","edad":22,"carrera":"software"}
dictionario.pop("edad")
print(dictionario)
```
📤 **Resultado mostrado:**

```
{'nombre': 'Laura', 'carrera': 'software'}
```

### 💻 Ejemplo 31 (versión alternativa)

```python
dictionario.popitem()
print(dictionario)
```
📤 **Resultado mostrado:**

```
{'nombre': 'Laura'}
```

### 💻 Ejemplo 32 (versión alternativa)

```python
d={"x":1,"y":2,"z":3}
print(d.get('y'))
```
# Documentación Consolidada de Notebooks

## Set.ipynb

``` python
s= set([5, 4,8,8,1])
print(s) #{1,4,5,6,8}
print(type(s))
```

``` python
s= {5, 4, 6, 8, 8, 1 }
print(s) #{1,4,5,6,8}
print(type(s))
```

``` python
s= set([5, 6, 7, 8 ])
```

``` python
lista = ["peru", "aegentina"]
s= set(["mexico", "españa", lista])
```

``` python
lista = ["peru", "aegentina"]
lista.append("mexico")
lista.append("españa")
print(lista)
```

``` python
s= set([5, 6, 7, 8])
for ss in s:
  print(ss)
```

``` python
s= set([1,2,2,3,4])
print(len(s))
```

``` python
s={"alan","paka","darian", "darian"}
print(len(s))
print(type(s))
```

``` python
s=set(["guitarra", "bajo"])
print("guitarra" in s)
```

``` python
s=set(["guitarra", "bajo"])
print("bateria" in s)
```

``` python
s1=set([1,2,3])
s2=set([3,4,5,])
print(s1 | s2)
```

``` python
l=set([1,2])
l.add(3)
print(l)
```

``` python
s=set ([1,2])
s.remove(2)
print(s)
```

``` python
s=set ([1,2])
s.discard(2)
print(s)
```

``` python
s=set ([1,2])
s.pop()
print(s)
```

``` python
s=set ([1,2])
s.clear()
print(s)
```

``` python
s1={1,2,3}
s2={3,4,5}
print(s1.union(s2))
```

``` python
s1={1,2,3}
s2={3,4,5}
print(s1.intersection(s2))
```

``` python
frontnd = set(["html", "css", "js", "react"])
backnd = set(["python", "sql", "js", "django"])
frontnd.add("vue.js")
backnd.remove("django")
diferencia = frontnd.difference(backnd)
print(frontnd | backnd)
print(frontnd.intersection(backnd))
print(diferencia)



```

------------------------------------------------------------------------

## esto es una tupla (no se puede modificar)s.ipynb

``` python
mi_tupla =(1,2,3,"hola", True) #acepta como una lista cualquier tipo de datos, inmutable sin añadir o eliminar elementos
print(mi_tupla)
```

``` python
t=(1,1,2,3,3,3) # admite valores repetidos
print(t)
```

``` python
#lista
listas =[1,2,3]

#tupla
tupla=(1,2,3)


#en lista se puede modificar
listas[0] =10

#en tupla no se puede
tupla[0] =10

```

``` python
coordenadas =(40.7128, -74.0060) #lat y lon (new york)
# coordenadas [0] =41.0 - esto daria error por que es inmutable
```

``` python
t1=(1,2,3) # con enteros
t2=("a","b","c") #cadenas de texto
t3=(1, "hola", 3.5) # esto es una tupla (no se puede modificar) con tipos mixtos
t4= ()# vacia
t5=(5,)# esto es una tupla (no se puede modificar) con un solo elemento

```

``` python
#acceso por indice

tupla=("python", 2025, True)
print(tupla[0])
print(tupla[1])
print(tupla[-1])
```

``` python
#slicing

tupla =(10,20,30,40,50)
print(tupla[1:4]) # del indice 1 al 3
print(tupla[:3]) # desde el inicio hasta el indice 2
print(tupla[::2]) # saltando de 2 en 2
```

``` python
#itrerar

colores= ("rojo", "verde", "azul")
for color in colores: # recorre acda element de la tupla
    print(color)
```

``` python
#anidadas

t=((1,2), (3,4), (5,6))
print(t[0]) # par acceder  a la primer tupla interna
print(t[0][1]) # accede al segundo elemento de la primer tupla
```

``` python
t1 = (1,2,3)
t2= (4,5,6)
resultado = t1+t2
print(resultado)
```

``` python
t= ("python",) * 3
print(t)
```

``` python
#Pertenencia
t=(10,20,30,40)
print(20 in t) # true si esta enla tupla
print(50 not in t) # true si no esta en la tupla
```

``` python
# desempaquetado
persona=("darian", 22, "colombia")
nombre , edad, pais = persona
print(nombre)
print(edad)
print(pais)
```

``` python
#metodos deisponibles, pocos metodos

t=(1,2,2,3,4)
print(t.count(2)) # cuenta cuantas veces aparee un elemento
print(t.index(3)) # devuelve el indice de la primera aparición
```

``` python
#funciones utiles
t = (5,1,7,3)
print(len(t)) # numero de elementos
print(max(t)) #valor maximo
print(min(t)) #valor minimo
print(sum(t)) #suma de los elementos
print(sorted(t)) # devuelve una nueva lista ordenada
```

``` python
# conversion entre lista y tupla

lista = [1,2,3]
tupla = tuple(lista)
print(tupla)

nueva_lista =list(tupla)
print(nueva_lista)
```

``` python
# usos practicos

personas= ("darian", 22, "colombia")
# acceder a cada atributo usando indices
print("nombre:", personas[0])
print("edad:", personas[1])
print("pais:", personas[2])
```

``` python
#claves en diccionario

coordenadas ={}
punto =(10,20)
coordenadas[punto] = "ubicacion A "
print(coordenadas)
```

``` python
#devolciendo multiples valores

def operaciones(a,b):
  return a+b, a-b, a*b, a/b

suma, resta, multiplicacion, division = operaciones(5,3)
print(suma, resta, multiplicacion, division)
```

``` python
#iteracion

frutas= ("manzana", "pera", "uva")
for i, fruta in enumerate(frutas):
  print(i, fruta)
```

``` python
#intercambio de valores
a,b =10,20
a,b = b,a
print(a,b)
```

``` python
# Ejercicio 1 – Crear una tupla
t = (1, 2, 3, 4, 5)
print(t) # (1, 2, 3, 4, 5)
```

``` python
# Ejercicio 2 – Acceder al tercer elemento
t = (10, 20, 30, 40, 50)
print(t[2]) # 30
```

``` python
# Ejercicio 3 – Tupla con nombre y edad
info = ("Nicolás", 22)
print("Nombre:", info[0], "Edad:", info[1])
```

``` python
# Ejercicio 4 – Concatenar tuplas
t1 = (1, 2, 3)
t2 = (4, 5, 6)
print(t1 + t2) # (1, 2, 3, 4, 5, 6)
```

``` python
# Ejercicio 5 – Repetir una tupla
t = ("Python",) * 3
print(t) # ('Python', 'Python', 'Python')
```

``` python
# Ejercicio 6 – Verificar pertenencia
t = (5, 10, 15, 20, 25)
print(20 in t) # True
```

``` python
# Ejercicio 7 – Desempaquetar tupla
paises = ("Colombia", "México", "Argentina")
a, b, c = paises
print(a, b, c) # Colombia México Argentina
```

``` python
# Ejercicio 8 – Tupla anidada
t = ((1, 2), (3, 4))
print(t[1][1]) # 4
```

``` python
# Ejercicio 9 – Función con suma y producto
def operaciones(a, b):
    return a+b, a*b
print(operaciones(3, 5)) # (8, 15)
```

``` python
# Ejercicio 10 – Intercambio de valores
a, b = 7, 9
a, b = b, a
print(a, b) # 9 7
```

``` python
# Ejercicio 11 – Contar apariciones
t = (2, 4, 6, 2, 8, 2)
print(t.count(2)) # 3
```

``` python
# Ejercicio 12 – Índice de un valor
t = (10, 20, 30, 40, 50)
print(t.index(50)) # 4
```

``` python
# Ejercicio 13 – Funciones integradas
t = (4, 7, 1, 9, 3)
print(max(t)) # 9
print(min(t)) # 1
print(sum(t)) # 24
```

``` python
# Ejercicio 14 – Convertir lista a tupla
lista = [10, 20, 30]
t = tuple(lista)
print(t) # (10, 20, 30)
```

``` python
# Ejercicio 15 – Enumerate con tuplas
colores = ("rojo", "verde", "azul")
for i, color in enumerate(colores):
    print(i, color)
```

------------------------------------------------------------------------

## Untitled0.ipynb

``` python
# Árbol binario representado con listas
# Estructura: [valor, Hijo_izquierdo, Hijo_derecho]

# aquí estamos creando el árbol
#
#     1
#    / \
#   2   3
#  / \
# 4   5

def crear_nodo(valor, izquierdo=None, derecho=None):
    # Función para crear un nodo con valor e hijos opcionales
    return [valor, izquierdo, derecho]

# Construir el árbol de abajo hacia arriba
nodo2 = crear_nodo(2, crear_nodo(4), crear_nodo(5))
nodo3 = crear_nodo(3)
raiz = crear_nodo(1, nodo2, nodo3)

# Función para recorrer el árbol en preorder (raíz, izquierdo, derecho)
def recorrer_preorden(nodo):
    if nodo is None:  # Caso base: nodo vacío
        return
    print(nodo[0], end=" ")  # mostramos en pantalla valor del nodo
    recorrer_preorden(nodo[1])  # Recorrer subárbol izquierdo
    recorrer_preorden(nodo[2])  # Recorrer subárbol derecho

print("Recorrido en preorden:")
recorrer_preorden(raiz)  # Salida: 1 2 4 5 3
```

``` python
# Árbol de expresiones matemáticas con tuplas (inmutables)
# Estructura: (operador, operando_izq, operando_der)
# Representa la expresión: (3 + 5) * (2 - 1)

# aquí estamos creando subexpresión: 3 + 5
suma = ('+', 3, 5)

# aquí estamos creando subexpresión: 2 - 1
resta = ('-', 2, 1)

# Combinar en expresión principal: (3 + 5) * (2 - 1)
expresion = ('*', suma, resta)

# Función para evaluar el árbol de expresiones
def evaluar(nodo):
    # Si el nodo es un número, devolverlo directamente
    if isinstance(nodo, (int, float)):
        return nodo

    # Extraer operador y operandos
    operador, izq, der = nodo
      # Evaluar recursivamente los operandos
    valor_izq = evaluar(izq)
    valor_der = evaluar(der)

    # Aplicar la operación según el operador
    if operador == '+':
        return valor_izq + valor_der
    elif operador == '-':
        return valor_izq - valor_der
    elif operador == '*':
        return valor_izq * valor_der
    elif operador == '/':
        return valor_izq / valor_der

# Evaluar la expresión completa
resultado = evaluar(expresion)
print(f"Resultado de (3 + 5) * (2 - 1) = {resultado}")  # Salida: 8
```

``` python
# Árbol Binario de Búsqueda (BST) con clases
# Los valores menores van a la izquierda, mayores a la derecha

class Nodo:
    # Clase que representa un nodo individual del árbol
    def __init__(self, valor):
        self.valor = valor  # Dato almacenado en el nodo
        self.izquierdo = None  # Referencia al hijo izquierdo
        self.derecho = None  # Referencia al hijo derecho

class ArbolBinarioBusqueda:
    # Clase que representa el árbol completo
    def __init__(self):
        self.raiz = None  # Inicialmente el árbol está vacío

    def insertar(self, valor):
        # Método público para insertar un valor
        if self.raiz is None:
            self.raiz = Nodo(valor)  # Si el árbol está vacío, crear raíz
        else:
            self._insertar_recursivo(self.raiz, valor)  # Insertar recursivamente

    def _insertar_recursivo(self, nodo, valor):
        # Método privado para insertar recursivamente
        if valor < nodo.valor:  # Si es menor, va a la izquierda
            if nodo.izquierdo is None:
                nodo.izquierdo = Nodo(valor)  # aquí estamos creando nuevo nodo
            else:
                self._insertar_recursivo(nodo.izquierdo, valor)  # Seguir buscando
        else:  # Si es mayor o igual, va a la derecha
            if nodo.derecho is None:
                nodo.derecho = Nodo(valor)  # aquí estamos creando nuevo nodo
            else:
                self._insertar_recursivo(nodo.derecho, valor)  # Seguir buscando

    def buscar(self, valor):
        # Buscar un valor en el árbol
        return self._buscar_recursivo(self.raiz, valor)

    def _buscar_recursivo(self, nodo, valor):
        # Método privado para buscar recursivamente
        if nodo is None:
            return False  # No se encontró el valor
        if nodo.valor == valor:
            return True  # Se encontró el valor
        elif valor < nodo.valor:
            return self._buscar_recursivo(nodo.izquierdo, valor)  # Buscar a la izquierda
        else:
            return self._buscar_recursivo(nodo.derecho, valor)  # Buscar a la derecha

    def inorden(self):
        # Recorrido inorden: izquierda-raíz-derecha (muestra valores ordenados)
        resultado = []
        self._inorden_recursivo(self.raiz, resultado)
        return resultado

    def _inorden_recursivo(self, nodo, resultado):
        # Método privado para recorrido inorden
        if nodo:
            self._inorden_recursivo(nodo.izquierdo, resultado)  # Visitar izquierda
            resultado.append(nodo.valor)  # Visitar raíz
            self._inorden_recursivo(nodo.derecho, resultado)  # Visitar derecha

# aquí estamos creando y usar el árbol
arbol = ArbolBinarioBusqueda()
valores = [50, 30, 70, 20, 40, 60, 80]

# Insertar valores en el árbol
for valor in valores:
    arbol.insertar(valor)

# Mostrar valores ordenados
print("Valores en orden:", arbol.inorden())  # [20, 30, 40, 50, 60, 70, 80]

# Buscar valores
print("¿Está el 40?", arbol.buscar(40))  # True
print("¿Está el 100?", arbol.buscar(100))  # False
```

``` python
# Árbol N-ario (cada nodo puede tener múltiples hijos) con diccionarios
# Representa un sistema de archivos

# aquí estamos creando estructura de carpetas y archivos
sistema_archivos = {
    'nombre': 'raiz',  # Nombre del directorio
    'tipo': 'carpeta',  # Tipo de nodo
    'hijos': [  # esta es una lista de hijos (subcarpetas y archivos)
        {
            'nombre': 'documentos',
            'tipo': 'carpeta',
            'hijos': [
                {'nombre': 'trabajo.pdf', 'tipo': 'archivo', 'tamaño': 150},
                {'nombre': 'personal.docx', 'tipo': 'archivo', 'tamaño': 80}
            ]
        },
        {
            'nombre': 'imagenes',
            'tipo': 'carpeta',
            'hijos': [
                {'nombre': 'foto1.jpg', 'tipo': 'archivo', 'tamaño': 200},
                {'nombre': 'foto2.png', 'tipo': 'archivo', 'tamaño': 300}
            ]
        },
        {'nombre': 'readme.txt', 'tipo': 'archivo', 'tamaño': 10}
    ]
}

# Función para mostrar la estructura del árbol con indentación
def mostrar_arbol(nodo, nivel=0):
    # aquí estamos creando indentación según el nivel de profundidad
    indentacion = "  " * nivel

    # Mostrar información del nodo actual
    if nodo['tipo'] == 'carpeta':
        print(f"{indentacion}📁 {nodo['nombre']}/")
    else:
        print(f"{indentacion}📄 {nodo['nombre']} ({nodo['tamaño']} KB)")

    # Recorrer recursivamente los hijos si existen
    if 'hijos' in nodo:
        for hijo in nodo['hijos']:
            mostrar_arbol(hijo, nivel + 1)

# Función para calcular el tamaño total del árbol
def calcular_tamaño(nodo):
    # Si es un archivo, devolver su tamaño
    if nodo['tipo'] == 'archivo':
        return nodo['tamaño']

    # Si es carpeta, sumar el tamaño de todos los hijos
    tamaño_total = 0
    if 'hijos' in nodo:
        for hijo in nodo['hijos']:
            tamaño_total += calcular_tamaño(hijo)

    return tamaño_total

# Mostrar la estructura del sistema de archivos
print("Estructura del sistema de archivos:")
mostrar_arbol(sistema_archivos)

# Calcular y mostrar el tamaño total
tamaño = calcular_tamaño(sistema_archivos)
print(f"\nTamaño total: {tamaño} KB")  # Salida: 740 KB
```

``` python
# Árbol de decisión para clasificar animales usando conjuntos
# Los conjuntos permiten verificaciones rápidas de pertenencia

class NodoDecision:
    # Clase para nodos de decisión con conjuntos de respuestas válidas
    def __init__(self, pregunta, respuestas_validas):
        self.pregunta = pregunta  # Pregunta a realizar
        self.respuestas_validas = set(respuestas_validas)  # Conjunto de respuestas válidas
        self.hijos = {}  # Diccionario: respuesta -> siguiente nodo
        self.resultado = None  # Resultado final si es nodo hoja

    def agregar_hijo(self, respuesta, nodo):
        # Agregar un hijo al árbol de decisión
        if respuesta in self.respuestas_validas:
            self.hijos[respuesta] = nodo
        else:
            print(f"⚠️ Error: '{respuesta}' no es una respuesta válida")

    def es_hoja(self):
        # Verificar si es un nodo hoja (nodo final con resultado)
        return self.resultado is not None

# Construir el árbol de decisión para clasificar animales
# Estructura del árbol:
#                   ¿Tiene pelo?
#                   /         \
#                 Sí          No
#                 /            \
#         ¿Es grande?      ¿Puede volar?
#          /    \            /      \
#        Sí     No         Sí       No
#        |      |          |        |
#      Oso   Gato      Pájaro   Serpiente

# aquí estamos creando nodos hoja (resultados finales)
nodo_oso = NodoDecision("", [])
nodo_oso.resultado = "🐻 Es un oso"

nodo_gato = NodoDecision("", [])
nodo_gato.resultado = "🐱 Es un gato"

nodo_pajaro = NodoDecision("", [])
nodo_pajaro.resultado = "🐦 Es un pájaro"

nodo_serpiente = NodoDecision("", [])
nodo_serpiente.resultado = "🐍 Es una serpiente"

# aquí estamos creando nodos de decisión intermedios
nodo_grande = NodoDecision("¿Es grande?", {'si', 'no'})
nodo_grande.agregar_hijo('si', nodo_oso)
nodo_grande.agregar_hijo('no', nodo_gato)

nodo_volar = NodoDecision("¿Puede volar?", {'si', 'no'})
nodo_volar.agregar_hijo('si', nodo_pajaro)
nodo_volar.agregar_hijo('no', nodo_serpiente)

# aquí estamos creando nodo raíz
raiz = NodoDecision("¿Tiene pelo?", {'si', 'no'})
raiz.agregar_hijo('si', nodo_grande)
raiz.agregar_hijo('no', nodo_volar)

# Función para recorrer el árbol y clasificar
def clasificar(nodo):
    # Si llegamos a un nodo hoja, mostrar resultado
    if nodo.es_hoja():
        print(f"\n🎯 Resultado: {nodo.resultado}")
        return

    # Hacer la pregunta y obtener respuesta
    print(f"\n❓ {nodo.pregunta}")
    print(f"   Respuestas válidas: {', '.join(nodo.respuestas_validas)}")
    respuesta = input("   Tu respuesta: ").lower().strip()

    # Validar respuesta usando el conjunto
    if respuesta not in nodo.respuestas_validas:
        print(f"   ⚠️ Respuesta inválida. Por favor usa: {nodo.respuestas_validas}")
        return clasificar(nodo)  # Volver a preguntar

    # Continuar con el siguiente nodo según la respuesta
    siguiente_nodo = nodo.hijos.get(respuesta)
    if siguiente_nodo:
        clasificar(siguiente_nodo)

# Ejecutar el clasificador
print("=== 🔍 Clasificador de Animales ===")
print("Responde las preguntas para identificar el animal\n")
# clasificar(raiz)  # Descomentar para ejecutar de forma interactiva

# Demostración con respuestas predefinidas
print("Ejemplo 1: Animal con pelo, grande")
print("Resultado esperado: Oso")
```

------------------------------------------------------------------------

## Untitled1.ipynb

``` python
vector1 = []
vector2 = []
vector1=len(input("digite el valor del elemeto"))
vector2=len(input("digite el valor del elemento"))

vector1.len


print(vector1)
print(vector2)

```

------------------------------------------------------------------------

## Untitled7.ipynb

``` python
# Árbol binario representado con listas
# Estructura: [valor, hijo_izquierdo, hijo_derecho]

# aquí estamos creando el árbol
#       1
#      / \
#     2   3
#    / \
#   4   5

def crear_nodo(valor, izquierdo=None, derecho=None):
    # Función para crear un nodo con valor e hijos opcionales
    return [valor, izquierdo, derecho]

# Construir el árbol de abajo hacia arriba
nodo4 = crear_nodo(4)  # Hoja izquierda
nodo5 = crear_nodo(5)  # Hoja derecha
nodo2 = crear_nodo(2, nodo4, nodo5)  # Nodo con dos hijos
nodo3 = crear_nodo(3)  # Hoja derecha de la raíz
raiz = crear_nodo(1, nodo2, nodo3)  # Raíz del árbol
```

``` python
# Función para recorrer el árbol en preorden (raíz-izquierda-derecha)
def recorrer_preorden(nodo):
    if nodo is None:  # Caso base: nodo vacío
        return
    print(nodo[0], end=" ")  # mostramos en pantalla valor del nodo
    recorrer_preorden(nodo[1])  # Recorrer subárbol izquierdo
    recorrer_preorden(nodo[2])  # Recorrer subárbol derecho

print("Recorrido en preorden:")
recorrer_preorden(raiz)  # Salida: 1 2 4 5 3
```

``` python
# Árbol de expresiones matemáticas con tuplas (inmutables)
# Estructura: (operador, operando_izq, operando_der)
# Representa la expresión: (3 + 5) * (2 - 1)

# aquí estamos creando subexpresión: 3 + 5
suma = ('+', 3, 5)

# aquí estamos creando subexpresión: 2 - 1
resta = ('-', 2, 1)

# Combinar en expresión principal: (3 + 5) * (2 - 1)
expresion = ('*', suma, resta)

# Función para evaluar el árbol de expresiones
def evaluar(nodo):
    # Si el nodo es un número, devolverlo directamente
    if isinstance(nodo, (int, float)):
        return nodo

    # Extraer operador y operandos
    operador, izq, der = nodo
```

``` python
 # Evaluar recursivamente los operandos
    valor_izq = evaluar(izq)
    valor_der = evaluar(der)

    # Aplicar la operación según el operador
    if operador == '+':
        return valor_izq + valor_der
    elif operador == '-':
        return valor_izq - valor_der
    elif operador == '*':
        return valor_izq * valor_der
    elif operador == '/':
        return valor_izq / valor_der

# Evaluar la expresión completa
resultado = evaluar(expresion)
print(f"Resultado de (3 + 5) * (2 - 1) = {resultado}")  # Salida: 8
```

``` python
# Árbol Binario de Búsqueda (BST) con clases
# Los valores menores van a la izquierda, mayores a la derecha

class Nodo:
    # Clase que representa un nodo individual del árbol
    def __init__(self, valor):
        self.valor = valor  # Dato almacenado en el nodo
        self.izquierdo = None  # Referencia al hijo izquierdo
        self.derecho = None  # Referencia al hijo derecho

class ArbolBinarioBusqueda:
    # Clase que representa el árbol completo
    def __init__(self):
        self.raiz = None  # Inicialmente el árbol está vacío

    def insertar(self, valor):
        # Método público para insertar un valor
        if self.raiz is None:
            self.raiz = Nodo(valor)  # Si el árbol está vacío, crear raíz
        else:
            self._insertar_recursivo(self.raiz, valor)  # Insertar recursivamente

    def _insertar_recursivo(self, nodo, valor):
        # Método privado para insertar recursivamente
        if valor < nodo.valor:  # Si es menor, va a la izquierda
```

``` python
def _buscar_recursivo(self, nodo, valor):
        # Método privado para buscar recursivamente
        if nodo is None:
            return False  # No se encontró el valor
        if nodo.valor == valor:
            return True  # Se encontró el valor
        elif valor < nodo.valor:
            return self._buscar_recursivo(nodo.izquierdo, valor)  # Buscar a la izquierda
        else:
            return self._buscar_recursivo(nodo.derecho, valor)  # Buscar a la derecha

    def inorden(self):
        # Recorrido inorden: izquierda-raíz-derecha (muestra valores ordenados)
        resultado = []
        self._inorden_recursivo(self.raiz, resultado)
        return resultado
```

``` python
def _inorden_recursivo(self, nodo, resultado):
        # Método privado para recorrido inorden
        if nodo:
            self._inorden_recursivo(nodo.izquierdo, resultado)  # Visitar izquierda
            resultado.append(nodo.valor)  # Visitar raíz
            self._inorden_recursivo(nodo.derecho, resultado)  # Visitar derecha

# aquí estamos creando y usar el árbol
arbol = ArbolBinarioBusqueda()
valores = [50, 30, 70, 20, 40, 60, 80]

# Insertar valores en el árbol
for valor in valores:
    arbol.insertar(valor)

# Mostrar valores ordenados
print("Valores en orden:", arbol.inorden())  # [20, 30, 40, 50, 60, 70, 80]

# Buscar valores
print("¿Está el 40?", arbol.buscar(40))  # True
print("¿Está el 100?", arbol.buscar(100))  # False
```

``` python
# Mostrar la estructura del sistema de archivos
print("Estructura del sistema de archivos:")
mostrar_arbol(sistema_archivos)

# Calcular y mostrar el tamaño total
tamaño = calcular_tamaño(sistema_archivos)
print(f"\nTamaño total: {tamaño} KB")  # Salida: 740 KB
```

------------------------------------------------------------------------

## workclass3.ipynb

``` python
#1
saludo="hola mundo :/"  #se declara la variable
print (saludo) # se imprime el mensaje de la variable
```

``` python
#2
nombre = input("escribe tu nombre:") # se usa input para poder que el usuario escriba por consola
print("hola " + nombre) #se usa el print para enviar la respuesta concatenada con el mensaje
```

``` python
#3
num1 = int(input("Escribe el 1er numero:")) # se declaran las variables
num2 = int(input("Escribe el 2do numero:"))

# se genran las operaciones básicas
suma = num1+num2
resta = num1- num2
multi = num1 * num2
if num2!= 0: # se usa un if para evitar error si el usuario digita 0
  divi = num1 / num2
else:
  divi = "No se puede dividir entre 0"

print("suma", suma )# se inmprime las respuestas
print("resta", resta )
print("multiplicación", multi )
print("division", divi )
```

``` python
#4
hrt = int(input("Escribe el numero de horas trabajadas:")) # se solicita al usuario y se almacena en una variable
pgt =int(input("Escribe el pago por hora"))

#se realiza la operacion para sacar el apago
multi = hrt*pgt
print("el valor que corresponde al pago es", multi) # se imprime el resultado
```

``` python
#5
n =int(input("Escribe un numero entero")) # se solicita el numero para almacenarlo en la variable


#se genera un for para hacer un la suma de losnumeros
for  i in range (1, n+1):
  suma +=i

print(" la suma de los numero del 1 hasta",n , "es", suma)# se imprime el resultado
```

``` python
#6
peso =float(input("Escribe tu peso en kg"))# se solicita al cliente que digite lo valores para ser almacenados
est =float(input("Escribe tu estatura en metros"))

imc = peso / (est ** 2) # se realiza la operación para sacar el resultado  se almacena en otra variable

print("el índice de masa corporal calculado es ", imc) # se imprime el resultado
```

``` python
#7
n = int(input("Escribe el primer numero n"))
m = int(input("Escribe el primer numero m"))# se solicita al cliente que digite lo valores para ser almacenados

cos = n//m# se realiza la operación para sacar el resultado  se almacena en otra variable
res = n%m

print(f"{n} entre {m} da un cosiente {cos} y un resto {res} ")# se imprime el resultado
```

``` python
#8
inver = float(input("Escribe la cantidad a invertir"))# se solicita al cliente que digite lo valores para ser almacenados
inter = float(input("Escribe el interes anual "))
años= int(input("Escribe la cantidad de años "))

cap = inver*(1+inter / 100 )** años # se realiza la operación para sacar el resultado  se almacena en otra variable

print(f"El capital obtenido es {round(cap,2)}"))# se imprime el resultado
```

``` python
#9
clown = int(input("Escribe la cantidad de payasosn vendidos"))# se solicita al cliente que digite lo valores para ser almacenados
doll = int(input("Escribe la cantidad de muñecas vendidos"))

pclown = 112
pdoll = 75

pest= (pclown * clown) + (pdoll * doll)#se realiza la operación para sacar el resultado  se almacena en otra variable

print(f" el peso total del paquete es {pest} gramops")# se imprime el resultado
```

``` python
#11
prebar = 4000
desc =0.60

barranof =int(input(" numero de barras que no son del dia "))

predesc = prebar * (1 - desc)
costt = barranof * predesc

print(f"precio habitual de una barra es ${prebar}")
print(f"descuento aplicado es {int(desc * 100)}%")
print(f"costo total por ${barranof} barras no frescas $ {round(costt, 2)}")
```

``` python
#10
ahor = float(input("introduce la cantidad despositada en la cuenta"))

inter = 0.40

primeraño = ahor * (1+ inter) ** 1
segunaño = ahor * (1+ inter) ** 2
terceraño = ahor * (1+ inter) ** 3

print(f"ahorros tras 1er año {round(primeraño,2)}")
print(f"ahorros tras 2do año {round(segunaño,2)}")
print(f"ahorros tras 3er año {round(terceraño,2)}")
```

``` python
#12
n= int (input(" cuantas palabras deseas agregar en la lista?"))

palabras= []

for i in range(n):
  palabra = input (f"ingrese la palabra {i+1}")
  palabras.append(palabra)

  print("la lista de palabras es:")
  print(palabras)
```

``` python
#13
n= int (input(" cuantas palabras deseas agregar en la lista?"))
palabras= []
for i in range(n):
  palabra = input (f"ingrese la palabra {i+1}")
  palabras.append(palabra)

  print("\nla lista de palabras es:", palabras)

  buscar = input("\n ingrese la palabra que desea buscar")
  contador = palabras.count(buscar)



  print(f"la palabra '{buscar}' apareces {contador} veces en la lista")

```

------------------------------------------------------------------------
# 🧠 Proyecto: Resolución de Problemas Algorítmicos con Gemini API

Este proyecto combina **ejercicios clásicos de estructuras de datos** (pilas, colas, listas, etc.) con el uso de la **API de Gemini** (Google Generative AI) para resolver problemas algorítmicos automáticamente.  

---

## 📂 Estructura del Proyecto

```
├── datos/
│   └── problema1.txt       # Contiene la pregunta/problema en texto plano
├── ia.py                   # Conexión y configuración de Gemini API
├── main.py                 # Script principal: lee la pregunta y muestra la respuesta
├── prueba.py               # Espacio para probar el código generado
├── Ejercicios de Estructuras de Datos.docx   # 50 ejercicios resueltos en Python
├── HOW.MD                  # Explicación conceptual de IA y su funcionamiento
├── README.MD               # Documentación principal del proyecto
└── Arboles.ipynb           # Ejercicios prácticos en Jupyter Notebook
```

---

## ⚙️ Flujo de Ejecución

1. ✍️ El usuario escribe un problema en `datos/problema1.txt`.
2. 📤 `main.py` lee el archivo y envía la pregunta a la función `api_ia()` definida en `ia.py`.
3. 🤖 La IA genera:
   - Una **explicación del algoritmo**.
   - El **código en Python** con comentarios.
   - Una **justificación del enfoque**.
4. 🖥️ El resultado se muestra en consola y puede probarse en `prueba.py`.

---

## 📘 Ejercicios Incluidos

El archivo `Ejercicios de Estructuras de Datos.docx` contiene **50 ejercicios resueltos en Python**, organizados así:

- 🔹 **Pilas (10 ejercicios):**
  - Balanceo de paréntesis.
  - Conversión infijo → postfijo.
  - Evaluar expresión postfija.
  - Invertir lista con pila.
  - Eliminar duplicados consecutivos.
  - Siguiente elemento mayor.
  - Validar secuencia push/pop.
  - Pila con mínimo en O(1).
  - Dos pilas en un array.
  - Ordenar pila.

- 🔹 **Colas (10 ejercicios):**
  - Cola con pilas.
  - Cola circular.
  - Revertir primeros *k* elementos.
  - Generar números binarios.
  - Cola de prioridad.
  - Cola eficiente con stacks.
  - Intercalar colas.
  - Revertir cola recursivamente.
  - Problema del puente.
  - Cola con máximo.

- 🔹 **Listas (10 ejercicios):**
  - Intersección / Unión de listas ordenadas.
  - Rotar lista.
  - Mover ceros al final.
  - Encontrar duplicados.
  - Producto máximo de sublista.
  - Fila de Pascal.
  - Combinar *k* listas ordenadas.
  - Subconjuntos.
  - Mayor rectángulo en histograma.

- 🔹 **Listas Enlazadas Simples (10 ejercicios):**
  - Invertir lista.
  - Detectar ciclo.
  - Encontrar intersección.
  - Eliminar duplicados.
  - N-ésimo desde el final.
  - Sumar números como listas.
  - Verificar palíndromo.
  - Rotar lista enlazada.
  - Eliminar nodos alternativos.
  - Punto de unión en Y.

- 🔹 **Listas Doblemente Enlazadas (5 ejercicios):**
  - LRU Cache.
  - Polinomio con lista doble.
  - Navegador web (historial).
  - Playlist de música.
  - Editor de texto con undo.

- 🔹 **Listas Circulares (5 ejercicios):**
  - Problema de Josephus.
  - Lista circular ordenada.
  - Dividir lista circular.
  - Verificar lista circular.
  - Rotar lista circular.

Cada ejercicio incluye:
- ✅ Enunciado  
- ✅ Código en Python  
- ✅ Ejemplo de uso / prueba  

---

## 📖 Guía Conceptual (HOW.MD)

El archivo `HOW.MD` explica de forma sencilla:

1. 🔍 **Qué es una IA generativa.**
2. 🧠 **Cómo entiende el lenguaje natural.**
3. 🌐 **Redes neuronales artificiales** (inspiradas en el cerebro).
4. 📐 **Matemáticas detrás de la IA**:
   - Álgebra lineal.
   - Cálculo.
   - Probabilidad.
   - Optimización.
5. 🧩 **Por qué puede resolver problemas difíciles.**
6. ✍️ **Qué es un prompt y por qué importa.**
7. ⚙️ **Cómo se conecta todo en el proyecto.**
8. ✅ **Conclusión**: la IA funciona porque combina ejemplos masivos + redes neuronales + optimización matemática.

---

## 🚀 Ejemplo de Uso

**Archivo `datos/problema1.txt`:**

```
Dado un grafo dirigido, implementa una función en Python que detecte si hay ciclos. Explica el algoritmo usado y su complejidad.
```

**Ejecución:**

```bash
python main.py
```

**Resultado esperado (consola):**

- Explicación del algoritmo (DFS / detección de ciclos).  
- Código en Python comentado.  
- Complejidad temporal y espacial.  

---

## ✅ Conclusión

Este proyecto es una integración entre:
- **Ejercicios clásicos de estructuras de datos y algoritmos.**
- **Automatización de resolución con IA (Gemini API).**

🔗 Ideal para estudiantes de programación, prácticas de algoritmos y experimentación con IA aplicada a la educación.

--------------------------------------------------------------------
# 📘 Ejercicios de Estructuras de Datos

Ejercicios de Estructuras de Datos
PILAS (10 ejercicios)
1. Balanceo de paréntesis
**Enunciado: Implementa una función que verifique si los paréntesis, corchetes y llaves en una expresión están correctamente balanceados.**

```python
def balanceo_parentesis(expresion):
pila = []
parejas = {')': '(', ']': '[', '}': '{'}
for caracter in expresion:
if caracter in '([{':
pila.append(caracter)
elif caracter in ')]}':
if not pila or pila[-1] != parejas[caracter]:
return False
pila.pop()
return len(pila) == 0
# Prueba
```python
print(balanceo_parentesis("({[]})"))  # True
```python
print(balanceo_parentesis("({[})"))   # False
2. Conversión infijo a postfijo
**Enunciado: Convierte una expresión matemática infija a notación postfija.**

```python
def infijo_a_postfijo(expresion):
precedencia = {'+': 1, '-': 1, '*': 2, '/': 2, '^': 3}
pila = []
salida = []
for token in expresion.split():
if token.isalnum():
salida.append(token)
elif token == '(':
pila.append(token)
elif token == ')':
while pila and pila[-1] != '(':
salida.append(pila.pop())
pila.pop()
else:
while (pila and pila[-1] != '(' and
precedencia.get(token, 0) <= precedencia.get(pila[-1], 0)):
salida.append(pila.pop())
pila.append(token)
while pila:
salida.append(pila.pop())
return ' '.join(salida)
# Prueba
```python
print(infijo_a_postfijo("( A + B ) * C"))  # A B + C *
3. Evaluar expresión postfija
**Enunciado: Evalúa una expresión matemática en notación postfija.**

```python
def evaluar_postfijo(expresion):
pila = []
for token in expresion.split():
if token.isdigit():
pila.append(int(token))
else:
b = pila.pop()
a = pila.pop()
if token == '+': pila.append(a + b)
elif token == '-': pila.append(a - b)
elif token == '*': pila.append(a * b)
elif token == '/': pila.append(a / b)
return pila[0]
# Prueba
```python
print(evaluar_postfijo("3 4 + 2 *"))  # 14
4. Invertir una lista usando pila
**Enunciado: Invierte una lista usando operaciones de pila.**

```python
def invertir_lista_pila(lista):
pila = []
# Push todos los elementos a la pila
for elemento in lista:
pila.append(elemento)
# Pop todos los elementos (saldrán en orden inverso)
lista_invertida = []
while pila:
lista_invertida.append(pila.pop())
return lista_invertida
# Prueba
```python
print(invertir_lista_pila([1, 2, 3, 4, 5]))  # [5, 4, 3, 2, 1]
5. Eliminar elementos consecutivos duplicados
**Enunciado: Elimina elementos duplicados consecutivos usando una pila.**

```python
def eliminar_consecutivos_duplicados(lista):
pila = []
for elemento in lista:
if not pila or pila[-1] != elemento:
pila.append(elemento)
return pila
# Prueba
```python
print(eliminar_consecutivos_duplicados([1, 2, 2, 3, 4, 4, 4, 5]))  # [1, 2, 3, 4, 5]
6. Siguiente elemento mayor
**Enunciado: Para cada elemento, encuentra el primer elemento mayor a su derecha.**

```python
def siguiente_elemento_mayor(lista):
pila = []
resultado = [-1] * len(lista)
for i in range(len(lista)):
while pila and lista[pila[-1]] < lista[i]:
idx = pila.pop()
resultado[idx] = lista[i]
pila.append(i)
return resultado
# Prueba
```python
print(siguiente_elemento_mayor([4, 5, 2, 10]))  # [5, 10, 10, -1]
7. Validar secuencia de push/pop
**Enunciado: Verifica si una secuencia es válida para operaciones push/pop.**

```python
def validar_secuencia_push_pop(push_seq, pop_seq):
pila = []
i = 0
for num in push_seq:
pila.append(num)
while pila and pila[-1] == pop_seq[i]:
pila.pop()
i += 1
return not pila
# Prueba
```python
print(validar_secuencia_push_pop([1, 2, 3, 4, 5], [4, 5, 3, 2, 1]))  # True
8. Pila con mínimo en O(1)
**Enunciado: Implementa una pila que devuelva el mínimo en tiempo constante.**

```python
class PilaConMinimo:
```python
def __init__(self):
self.pila_principal = []
self.pila_minimos = []
```python
def push(self, valor):
self.pila_principal.append(valor)
if not self.pila_minimos or valor <= self.pila_minimos[-1]:
self.pila_minimos.append(valor)
```python
def pop(self):
if not self.pila_principal:
return None
valor = self.pila_principal.pop()
if valor == self.pila_minimos[-1]:
self.pila_minimos.pop()
return valor
```python
def min(self):
return self.pila_minimos[-1] if self.pila_minimos else None
# Prueba
pila = PilaConMinimo()
pila.push(3)
pila.push(1)
pila.push(2)
```python
print(pila.min())  # 1
9. Dos pilas en un array
**Enunciado: Implementa dos pilas usando un solo array.**

```python
class DosPilas:
```python
def __init__(self, capacidad):
self.capacidad = capacidad
self.array = [None] * capacidad
self.top1 = -1
self.top2 = capacidad
```python
def push1(self, valor):
if self.top1 < self.top2 - 1:
self.top1 += 1
self.array[self.top1] = valor
else:
```python
print("Pila 1 llena")
```python
def push2(self, valor):
if self.top1 < self.top2 - 1:
self.top2 -= 1
self.array[self.top2] = valor
else:
```python
print("Pila 2 llena")
```python
def pop1(self):
if self.top1 >= 0:
valor = self.array[self.top1]
self.top1 -= 1
return valor
return None
```python
def pop2(self):
if self.top2 < self.capacidad:
valor = self.array[self.top2]
self.top2 += 1
return valor
return None
# Prueba
pilas = DosPilas(5)
pilas.push1(1)
pilas.push2(2)
```python
print(pilas.pop1())  # 1
10. Ordenar pila
**Enunciado: Ordena una pila usando solo operaciones de pila.**

```python
def ordenar_pila(pila):
pila_temp = []
while pila:
temp = pila.pop()
while pila_temp and pila_temp[-1] > temp:
pila.append(pila_temp.pop())
pila_temp.append(temp)
return pila_temp
# Prueba
pila = [3, 1, 4, 2]
```python
print(ordenar_pila(pila))  # [1, 2, 3, 4]
COLAS (10 ejercicios)
11. Implementar cola usando pilas
**Enunciado: Implementa una cola usando dos pilas.**

```python
class ColaConPilas:
```python
def __init__(self):
self.entrada = []
self.salida = []
```python
def enqueue(self, valor):
self.entrada.append(valor)
```python
def dequeue(self):
if not self.salida:
while self.entrada:
self.salida.append(self.entrada.pop())
return self.salida.pop() if self.salida else None
```python
def front(self):
if not self.salida:
while self.entrada:
self.salida.append(self.entrada.pop())
return self.salida[-1] if self.salida else None
# Prueba
cola = ColaConPilas()
cola.enqueue(1)
cola.enqueue(2)
```python
print(cola.dequeue())  # 1
12. Cola circular
**Enunciado: Implementa una cola circular con array de tamaño fijo.**

```python
class ColaCircular:
```python
def __init__(self, capacidad):
self.capacidad = capacidad
self.cola = [None] * capacidad
self.frente = 0
self.final = -1
self.tamaño = 0
```python
def enqueue(self, valor):
if self.tamaño == self.capacidad:
return False
self.final = (self.final + 1) % self.capacidad
self.cola[self.final] = valor
self.tamaño += 1
return True
```python
def dequeue(self):
if self.tamaño == 0:
return None
valor = self.cola[self.frente]
self.frente = (self.frente + 1) % self.capacidad
self.tamaño -= 1
return valor
```python
def front(self):
return self.cola[self.frente] if self.tamaño > 0 else None
# Prueba
cola = ColaCircular(3)
cola.enqueue(1)
cola.enqueue(2)
```python
print(cola.dequeue())  # 1
13. Revertir primeros k elementos
**Enunciado: Invierte los primeros k elementos de una cola.**

```python
def revertir_primeros_k(cola, k):
pila = []
# Sacar primeros k elementos a la pila
for _ in range(k):
pila.append(cola.dequeue())
# Devolver de la pila a la cola (invertidos)
while pila:
cola.enqueue(pila.pop())
# Mover los elementos restantes al final
for _ in range(len(cola) - k):
cola.enqueue(cola.dequeue())
return cola
# Prueba (asumiendo implementación básica de cola)
```python
class ColaSimple:
```python
def __init__(self):
self.elementos = []
```python
def enqueue(self, valor):
self.elementos.append(valor)
```python
def dequeue(self):
return self.elementos.pop(0) if self.elementos else None
```python
def __len__(self):
return len(self.elementos)
cola = ColaSimple()
for i in range(1, 6):
cola.enqueue(i)
revertir_primeros_k(cola, 3)
14. Generar números binarios
**Enunciado: Genera los primeros n números binarios usando una cola.**

```python
def generar_numeros_binarios(n):
if n <= 0:
return []
resultado = []
cola = []
cola.append("1")
for _ in range(n):
actual = cola.pop(0)
resultado.append(actual)
cola.append(actual + "0")
cola.append(actual + "1")
return resultado
# Prueba
```python
print(generar_numeros_binarios(5))  # ['1', '10', '11', '100', '101']
15. Cola de prioridad simple
**Enunciado: Implementa una cola de prioridad usando listas.**

```python
class ColaPrioridadSimple:
```python
def __init__(self):
self.elementos = []
```python
def enqueue(self, valor, prioridad):
self.elementos.append((valor, prioridad))
# Ordenar por prioridad (menor número = mayor prioridad)
self.elementos.sort(key=lambda x: x[1])
```python
def dequeue(self):
if not self.elementos:
return None
return self.elementos.pop(0)[0]
```python
def front(self):
return self.elementos[0][0] if self.elementos else None
# Prueba
cp = ColaPrioridadSimple()
cp.enqueue("tarea1", 2)
cp.enqueue("tarea2", 1)
```python
print(cp.dequeue())  # tarea2
16. Cola con dos stacks eficiente
**Enunciado: Implementa una cola eficiente usando dos stacks.**

```python
class ColaEficiente:
```python
def __init__(self):
self.stack_entrada = []
self.stack_salida = []
```python
def enqueue(self, valor):
self.stack_entrada.append(valor)
```python
def dequeue(self):
if not self.stack_salida:
self._transferir()
return self.stack_salida.pop() if self.stack_salida else None
```python
def _transferir(self):
while self.stack_entrada:
self.stack_salida.append(self.stack_entrada.pop())
```python
def front(self):
if not self.stack_salida:
self._transferir()
return self.stack_salida[-1] if self.stack_salida else None
# Prueba
cola = ColaEficiente()
cola.enqueue(1)
cola.enqueue(2)
```python
print(cola.dequeue())  # 1
17. Intercalar colas
**Enunciado: Intercala elementos de dos colas en una nueva cola.**

```python
def intercalar_colas(cola1, cola2):
resultado = []
while cola1 and cola2:
resultado.append(cola1.pop(0))
resultado.append(cola2.pop(0))
# Agregar elementos restantes
resultado.extend(cola1)
resultado.extend(cola2)
return resultado
# Prueba
```python
print(intercalar_colas([1, 3, 5], [2, 4, 6, 8]))  # [1, 2, 3, 4, 5, 6, 8]
18. Revertir cola recursivamente
**Enunciado: Revierte una cola usando recursión.**

```python
def revertir_cola_recursiva(cola):
if not cola:
return
# Sacar el frente
frente = cola.pop(0)
# Revertir el resto recursivamente
revertir_cola_recursiva(cola)
# Poner el frente al final
cola.append(frente)
# Prueba
cola = [1, 2, 3, 4, 5]
revertir_cola_recursiva(cola)
```python
print(cola)  # [5, 4, 3, 2, 1]
19. Problema del puente
**Enunciado: Simula el cruce de vehículos por un puente de capacidad limitada.**

```python
class Puente:
```python
def __init__(self, capacidad):
self.capacidad = capacidad
self.cola_entrada = []
self.puente = []
```python
def llegar_vehiculo(self, vehiculo):
if len(self.puente) < self.capacidad:
self.puente.append(vehiculo)
```python
print(f"{vehiculo} entra al puente")
else:
self.cola_entrada.append(vehiculo)
```python
print(f"{vehiculo} espera en cola")
```python
def salir_vehiculo(self):
if self.puente:
vehiculo = self.puente.pop(0)
```python
print(f"{vehiculo} sale del puente")
# Si hay vehículos esperando, dejar pasar uno
if self.cola_entrada:
siguiente = self.cola_entrada.pop(0)
self.puente.append(siguiente)
```python
print(f"{siguiente} entra al puente")
return vehiculo
# Prueba
puente = Puente(2)
puente.llegar_vehiculo("Auto1")
puente.llegar_vehiculo("Auto2")
puente.llegar_vehiculo("Auto3")
puente.salir_vehiculo()
20. Cola con máximo
**Enunciado: Implementa una cola que pueda devolver el elemento máximo en O(1).**

```python
from collections import deque
```python
class ColaConMaximo:
```python
def __init__(self):
self.cola_principal = deque()
self.cola_maximos = deque()
```python
def enqueue(self, valor):
self.cola_principal.append(valor)
# Mantener cola de máximos
while self.cola_maximos and self.cola_maximos[-1] < valor:
self.cola_maximos.pop()
self.cola_maximos.append(valor)
```python
def dequeue(self):
if not self.cola_principal:
return None
valor = self.cola_principal.popleft()
if valor == self.cola_maximos[0]:
self.cola_maximos.popleft()
return valor
```python
def max(self):
return self.cola_maximos[0] if self.cola_maximos else None
# Prueba
cola = ColaConMaximo()
cola.enqueue(3)
cola.enqueue(1)
cola.enqueue(2)
```python
print(cola.max())  # 3
LISTAS (10 ejercicios)
21. Intersección de listas ordenadas
**Enunciado: Encuentra la intersección de dos listas ordenadas.**

```python
def interseccion_listas_ordenadas(lista1, lista2):
i, j = 0, 0
resultado = []
while i < len(lista1) and j < len(lista2):
if lista1[i] == lista2[j]:
resultado.append(lista1[i])
i += 1
j += 1
elif lista1[i] < lista2[j]:
i += 1
else:
j += 1
return resultado
# Prueba
```python
print(interseccion_listas_ordenadas([1, 2, 3, 4], [2, 4, 6]))  # [2, 4]
22. Unión de listas ordenadas
**Enunciado: Encuentra la unión de dos listas ordenadas.**

```python
def union_listas_ordenadas(lista1, lista2):
i, j = 0, 0
resultado = []
while i < len(lista1) and j < len(lista2):
if lista1[i] < lista2[j]:
resultado.append(lista1[i])
i += 1
elif lista1[i] > lista2[j]:
resultado.append(lista2[j])
j += 1
else:
resultado.append(lista1[i])
i += 1
j += 1
# Agregar elementos restantes
resultado.extend(lista1[i:])
resultado.extend(lista2[j:])
return resultado
# Prueba
```python
print(union_listas_ordenadas([1, 2, 3], [2, 3, 4]))  # [1, 2, 3, 4]
23. Rotar lista
**Enunciado: Rota una lista k posiciones a la derecha.**

```python
def rotar_lista(lista, k):
if not lista:
return lista
k = k % len(lista)  # Manejar k mayor que longitud
return lista[-k:] + lista[:-k]
# Prueba
```python
print(rotar_lista([1, 2, 3, 4, 5], 2))  # [4, 5, 1, 2, 3]
24. Mover ceros al final
**Enunciado: Mueve todos los ceros al final manteniendo el orden relativo.**

```python
def mover_ceros_al_final(lista):
no_ceros = [x for x in lista if x != 0]
ceros = [0] * (len(lista) - len(no_ceros))
return no_ceros + ceros
# Versión in-place
```python
def mover_ceros_al_final_inplace(lista):
pos = 0
for i in range(len(lista)):
if lista[i] != 0:
lista[pos], lista[i] = lista[i], lista[pos]
pos += 1
# Prueba
lista = [0, 1, 0, 3, 12]
mover_ceros_al_final_inplace(lista)
```python
print(lista)  # [1, 3, 12, 0, 0]
25. Encontrar duplicados
**Enunciado: Encuentra todos los elementos duplicados en una lista.**

```python
def encontrar_duplicados(lista):
vistos = set()
duplicados = set()
for elemento in lista:
if elemento in vistos:
duplicados.add(elemento)
else:
vistos.add(elemento)
return list(duplicados)
# Prueba
```python
print(encontrar_duplicados([1, 2, 3, 2, 1, 4, 5]))  # [1, 2]
26. Producto máximo de sublista
**Enunciado: Encuentra el producto máximo de cualquier sublista contigua.**

```python
def producto_maximo_sublista(lista):
if not lista:
return 0
max_producto = lista[0]
min_producto = lista[0]
resultado = lista[0]
for i in range(1, len(lista)):
if lista[i] < 0:
max_producto, min_producto = min_producto, max_producto
max_producto = max(lista[i], max_producto * lista[i])
min_producto = min(lista[i], min_producto * lista[i])
resultado = max(resultado, max_producto)
return resultado
# Prueba
```python
print(producto_maximo_sublista([2, 3, -2, 4]))  # 6
27. Lista de Pascal
**Enunciado: Genera una fila del triángulo de Pascal.**

```python
def fila_triangulo_pascal(n):
if n == 0:
return [1]
fila_anterior = [1]
for i in range(1, n + 1):
fila_actual = [1]
for j in range(1, i):
fila_actual.append(fila_anterior[j-1] + fila_anterior[j])
fila_actual.append(1)
fila_anterior = fila_actual
return fila_anterior
# Prueba
```python
print(fila_triangulo_pascal(4))  # [1, 4, 6, 4, 1]
28. Combinar listas ordenadas
**Enunciado: Combina k listas ordenadas en una sola lista ordenada.**

```python
import heapq
```python
def combinar_listas_ordenadas(listas):
heap = []
resultado = []
# Insertar primer elemento de cada lista en el heap
for i, lista in enumerate(listas):
if lista:
heapq.heappush(heap, (lista[0], i, 0))
while heap:
valor, lista_idx, elem_idx = heapq.heappop(heap)
resultado.append(valor)
# Insertar siguiente elemento de la misma lista
if elem_idx + 1 < len(listas[lista_idx]):
siguiente_valor = listas[lista_idx][elem_idx + 1]
heapq.heappush(heap, (siguiente_valor, lista_idx, elem_idx + 1))
return resultado
# Prueba
```python
print(combinar_listas_ordenadas([[1, 4, 5], [1, 3, 4], [2, 6]]))  # [1, 1, 2, 3, 4, 4, 5, 6]
29. Subconjuntos
**Enunciado: Genera todos los subconjuntos posibles de una lista.**

```python
def generar_subconjuntos(lista):
resultado = [[]]
for elemento in lista:
nuevos_subconjuntos = []
for subconjunto in resultado:
nuevos_subconjuntos.append(subconjunto + [elemento])
resultado.extend(nuevos_subconjuntos)
return resultado
# Prueba
```python
print(generar_subconjuntos([1, 2, 3]))
# [[], [1], [2], [1, 2], [3], [1, 3], [2, 3], [1, 2, 3]]
30. Mayor rectángulo en histograma
**Enunciado: Encuentra el área del rectángulo más grande en un histograma.**

```python
def mayor_rectangulo_histograma(alturas):
pila = []
max_area = 0
i = 0
while i < len(alturas):
if not pila or alturas[i] >= alturas[pila[-1]]:
pila.append(i)
i += 1
else:
top = pila.pop()
ancho = i if not pila else i - pila[-1] - 1
area = alturas[top] * ancho
max_area = max(max_area, area)
while pila:
top = pila.pop()
ancho = i if not pila else len(alturas) - pila[-1] - 1
area = alturas[top] * ancho
max_area = max(max_area, area)
return max_area
# Prueba
```python
print(mayor_rectangulo_histograma([2, 1, 5, 6, 2, 3]))  # 10
LISTAS ENLAZADAS SIMPLES (10 ejercicios)
31. Invertir lista enlazada
**Enunciado: Invierte una lista enlazada simple.**

```python
class Nodo:
```python
def __init__(self, valor):
self.valor = valor
self.siguiente = None
```python
class ListaEnlazada:
```python
def __init__(self):
self.cabeza = None
```python
def agregar(self, valor):
nuevo = Nodo(valor)
if not self.cabeza:
self.cabeza = nuevo
else:
actual = self.cabeza
while actual.siguiente:
actual = actual.siguiente
actual.siguiente = nuevo
```python
def invertir(self):
anterior = None
actual = self.cabeza
while actual:
siguiente_temp = actual.siguiente
actual.siguiente = anterior
anterior = actual
actual = siguiente_temp
self.cabeza = anterior
```python
def imprimir(self):
actual = self.cabeza
while actual:
```python
print(actual.valor, end=" -> ")
actual = actual.siguiente
```python
print("None")
# Prueba
lista = ListaEnlazada()
for i in range(1, 6):
lista.agregar(i)
lista.invertir()
lista.imprimir()  # 5 -> 4 -> 3 -> 2 -> 1 -> None
32. Detectar ciclo
**Enunciado: Detecta si una lista enlazada tiene un ciclo.**

```python
def tiene_ciclo(lista):
if not lista.cabeza:
return False
lento = lista.cabeza
rapido = lista.cabeza
while rapido and rapido.siguiente:
lento = lento.siguiente
rapido = rapido.siguiente.siguiente
if lento == rapido:
return True
return False
# Prueba
lista_ciclica = ListaEnlazada()
nodo1 = Nodo(1)
nodo2 = Nodo(2)
nodo3 = Nodo(3)
nodo1.siguiente = nodo2
nodo2.siguiente = nodo3
nodo3.siguiente = nodo1  # Ciclo
lista_ciclica.cabeza = nodo1
```python
print(tiene_ciclo(lista_ciclica))  # True
33. Encontrar intersección
**Enunciado: Encuentra el nodo de intersección de dos listas enlazadas.**

```python
def encontrar_interseccion(lista1, lista2):
if not lista1.cabeza or not lista2.cabeza:
return None
# Calcular longitudes
len1, len2 = 0, 0
actual1, actual2 = lista1.cabeza, lista2.cabeza
while actual1:
len1 += 1
actual1 = actual1.siguiente
while actual2:
len2 += 1
actual2 = actual2.siguiente
# Avanzar la lista más larga
actual1, actual2 = lista1.cabeza, lista2.cabeza
if len1 > len2:
for _ in range(len1 - len2):
actual1 = actual1.siguiente
else:
for _ in range(len2 - len1):
actual2 = actual2.siguiente
# Encontrar intersección
while actual1 and actual2:
if actual1 == actual2:
return actual1
actual1 = actual1.siguiente
actual2 = actual2.siguiente
return None
34. Eliminar duplicados
**Enunciado: Elimina nodos duplicados de una lista enlazada ordenada.**

```python
def eliminar_duplicados_ordenada(lista):
if not lista.cabeza:
return
actual = lista.cabeza
while actual and actual.siguiente:
if actual.valor == actual.siguiente.valor:
actual.siguiente = actual.siguiente.siguiente
else:
actual = actual.siguiente
# Prueba
lista = ListaEnlazada()
for valor in [1, 1, 2, 3, 3, 4]:
lista.agregar(valor)
eliminar_duplicados_ordenada(lista)
lista.imprimir()  # 1 -> 2 -> 3 -> 4 -> None
35. N-ésimo nodo desde el final
**Enunciado: Encuentra el n-ésimo nodo desde el final de la lista.**

```python
def nesimo_desde_final(lista, n):
if not lista.cabeza or n <= 0:
return None
primero = lista.cabeza
segundo = lista.cabeza
# Avanzar primero n posiciones
for _ in range(n):
if not primero:
return None
primero = primero.siguiente
# Avanzar ambos hasta que primero llegue al final
while primero:
primero = primero.siguiente
segundo = segundo.siguiente
return segundo.valor if segundo else None
# Prueba
lista = ListaEnlazada()
for i in range(1, 6):
lista.agregar(i)
```python
print(nesimo_desde_final(lista, 2))  # 4
36. Suma de números como listas
**Enunciado: Suma dos números representados como listas enlazadas.**

```python
def sumar_listas_numeros(lista1, lista2):
```python
def lista_a_numero(lista):
num = 0
actual = lista.cabeza
while actual:
num = num * 10 + actual.valor
actual = actual.siguiente
return num
num1 = lista_a_numero(lista1)
num2 = lista_a_numero(lista2)
suma = num1 + num2
# Convertir resultado a lista enlazada
resultado = ListaEnlazada()
for digito in str(suma):
resultado.agregar(int(digito))
return resultado
# Prueba
lista1 = ListaEnlazada()
lista2 = ListaEnlazada()
for digito in [2, 4, 3]:
lista1.agregar(digito)
for digito in [5, 6, 4]:
lista2.agregar(digito)
resultado = sumar_listas_numeros(lista1, lista2)
resultado.imprimir()  # 8 -> 0 -> 7 -> None
37. Palíndromo en lista enlazada
**Enunciado: Verifica si una lista enlazada es palíndroma.**

```python
def es_palindromo(lista):
# Encontrar mitad usando técnica de tortuga y liebre
lento = lista.cabeza
rapido = lista.cabeza
pila = []
while rapido and rapido.siguiente:
pila.append(lento.valor)
lento = lento.siguiente
rapido = rapido.siguiente.siguiente
# Si la lista tiene longitud impar, saltar el elemento del medio
if rapido:
lento = lento.siguiente
# Comparar con la pila
while lento:
if lento.valor != pila.pop():
return False
lento = lento.siguiente
return True
# Prueba
lista_pal = ListaEnlazada()
for valor in [1, 2, 3, 2, 1]:
lista_pal.agregar(valor)
```python
print(es_palindromo(lista_pal))  # True
38. Rotar lista enlazada
**Enunciado: Rota una lista enlazada k posiciones a la derecha.**

```python
def rotar_lista_enlazada(lista, k):
if not lista.cabeza or k == 0:
return
# Calcular longitud
longitud = 0
actual = lista.cabeza
while actual:
longitud += 1
actual = actual.siguiente
k = k % longitud
if k == 0:
return
# Encontrar nuevo tail y nuevo head
actual = lista.cabeza
for _ in range(longitud - k - 1):
actual = actual.siguiente
nuevo_head = actual.siguiente
actual.siguiente = None
# Conectar el final con la cabeza original
tail = nuevo_head
while tail.siguiente:
tail = tail.siguiente
tail.siguiente = lista.cabeza
lista.cabeza = nuevo_head
# Prueba
lista = ListaEnlazada()
for i in range(1, 6):
lista.agregar(i)
rotar_lista_enlazada(lista, 2)
lista.imprimir()  # 4 -> 5 -> 1 -> 2 -> 3 -> None
39. Eliminar nodos alternativos
**Enunciado: Elimina cada segundo nodo de la lista enlazada.**

```python
def eliminar_nodos_alternativos(lista):
if not lista.cabeza:
return
actual = lista.cabeza
while actual and actual.siguiente:
actual.siguiente = actual.siguiente.siguiente
actual = actual.siguiente
# Prueba
lista = ListaEnlazada()
for i in range(1, 7):
lista.agregar(i)
eliminar_nodos_alternativos(lista)
lista.imprimir()  # 1 -> 3 -> 5 -> None
40. Punto de unión en Y
**Enunciado: Encuentra el punto donde dos listas se unen formando una Y.**

```python
def encontrar_punto_union(lista1, lista2):
```python
def obtener_longitud(lista):
longitud = 0
actual = lista.cabeza
while actual:
longitud += 1
actual = actual.siguiente
return longitud
len1 = obtener_longitud(lista1)
len2 = obtener_longitud(lista2)
actual1, actual2 = lista1.cabeza, lista2.cabeza
# Avanzar la lista más larga
if len1 > len2:
for _ in range(len1 - len2):
actual1 = actual1.siguiente
else:
for _ in range(len2 - len1):
actual2 = actual2.siguiente
# Encontrar punto de unión
while actual1 and actual2:
if actual1 == actual2:
return actual1
actual1 = actual1.siguiente
actual2 = actual2.siguiente
return None
LISTAS DOBLEMENTE ENLAZADAS (5 ejercicios)
41. Implementar LRU Cache
**Enunciado: Implementa un cache LRU usando lista doblemente enlazada y hash map.**

```python
class NodoDoble:
```python
def __init__(self, key, value):
self.key = key
self.value = value
self.siguiente = None
self.anterior = None
```python
class LRUCache:
```python
def __init__(self, capacidad):
self.capacidad = capacidad
self.cache = {}
self.head = NodoDoble(0, 0)
self.tail = NodoDoble(0, 0)
self.head.siguiente = self.tail
self.tail.anterior = self.head
```python
def _agregar_nodo(self, nodo):
# Agregar después de head
nodo.siguiente = self.head.siguiente
nodo.anterior = self.head
self.head.siguiente.anterior = nodo
self.head.siguiente = nodo
```python
def _remover_nodo(self, nodo):
anterior = nodo.anterior
siguiente = nodo.siguiente
anterior.siguiente = siguiente
siguiente.anterior = anterior
```python
def _mover_a_frente(self, nodo):
self._remover_nodo(nodo)
self._agregar_nodo(nodo)
```python
def get(self, key):
if key in self.cache:
nodo = self.cache[key]
self._mover_a_frente(nodo)
return nodo.value
return -1
```python
def put(self, key, value):
if key in self.cache:
nodo = self.cache[key]
nodo.value = value
self._mover_a_frente(nodo)
else:
if len(self.cache) >= self.capacidad:
# Remover el menos recientemente usado
lru = self.tail.anterior
self._remover_nodo(lru)
del self.cache[lru.key]
nuevo_nodo = NodoDoble(key, value)
self.cache[key] = nuevo_nodo
self._agregar_nodo(nuevo_nodo)
# Prueba
cache = LRUCache(2)
cache.put(1, 1)
cache.put(2, 2)
```python
print(cache.get(1))  # 1
cache.put(3, 3)
```python
print(cache.get(2))  # -1
42. Polinomio con lista doble
**Enunciado: Representa y suma polinomios usando listas doblemente enlazadas.**

```python
class Termino:
```python
def __init__(self, coeficiente, exponente):
self.coeficiente = coeficiente
self.exponente = exponente
self.siguiente = None
self.anterior = None
```python
class Polinomio:
```python
def __init__(self):
self.cabeza = None
```python
def agregar_termino(self, coeficiente, exponente):
nuevo = Termino(coeficiente, exponente)
if not self.cabeza:
self.cabeza = nuevo
else:
actual = self.cabeza
while actual.siguiente:
actual = actual.siguiente
actual.siguiente = nuevo
nuevo.anterior = actual
```python
def sumar(self, otro):
resultado = Polinomio()
actual1 = self.cabeza
actual2 = otro.cabeza
while actual1 and actual2:
if actual1.exponente == actual2.exponente:
suma_coef = actual1.coeficiente + actual2.coeficiente
if suma_coef != 0:
resultado.agregar_termino(suma_coef, actual1.exponente)
actual1 = actual1.siguiente
actual2 = actual2.siguiente
elif actual1.exponente > actual2.exponente:
resultado.agregar_termino(actual1.coeficiente, actual1.exponente)
actual1 = actual1.siguiente
else:
resultado.agregar_termino(actual2.coeficiente, actual2.exponente)
actual2 = actual2.siguiente
# Agregar términos restantes
while actual1:
resultado.agregar_termino(actual1.coeficiente, actual1.exponente)
actual1 = actual1.siguiente
while actual2:
resultado.agregar_termino(actual2.coeficiente, actual2.exponente)
actual2 = actual2.siguiente
return resultado
```python
def imprimir(self):
actual = self.cabeza
while actual:
```python
print(f"{actual.coeficiente}x^{actual.exponente}", end="")
if actual.siguiente:
```python
print(" + ", end="")
actual = actual.siguiente
```python
print()
# Prueba
p1 = Polinomio()
p1.agregar_termino(3, 2)
p1.agregar_termino(2, 1)
p1.agregar_termino(1, 0)
p2 = Polinomio()
p2.agregar_termino(2, 2)
p2.agregar_termino(1, 1)
resultado = p1.sumar(p2)
resultado.imprimir()  # 5x^2 + 3x^1 + 1x^0
43. Navegador web simple
**Enunciado: Simula las funciones adelante/atrás de un navegador web.**

```python
class NavegadorWeb:
```python
def __init__(self):
self.pagina_actual = None
self.historial_atras = []
self.historial_adelante = []
```python
def visitar_pagina(self, url):
if self.pagina_actual:
self.historial_atras.append(self.pagina_actual)
self.pagina_actual = url
self.historial_adelante.clear()
```python
print(f"Visitando: {url}")
```python
def atras(self):
if self.historial_atras:
self.historial_adelante.append(self.pagina_actual)
self.pagina_actual = self.historial_atras.pop()
```python
print(f"Yendo atrás a: {self.pagina_actual}")
else:
```python
print("No hay páginas anteriores")
```python
def adelante(self):
if self.historial_adelante:
self.historial_atras.append(self.pagina_actual)
self.pagina_actual = self.historial_adelante.pop()
```python
print(f"Yendo adelante a: {self.pagina_actual}")
else:
```python
print("No hay páginas siguientes")
```python
def pagina_actual(self):
return self.pagina_actual
# Prueba
navegador = NavegadorWeb()
navegador.visitar_pagina("google.com")
navegador.visitar_pagina("facebook.com")
navegador.atras()
navegador.adelante()
44. Playlist de música
**Enunciado: Implementa una playlist con funciones de next, previous, add, remove.**

```python
class Cancion:
```python
def __init__(self, titulo, artista):
self.titulo = titulo
self.artista = artista
self.siguiente = None
self.anterior = None
```python
class Playlist:
```python
def __init__(self):
self.cabeza = None
self.cola = None
self.actual = None
```python
def agregar_cancion(self, titulo, artista):
nueva = Cancion(titulo, artista)
if not self.cabeza:
self.cabeza = nueva
self.cola = nueva
self.actual = nueva
else:
self.cola.siguiente = nueva
nueva.anterior = self.cola
self.cola = nueva
```python
def reproducir_siguiente(self):
if self.actual and self.actual.siguiente:
self.actual = self.actual.siguiente
```python
print(f"Reproduciendo: {self.actual.titulo} - {self.actual.artista}")
else:
```python
print("No hay siguiente canción")
```python
def reproducir_anterior(self):
if self.actual and self.actual.anterior:
self.actual = self.actual.anterior
```python
print(f"Reproduciendo: {self.actual.titulo} - {self.actual.artista}")
else:
```python
print("No hay canción anterior")
```python
def eliminar_cancion_actual(self):
if not self.actual:
return
if self.actual.anterior:
self.actual.anterior.siguiente = self.actual.siguiente
else:
self.cabeza = self.actual.siguiente
if self.actual.siguiente:
self.actual.siguiente.anterior = self.actual.anterior
else:
self.cola = self.actual.anterior
siguiente = self.actual.siguiente if self.actual.siguiente else self.cabeza
self.actual = siguiente
```python
def mostrar_playlist(self):
actual = self.cabeza
while actual:
marcador = " [ACTUAL]" if actual == self.actual else ""
```python
print(f"{actual.titulo} - {actual.artista}{marcador}")
actual = actual.siguiente
# Prueba
playlist = Playlist()
playlist.agregar_cancion("Song1", "Artist1")
playlist.agregar_cancion("Song2", "Artist2")
playlist.agregar_cancion("Song3", "Artist3")
playlist.reproducir_siguiente()
playlist.mostrar_playlist()
45. Texto editor con undo
**Enunciado: Implementa un editor de texto simple con función deshacer.**

```python
class EstadoTexto:
```python
def __init__(self, texto):
self.texto = texto
self.siguiente = None
self.anterior = None
```python
class EditorTexto:
```python
def __init__(self):
self.estado_actual = EstadoTexto("")
self.max_historial = 10
self.contador_estados = 1
```python
def escribir(self, texto):
# Crear nuevo estado
nuevo_estado = EstadoTexto(self.estado_actual.texto + texto)
nuevo_estado.anterior = self.estado_actual
self.estado_actual.siguiente = nuevo_estado
self.estado_actual = nuevo_estado
# Limitar historial
self.contador_estados += 1
if self.contador_estados > self.max_historial:
# Eliminar el estado más antiguo
viejo = self.estado_actual
for _ in range(self.max_historial):
viejo = viejo.anterior
viejo.anterior = None
```python
def deshacer(self):
if self.estado_actual.anterior:
self.estado_actual = self.estado_actual.anterior
return True
return False
```python
def rehacer(self):
if self.estado_actual.siguiente:
self.estado_actual = self.estado_actual.siguiente
return True
return False
```python
def obtener_texto(self):
return self.estado_actual.texto
# Prueba
editor = EditorTexto()
editor.escribir("Hola ")
editor.escribir("Mundo")
```python
print(editor.obtener_texto())  # Hola Mundo
editor.deshacer()
```python
print(editor.obtener_texto())  # Hola
LISTAS CIRCULARES (5 ejercicios)
46. Problema de Josephus
**Enunciado: Resuelve el problema de Josephus usando lista circular.**

```python
class NodoCircular:
```python
def __init__(self, valor):
self.valor = valor
self.siguiente = None
```python
def problema_josephus(n, k):
if n == 1:
return 1
# Crear lista circular
cabeza = NodoCircular(1)
actual = cabeza
for i in range(2, n + 1):
actual.siguiente = NodoCircular(i)
actual = actual.siguiente
actual.siguiente = cabeza  # Hacer circular
# Encontrar posición segura
actual = cabeza
while actual.siguiente != actual:
# Saltar k-1 personas
for _ in range(k - 2):
actual = actual.siguiente
# Eliminar siguiente persona
actual.siguiente = actual.siguiente.siguiente
actual = actual.siguiente
return actual.valor
# Prueba
```python
print(problema_josephus(5, 2))  # 3
47. Lista circular ordenada
**Enunciado: Inserta elementos en una lista circular manteniéndola ordenada.**

```python
class ListaCircularOrdenada:
```python
def __init__(self):
self.cabeza = None
```python
def insertar_ordenado(self, valor):
nuevo = NodoCircular(valor)
# Caso 1: Lista vacía
if not self.cabeza:
self.cabeza = nuevo
nuevo.siguiente = nuevo
return
# Caso 2: Insertar antes de la cabeza
if valor < self.cabeza.valor:
# Encontrar cola
cola = self.cabeza
while cola.siguiente != self.cabeza:
cola = cola.siguiente
nuevo.siguiente = self.cabeza
cola.siguiente = nuevo
self.cabeza = nuevo
return
# Caso 3: Insertar en medio o al final
actual = self.cabeza
while actual.siguiente != self.cabeza and actual.siguiente.valor < valor:
actual = actual.siguiente
nuevo.siguiente = actual.siguiente
actual.siguiente = nuevo
```python
def imprimir(self):
if not self.cabeza:
return
actual = self.cabeza
while True:
```python
print(actual.valor, end=" -> ")
actual = actual.siguiente
if actual == self.cabeza:
break
```python
print("(cabeza)")
# Prueba
lista = ListaCircularOrdenada()
lista.insertar_ordenado(3)
lista.insertar_ordenado(1)
lista.insertar_ordenado(2)
lista.imprimir()  # 1 -> 2 -> 3 -> (cabeza)
48. Dividir lista circular
**Enunciado: Divide una lista circular en dos mitades iguales.**

```python
def dividir_lista_circular(lista):
if not lista.cabeza or lista.cabeza.siguiente == lista.cabeza:
return lista, None
# Encontrar punto medio con técnica de tortuga y liebre
tortuga = lista.cabeza
liebre = lista.cabeza
while liebre.siguiente != lista.cabeza and liebre.siguiente.siguiente != lista.cabeza:
tortuga = tortuga.siguiente
liebre = liebre.siguiente.siguiente
# Crear segunda lista
cabeza2 = tortuga.siguiente
tortuga.siguiente = lista.cabeza
# Hacer circular la segunda lista
actual = cabeza2
while actual.siguiente != lista.cabeza:
actual = actual.siguiente
actual.siguiente = cabeza2
# Crear nueva lista para la segunda mitad
lista2 = ListaCircularOrdenada()
lista2.cabeza = cabeza2
return lista, lista2
# Prueba
lista = ListaCircularOrdenada()
for i in range(1, 6):
lista.insertar_ordenado(i)
lista1, lista2 = dividir_lista_circular(lista)
lista1.imprimir()
lista2.imprimir()
49. Verificar lista circular
**Enunciado: Verifica si una lista enlazada es circular.**

```python
def es_lista_circular(lista):
if not lista.cabeza:
return False
tortuga = lista.cabeza
liebre = lista.cabeza
while liebre and liebre.siguiente:
tortuga = tortuga.siguiente
liebre = liebre.siguiente.siguiente
if tortuga == liebre:
return True
return False
# Prueba
lista_circular = ListaCircularOrdenada()
lista_circular.insertar_ordenado(1)
lista_circular.insertar_ordenado(2)
```python
print(es_lista_circular(lista_circular))  # True
50. Rotar lista circular
**Enunciado: Rota una lista circular k posiciones.**

```python
def rotar_lista_circular(lista, k):
if not lista.cabeza or k == 0:
return
# Encontrar longitud
longitud = 1
actual = lista.cabeza
while actual.siguiente != lista.cabeza:
longitud += 1
actual = actual.siguiente
k = k % longitud
if k == 0:
return
# Encontrar nueva cabeza
actual = lista.cabeza
for _ in range(longitud - k - 1):
actual = actual.siguiente
lista.cabeza = actual.siguiente
# Prueba
lista = ListaCircularOrdenada()
for i in range(1, 6):
lista.insertar_ordenado(i)
rotar_lista_circular(lista, 2)
lista.imprimir()
```
