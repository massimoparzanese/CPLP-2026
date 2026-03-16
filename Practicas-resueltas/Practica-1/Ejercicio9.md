## Consigna

¿Cómo es la estructura de un programa escrito en C? ¿Existe anidamiento de
funciones?

## Respuesta


### ¿Cómo es la estructura de un programa escrito en C?

Un programa escrito en C suele tener una estructura compuesta por diferentes secciones. Aunque puede variar según el programa, generalmente incluye:

Directivas del preprocesador
- Se utilizan para incluir bibliotecas o definir constantes antes de la compilación.
```C
#include <stdio.h>
#define PI 3.14
```
Declaración de variables globales y prototipos de funciones
- En esta sección se pueden declarar variables que serán accesibles desde todo el programa y también los prototipos de funciones.

Función principal (main)
- Es el punto de entrada del programa. Todo programa en C debe tener una función main desde donde comienza la ejecución.
```C
int main() {
    printf("Hola mundo");
    return 0;
}
```



Definición de funciones
- Luego de la función main o antes de ella pueden definirse otras funciones que el programa utilizará.
```C
int sumar(int a, int b) {
    return a + b;
}
```


### ¿Existe anidamiento de funciones?

En el lenguaje C estándar, no existe anidamiento de funciones. Esto significa que no es posible definir una función dentro de otra función. Todas las funciones deben definirse a nivel global del programa.

Por ejemplo, lo siguiente no es válido en C:
```C
int main() {
    int suma(int a, int b) { // incorrecto en C
        return a + b;
    }
}
```
Las funciones deben declararse fuera de main o de cualquier otra función.