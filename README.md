# RETO_5

#1 Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```python
n=int(input ("escribe un numero"))
if n == 97 or n == 101 or n == 105 or n == 111 or n == 117 :
    print("el numero es un vocal vocal minuscula en ASCCI)
Else
    print("el numero NO es un vocal vocal minuscula en ASCCI)
```

#2 Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```python
A = input("Ingrese una cadena de carácteres: ")
numeros = ord(A)
if numeros%2 == 0:
 print ("La primera letra de la enteior cadena de caracteres corresponde al código ASCII de un número par")
else:
 print ("La primera letra de la anterior cadena de caracteres corresponde al código ASCII de un número impar")
```

#3 Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```python
A=input("Ingrese solo un carácter, SOLO UNO")
ord(A)
B=ord(A)
if B<=57 and B>=48:
    print("el carácter ",A," no es un dígito ")
else :
    print("el carácter ",A, " es un dígito ")
```
#4 Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma".

```python
A=float(input("ingrese un numero")
If A>0:
    print("el numero es positivo")
elif A<0:
    print("el numero es negativo")
Else:
    print("el numero es neutro")
```

#5Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```python
from math import sqrt
X1=float(input("Cordenada X del circulo"))
Y1=float(input("Cordenada Y del circulo"))
R=float(input("radio del circulo"))
X2=float(input("cordenada del eje X"))
Y2=float(input("cordenada del punto Y"))

if sqrt((X2-X1)**2+(Y2-Y1)**2) < R :
    print("la cordenada  (", X2,",",Y2,") esta dentro del circulo")
else:
    print("la cordenada  (", X2,",",Y2,") No esta dentro del circulo")
```

#6 Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```python
A=float(input("lado A"))
B=float(input("lado B"))
C=float(input("lado C"))
if A+B>C and A+C>B and C+B>A:
    print("se puede armar un triangulo")
else:
    print("no se puede armar un triangulo")
```
