## Consigna

Cite otras características importantes de javascript. Tipado de datos, excepciones,
variables, etc.

## Respuesta


### Otras características importantes de JavaScript


##### Tipado de datos

- Tipado dinámico: el tipo de una variable se determina en tiempo de ejecución.
- Tipado débil: permite conversiones implícitas entre tipos (coerción).


##### Variables

Se pueden declarar con var, let y const.
- let y const tienen alcance de bloque (block scope).
- var tiene alcance de función.


##### Excepciones

Manejo de errores mediante estructuras try, catch, finally.

Permite lanzar errores con throw.

Ejemplo:

```JavaScript
try {
  let x = 10 / 0;
} catch (e) {
  console.log("Error");
}
```


##### Funciones

Las funciones son ciudadanos de primera clase (se pueden asignar a variables, pasar como parámetros, retornar).

Soporta funciones anónimas y arrow functions.


##### Modelo de objetos

Basado en prototipos, no en clases tradicionales (aunque hoy existen clases sintácticas).


##### Asincronía

Soporte para programación asincrónica mediante:
- callbacks
- Promesas
- async/await

##### Organización del programa

Se organiza en archivos (scripts o módulos).

Permite modularización mediante import y export.

##### Entorno de ejecución

Puede ejecutarse en:

navegadores (frontend)

servidores (Node.js)