## Variables

1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla
```python
>>> a1 = 27
>>> print(a1)
27
```

2) Imprimir el tipo de dato de la constante 8.5
```python
>>> a2 = type(8.5)
>>> print(a2)
<class 'float'>
```

3) Imprimir el tipo de dato de la variable creada en el punto 1
```python
>>> a3 = type(a1)
>>> print(a3)
<class 'int'>
```

4) Crear una variable que contenga tu nombre
```python
>>> Nombre = 'Alan Sánchez Díaz'
>>> print(Nombre)
Alan Sánchez Díaz
```

5) Crear una variable que contenga un número complejo
```python
>>> num_complex = 10 + 2j
>>> print(num_complex)
(10+2j)
```

6) Mostrar el tipo de dato de la variable crada en el punto 5
```python
>>> a6 = type(num_complex)
>>> print(a6)
<class 'complex'>
```

7) Crear una variable que contenga el valor del número Pi redondeado a 4 decimales
```python
>>> Pi = 3.1416
>>> print(Pi)
3.1416
```

8) Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?
```python
>>> VarStrVer = 'True'
>>> Ver = True
>>> print(VarStrVer)
>>> print(Ver)
>>> print('Son distintas cosas, ya que uno es un valor String y otro de tipo Boolean')
True
True
Son distintas cosas, ya que uno es un valor String y otro de tipo Boolean
```

9) Imprimir el tipo de dato correspondientes a las variables creadas en el punto 9
```python
>>> print('La variable 1 es de tipo ', type(VarStrVer), ' y la variable 2 es de tipo ', type(Ver))
La variable 1 es de tipo  <class 'str'>  y la variable 2 es de tipo  <class 'bool'>
```

10) Asignar a una variable, la suma de un número entero y otro decimal
```python
>>> a10 = 6 + 3.1416
>>> print(a10)
9.1416
```

11) Realizar una operación de suma de números complejos
```python
>>> a11 = 10 + 2j
>>> b11 = 5 + 1j
>>> print(a11 + b11)
(15+3j)
```

12) Realizar una operación de suma de un número real y otro complejo
```python
>>> a12 = 3.1416 + 15j
>>> print(a12)
(3.1416+15j)
```

13) Realizar una operación de multiplicación
```python
>>> a13 = 2 * 4
>>> print(a13)
8
```

14) Mostrar el resultado de elevar 2 a la octava potencia
```python
>>> a14 = (2**8)
>>> print(a14)
256
```

15) Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla
```python
>>> a15 = 27 / 4
>>> print(a15)
6.75
```

16) De la división anterior solamente mostrar la parte entera
```python
>>> a16 = 27 // 4
>>> print(a16)
6
```

17) De la división de 27 entre 4 mostrar solamente el resto
```python
>>> a17 = 27 % 4
>>> print(a17)
3
```

18) Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 16 y 17. Obtener 27 como resultado
```python
>>> a18 = (4 * 6) + 3
>>> print(a18)
27
```

19) Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas
```python
>>> vstring1 = 'Star '
>>> vstring2 = 'Craft 2'
>>> print(vstring1 + vstring2)
Star Craft 2
```

20) Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?
```python
>>> a20 = 2 == '2'
>>> print(a20)
>>> print('Son distintos tipos de valores')
False
Son distintos tipos de valores
```

21) Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 20 resulte verdadera
```python
>>> a21= 2 == int('2')
>>> print(a21)
>>> print('El tipo de valores son idénticos')
True
El tipo de valores son idénticos
```

22) ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8')
```python
>>> print('Porque el caracter "," no es correcto para los decimales en terminos matemáticos, tampoco valido para el lenguaje de programación')
>>> print('Lo correcto es lo siguiente:')
>>> print("a = float('3.8')")
>>> a22 = (float('3.8'))
>>> print(a22)
Porque el caracter "," no es correcto para los decimales en terminos matemáticos, tampoco valido para el lenguaje de programación
Lo correcto es lo siguiente:
a = float('3.8')
3.8
```

23) Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido
```python
>>> a23 = 3
>>> a23 -= 1
>>> print(a23)
2
```

24) Realizar la operacion 1 << 2 ¿Por qué da ese resultado? ¿Qué es el sistema de numeración binario?
```python
>>> a24 = 1 << 2
>>> print('Nos muestra ese resultado ya que realiza una operacion llamada Bitshift, en este caso a la izquierda; el numero 1 es representado por 1 en binario') 
>>> print('al realizar la operacion de bitshift a la izquierda, la operacion nos indica que debe recorrerse 2 valores a la izquierda dando lugar al 100') 
>>> print('el cual al ser convertido de binario a decimal da como resultado el numero 4.')
>>> print('Es un sistema de numeracion compuesto por 2 digitos el 1 y el 0; el cual es usado comunmente en el área informática.')
'1 << 2 = 4'
Nos muestra ese resultado ya que realiza una operacion llamada Bitshift, en este caso a la izquierda; el numero 1 es representado por 1 en binario
al realizar la operacion de bitshift a la izquierda, la operacion nos indica que debe recorrerse 2 valores a la izquierda dando lugar al 100
el cual al ser convertido de binario a decimal da como resultado el numero 4.
Es un sistema de numeracion compuesto por 2 digitos el 1 y el 0; el cual es usado comunmente en el área informática.
'1 << 2 = 4'
```

25) Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?
```python
>>> print('No esta permitida la operacion ya que no se puede sumar datos del tipo string e integer, mas si concatenar')
>>> print('Si los operandos son del mismo tipo el resultado dependerá del tipo de caracter, si son integer será una suma, si son string será una concatenación')
No esta permitida la operacion ya que no se puede sumar datos del tipo string e integer, mas si concatenar
Si los operandos son del mismo tipo el resultado dependerá del tipo de caracter, si son integer será una suma, si son string será una concatenación
```

26) Realizar una operación válida entre valores de tipo entero y string
```python
>>> Var261 = 'ABCDE '
>>> Var262 = 5
>>> a26 = Var261 * Var262
>>> print(a26)
>>> print ('Es un ejemplo de operacion entre 2 tipos de valores')
ABCDE ABCDE ABCDE ABCDE ABCDE 
Es un ejemplo de operacion entre 2 tipos de valores
```