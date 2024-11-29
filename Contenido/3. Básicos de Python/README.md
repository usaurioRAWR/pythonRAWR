## 3. Básicos de Python

Esta sección te introduce a los tipos de variables y operadores fundamentales en Python.

## 3.1. Tipos de Variables

En programación, una variable es como un contenedor que almacena información. Puedes pensar en ella como una caja etiquetada donde guardas datos para usarlos más adelante en tu programa.

Python ofrece varios tipos de variables, cada uno diseñado para almacenar un tipo específico de dato:

## 3.1.1. Enteros (int)

Los enteros son uno de los tipos de datos más básicos y fundamentales en programación. En Python, los enteros (**int**) representan números enteros, sin decimales.  

Piensa en ellos como los números que usas para contar objetos o expresar cantidades exactas:

* **Ejemplos:** 10, -5, 0, 1000, -25


### ¿Para qué sirven los enteros?

Los enteros son esenciales para muchas tareas en programación, como:

* **Conteo:**  
Mantener un registro de cuántas veces se ha ejecutado una acción.

* **Índices:**  
Acceder a elementos específicos dentro de listas o cadenas de texto.

* **Cálculos matemáticos básicos:** 
Suma, resta, multiplicación, división (siempre que el resultado sea un entero).


### Crear enteros en Python:

Es muy sencillo crear un entero en Python. Simplemente escribe el número sin decimales:

```python
edad = 25
cantidad_de_productos = 10
temperatura = -5
```

### Operaciones con enteros:

Python te permite realizar operaciones matemáticas básicas con enteros:

* **Suma:** `+`
* **Resta:** `-`
* **Multiplicación:** `*`
* **División (entera):** `/` (en Python 3, la división siempre devuelve un número decimal, incluso si los operandos son enteros. Para obtener la parte entera de la división, utiliza el operador `//`)

```python
resultado_suma = 5 + 10 # resultado_suma será 15
diferencia = 20 - 8  # diferencia será 12
producto = 3 * 7    # producto será 21
cociente = 15 // 4   # cociente será 3 (parte entera de la división)

```


### Algunas cosas importantes a recordar:



* **Rango:** Los enteros en Python no tienen un límite superior o inferior fijo. Pueden ser tan grandes como sea necesario para representar los datos que estés trabajando.
* **Tipo:** Para verificar si una variable es de tipo entero, puedes usar la función `type()`:

```python
print(type(edad)) # Output: <class 'int'>
```

## 3.1.2. Flotantes (float)

Los flotantes representan números con decimales, como 3.14, -2.5 o 0.0.

```python
price = 19.99
temperature = -2.7
```

## 3.1.3. Cadenas (str)

Las cadenas almacenan texto entre comillas simples (' ') o dobles (" ").

```python
name = "Alice"
message = 'Hello, world!'
```

## 3.1.4. Booleanos (bool)

Los booleanos representan valores de verdad: `True` o `False`.

```python
is_logged_in = True
has_permission = False
```

## 3.2. Operadores

Los operadores permiten realizar operaciones con variables y valores.

## 3.2.1. Aritméticos

Operadores para cálculos matemáticos:

* `+` (suma)
* `-` (resta)
* `*` (multiplicación)
* `/` (división)
* `//` (división entera)
* `%` (módulo - resto de la división)
* `**` (exponenciación)

```python
sum = 5 + 3
difference = 10 - 4
product = 2 * 6
```

## 3.2.2. Comparación

Operadores para comparar valores:

* `==` (igual a)
* `!=` (diferente a)
* `>` (mayor que)
* `<` (menor que)
* `>=` (mayor o igual que)
* `<=` (menor o igual que)

```python
is_equal = 5 == 5  # True
is_greater = 10 > 5 # True
```

## 3.2.3. Lógicos

Operadores para combinar condiciones:

* `and` (y)
* `or` (o)
* `not` (no)

```python
is_adult = age >= 18 and has_id
has_permission = is_admin or is_moderator
```
