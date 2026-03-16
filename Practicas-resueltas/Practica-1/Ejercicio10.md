## Consigna

Describa el manejo de expresiones que brinda el lenguaje.​

## Respuesta


#### Manejo de expresiones en C

En C, una expresión es una combinación de variables, constantes, operadores y llamadas a funciones que produce un valor.

El lenguaje ofrece distintos tipos de expresiones.

##### Expresiones aritméticas

Permiten realizar operaciones matemáticas utilizando operadores como:

- + suma

- - resta

- * multiplicación

- / división

- % módulo

Ejemplo:

```C
int resultado = a + b * 2;
```


##### Expresiones relacionales

Se utilizan para comparar valores y devuelven un resultado booleano (0 o 1).

Operadores:

- ==

- !=

- <

- >

- <=

- >=

Ejemplo:
```C
int mayor = a > b;
```


##### Expresiones lógicas

Permiten combinar condiciones mediante operadores lógicos:

- && (AND)

- || (OR)

- ! (NOT)


Ejemplo:

```C
if (edad >= 18 && tieneDocumento) {
    printf("Acceso permitido");
}
```

##### Expresiones de asignación

Permiten asignar valores a variables.

Operadores comunes:

- =

- +=

- -=

- *=

- /=

Ejemplo:
```C
x += 5;
```

##### Expresiones condicionales

C permite utilizar el operador ternario ?:, que evalúa una condición y devuelve un valor dependiendo del resultado.

Ejemplo:

```C
int mayor = (a > b) ? a : b;
```

#### Reflexión

En general, el lenguaje C ofrece un manejo flexible de expresiones, permitiendo combinar operadores y operandos de diversas maneras, respetando reglas de precedencia y asociatividad que determinan el orden en que se evalúan.