## 3. Básicos de Python

Esta sección te introduce a los tipos de variables y operadores fundamentales en Python.

### 3.1. Tipos de Variables

Las variables son contenedores que almacenan datos en tu programa. Python ofrece varios tipos de variables para diferentes tipos de datos:

- #### 3.1.1. Enteros (int)

Los enteros representan números enteros sin decimales, como 10, -5 o 0. 

```python
age = 25
quantity = -10
```

- #### 3.1.2. Flotantes (float)

Los flotantes representan números con decimales, como 3.14, -2.5 o 0.0.

```python
price = 19.99
temperature = -2.7
```

- #### 3.1.3. Cadenas (str)

Las cadenas almacenan texto entre comillas simples (' ') o dobles (" ").

```python
name = "Alice"
message = 'Hello, world!'
```

- #### 3.1.4. Booleanos (bool)

Los booleanos representan valores de verdad: `True` o `False`.

```python
is_logged_in = True
has_permission = False
```

### 3.2. Operadores

Los operadores permiten realizar operaciones con variables y valores.

- #### 3.2.1. Aritméticos

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

- #### 3.2.2. Comparación

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

- #### 3.2.3. Lógicos

Operadores para combinar condiciones:

* `and` (y)
* `or` (o)
* `not` (no)

```python
is_adult = age >= 18 and has_id
has_permission = is_admin or is_moderator
```