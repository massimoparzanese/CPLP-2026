## Pregunta

Tome uno o dos lenguajes de los que ud. Conozca y
- Describa los tipos de expresiones que se pueden escribir en él/ellos
- Describa las facilidades provistas para la organización del programa
- Indique cuáles de los atributos del ejercicio anterior posee el/los lenguaje/s elegidos y cuáles
no posee, justifique en cada caso.


## Respuesta


Lenguaje elegido: Java

### Tipos de expresiones que se pueden escribir en Java

En Java, una **expresión** es una combinación de variables, constantes, operadores y llamadas a métodos que se evalúa para producir un valor. Entre los principales tipos de expresiones se encuentran:

#### Expresiones aritméticas
Realizan operaciones matemáticas utilizando operadores como `+`, `-`, `*`, `/` y `%`.

Ejemplo:

```java
int resultado = a + b * 2;
```


#### Expresiones relacionales

Permiten comparar valores y producen un resultado booleano (true o false).
Utilizan operadores como ==, !=, <, >, <= y >=.

Ejemplo:
```Java
boolean mayor = edad >= 18;
Expresiones lógicas
```

Se utilizan para combinar condiciones booleanas mediante operadores como && (AND), || (OR) y ! (NOT).

Ejemplo:
```Java
boolean acceso = edad >= 18 && tieneDocumento;
```
#### Expresiones de asignación

Permiten asignar valores a variables mediante operadores como =, +=, -=, *=, /=.

Ejemplo:
```Java
x += 5;
```

#### Expresiones condicionales

Se realizan mediante el operador ternario ? :, que evalúa una condición y devuelve un valor según su resultado.

Ejemplo:

```Java
int mayor = (a > b) ? a : b;
```

#### Expresiones de invocación de métodos y creación de objetos

Ejemplo:

```Java
Persona p = new Persona();
int suma = calcular(a, b);

```
### Facilidades provistas para la organización del programa

Java ofrece diversas herramientas para organizar programas de manera estructurada.

#### Clases

El código se organiza principalmente en clases, que agrupan datos (atributos) y comportamientos (métodos).

#### Métodos

Permiten dividir el programa en subprogramas reutilizables, facilitando la modularidad y el mantenimiento del código.

#### Paquetes (packages)

Permiten organizar las clases en grupos o módulos, evitando conflictos de nombres y facilitando la organización de proyectos grandes.

Ejemplo de estructura conceptual:

com.empresa.proyecto
 ├── modelo
 ├── servicio
 └── controlador


#### Herencia e interfaces

Java permite reutilizar y organizar el código mediante mecanismos de programación orientada a objetos como:

- herencia (extends)

- interfaces (implements)


### Atributos que cumple y cuales no

A continuación se analizan algunos criterios utilizados para evaluar la calidad del diseño de un lenguaje de programación.

#### Simplicidad y legibilidad
Java posee buena legibilidad debido a su sintaxis estructurada y clara. El uso obligatorio de tipos, el formato similar a otros lenguajes de la familia C y la organización en clases facilitan la comprensión del código.

Sin embargo, **no es completamente simple**, ya que ciertos conceptos como la programación orientada a objetos, el manejo de excepciones y el uso de genéricos pueden aumentar la complejidad del lenguaje.

---

#### Claridad en los bindings
Java posee **claridad en los bindings**, ya que la asociación entre variables, tipos y valores se define principalmente en tiempo de compilación.  
Esto permite detectar errores antes de la ejecución y mejora la seguridad del programa.

---

#### Confiabilidad
Java es considerado un lenguaje confiable porque incluye:

- tipado fuerte
- verificación en tiempo de compilación
- manejo de excepciones
- recolección automática de memoria

Estas características reducen la probabilidad de errores comunes como accesos inválidos a memoria.

---

#### Soporte
Java posee **amplio soporte**, tanto por parte de herramientas de desarrollo, bibliotecas estándar, frameworks y una gran comunidad de desarrolladores.  
Esto facilita el mantenimiento, aprendizaje y desarrollo de aplicaciones.

---

#### Abstracción
Java ofrece buenos mecanismos de abstracción mediante:

- clases
- interfaces
- herencia
- encapsulamiento

Estos mecanismos permiten modelar problemas complejos de forma organizada y reutilizable.

---

#### Ortogonalidad
La ortogonalidad se refiere a que las diferentes características del lenguaje puedan combinarse de manera consistente.

Java **no es completamente ortogonal**, ya que existen ciertas restricciones o excepciones en el uso de algunas características. Por ejemplo, algunos tipos primitivos no pueden utilizarse directamente con colecciones sin utilizar clases envoltorio (wrappers), lo que rompe la uniformidad del lenguaje.

---

#### Eficiencia
Java no alcanza la misma eficiencia que lenguajes compilados directamente a código máquina como C o C++, ya que los programas se ejecutan sobre la máquina virtual de Java (JVM).

No obstante, el uso de compilación Just-In-Time y optimizaciones modernas permite que el rendimiento sea adecuado para la mayoría de aplicaciones.