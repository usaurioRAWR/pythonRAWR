## 3. Básicos de Python

Esta sección te introduce a los tipos de variables y operadores fundamentales en Python.

## 3.1. Tipos de Variables

En programación, una variable es como un contenedor que almacena información. Puedes pensar en ella como una caja etiquetada donde guardas datos para usarlos más adelante en tu programa.

Python ofrece varios tipos de variables, cada uno diseñado para almacenar un tipo específico de dato:

Para verificar el tipo de una variable, puedes usar la función `type()`:

```python
edad = 25
print(type(edad)) # Output: <class 'int'>
```
## 3.1.1. Enteros (int)

Los enteros son uno de los tipos de datos más básicos y fundamentales en programación. En Python, los enteros (**int**) representan números enteros, sin decimales. Una característica importante es que no tienen un límite superior o inferior fijo; pueden ser tan grandes como sea necesario para representar los datos que estés trabajando.

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

### Ejercicio;

```python
# Crea dos variables enteras
edad = 25
cantidad_de_manzanas = 10

# Imprime las variables en pantalla
print("Edad:", edad)
print("Cantidad de manzanas:", cantidad_de_manzanas)

# Terminal Output:
Edad: 25
Cantidad de manzanas: 10
```

## 3.1.2. Flotantes (float)

Los **flotantes**, también conocidos como *números de punto flotante* (**float**) en Python, son esenciales para representar números con decimales.  

Imagina que necesitas trabajar con cantidades más precisas, como precios, temperaturas o medidas científicas. Los flotantes te permiten almacenar estos valores con la precisión necesaria.

### ¿Para qué sirven los flotantes?

Los flotantes son útiles cuando:

* Necesitas representar **cantidades con decimales**.
* Realizas **cálculos que involucran números con partes fraccionarias**.

### Limitaciones de los Flotantes:

Es importante tener en cuenta que, aunque Python maneja los flotantes con gran precisión, estos tienen una representación finita en la memoria. Esto significa que solo pueden almacenar un número limitado de dígitos decimales.  

En la mayoría de los casos, esta limitación no será un problema. Sin embargo, si necesitas una precisión extrema para cálculos científicos o financieros, podrías considerar utilizar la biblioteca `decimal` de Python, que permite controlar la cantidad de dígitos decimales.

### Crear flotantes en Python:

Para crear un flotante, simplemente escribe el número incluyendo un punto decimal.

```python
precio = 19.99
altura = 1.75
pi = 3.14159 
```

### Ejercicio:


```python
# Crea dos variables flotantes
precio_cafe = 2.50
temperatura_ambiente = 25.5

# Imprime las variables en pantalla
print("Precio del café:", precio_cafe)
print("Temperatura ambiente:", temperatura_ambiente)

# Terminal Output:
Precio del café: 2.5
Temperatura ambiente: 25.5
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
