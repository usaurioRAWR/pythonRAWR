## 4. Programación Orientada a Objetos (POO)

La programación orientada a objetos (POO) es un paradigma de programación que organiza el código alrededor de "objetos" que combinan datos (atributos) y funciones (métodos).


### 4.1. Clases y Objetos

- #### 4.1.1. Definición de clases

Una clase actúa como un plano o molde para crear objetos. Define las características (atributos) y comportamientos (métodos) que los objetos de esa clase compartirán.

```python
class Perro:  # Definición de una clase llamada 'Perro'
    def __init__(self, nombre, raza): # Método constructor 
        self.nombre = nombre
        self.raza = raza

    def ladrar(self):
        print("¡Guau!")
```

- #### 4.1.2. Instanciación de objetos

Crear un objeto a partir de una clase se llama instanciación. 

```python
mi_perro = Perro("Fido", "Pastor Alemán")  # Crea un objeto 'Perro' llamado mi_perro
print(mi_perro.nombre) # Output: Fido
mi_perro.ladrar() # Output: ¡Guau!
```

### 4.2. Herencia


La herencia permite crear nuevas clases (clases hijas) a partir de clases existentes (clases padre), heredando sus atributos y métodos.

- #### 4.2.1. Herencia única

Una clase hija hereda de una sola clase padre.

```python
class Animal: # Clase padre
    def __init__(self, nombre):
        self.nombre = nombre

    def hablar(self):
        print("Sonido genérico")

class Gato(Animal): # Clase hija que hereda de Animal
    def hablar(self):
        print("Miau!")

mi_gato = Gato("Mittens")
mi_gato.hablar() # Output: Miau!
```

- #### 4.2.2. Herencia múltiple

Una clase hija puede heredar de varias clases padre (menos común en Python).


### 4.3. Polimorfismo



El polimorfismo permite que objetos de diferentes clases respondan al mismo método de manera diferente.

- #### 4.3.1. Métodos sobrecargados

Definir múltiples métodos con el mismo nombre pero con diferentes parámetros. (Python no soporta sobrecarga de métodos en el sentido estricto).

- #### 4.3.2. Métodos sobrescritos

Una clase hija redefine un método heredado de la clase padre.

(Ejemplo mostrado en la herencia única)