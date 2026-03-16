## Consigna

Ejercicio 5: Describa las características más relevantes de Ada, referida a:
- Tipos de datos
- Tipos abstractos de datos – paquetes
- Estructuras de datos
- Manejo de excepciones
- Manejo de concurrencia

## Respuesta

- Tipos de datos:
    - Tipado estático fuerte: En ADA, cada variable debe ser 
    declarada con un tipo específico y este tipo no puede 
    cambiar durante la ejecución del programa. Esto ayuda a
    prevenir errores de tipo en tiempo de ejecución.
    - Tipos escalares: ADA soporta tipos de datos escalares como 
    enteros, reales, caracteres y booleanos. Los enteros pueden
    ser de tamaño fijo (por ejemplo, Integer) o de tamaño
    variable (por ejemplo, Integer_16, Integer_32, Integer_64). Los
    reales pueden ser de precisión simple (Float) o doble
    precisión (Long_Float).
    - Enumeraciones: ADA permite definir tipos enumerados,
    donde el programador puede especificar un conjunto finito
    de valores posibles para una variable.
    - Tipos derivados: Los tipos derivados permiten al
    programador crear nuevos tipos a partir de otros tipos
    existentes.
    - Arrays: ADA soporta arreglos multidimensionales de tamaño
    fijo y tamaño variable.
    - Registros (Records): Los registros en ADA son similares a las
    estructuras en otros lenguajes de programación.
    - Punteros: ADA permite el uso de punteros mediante el tipo
    Access, que se utiliza para referenciar datos dinámicamente
    asignados en el almacenamiento.
- Tipos abstractos de datos - paquetes:
    - Encapsulación: Los paquetes en ADA permiten encapsular
    datos y procedimientos relacionados en un único módulo.
    Esto promueve la modularidad y el ocultamiento de la 
    información, lo que facilita el mantenimiento y la
    reutilización del código.
    - Declaración y especificación: Un paquete en ADA consta de
    dos partes principales: la declaración del paquete en la
    especificación (archivo .ads) y la implementación del
    paquete en el cuerpo (archivo .adb). La especificación define
    la interfaz pública del paquete, incluyendo tipos, variables y
    procedimientos accesibles desde fuera del paquete.
    - Tipos privados: ADA permite la definición de tipos privados
    dentro de un paquete, lo que significa que los detalles
    internos de la implementación pueden ocultarse al usuario.
    - Procedimientos y funciones: Los paquetes en ADA pueden
    contener procedimientos y funciones que operan en los
    tipos definidos dentro del paquete. Estas subrutinas
    pueden ser públicas o privadas, según se especifique en la
    interfaz del paquete.
    - Variables privadas y constantes: Además de tipos,
    procedimientos y funciones, los paquetes pueden contener
    variables privadas y constantes que son accesibles sólo
    dentro del paquete.
    - Uso de renombramiento: ADA permite el uso de
    renombramiento dentro de los paquetes para proporcionar
    nombres alternativos para tipos, variables, procedimientos y
    funciones.
    - Especificación de la dependencia: Los paquetes en ADA
    pueden depender de otros paquetes, lo que significa que
    pueden utilizar tipos y subrutinas definidos en otros
    lugares.
- Estructuras de datos:
    - Arrays: ADA admite la creación de arreglos
    unidimensionales y multidimensionales con tamaño fijo o
    variable. Estos arreglos pueden contener elementos de
    cualquier tipo de datos válido en ADA, incluyendo tipos
    primitivos como enteros y caracteres, así como tipos
    compuestos como registros y otros arreglos.
    - Registros (Records): Los registros en ADA permiten agrupar
    diferentes tipos de datos relacionados bajo una única
    entidad. Cada campo del registro puede tener un tipo de
    datos distinto. Esto facilita la organización de datos
    complejos en una estructura coherente.
    - Listas enlazadas (Linked Lists): Aunque ADA no proporciona
    listas enlazadas como parte de su biblioteca estándar, es
    posible implementarlas utilizando punteros y registros. Las
    listas enlazadas son útiles para estructuras de datos
    dinámicas donde el tamaño puede cambiar durante la
    ejecución del programa.
- Manejo de excepciones:
    - Declaración de excepciones: En ADA, las excepciones se
    declaran en la especificación del paquete utilizando la
    cláusula “exception".
    - Razón y mensaje de excepción: Además de declarar
    excepciones, los programadores pueden proporcionar
    información adicional sobre la excepción, como una
    descripción o una razón para su ocurrencia. Esto facilita la
    depuración y el manejo de errores.
    - Rutinas de excepción: ADA proporciona la cláusula
    “exception” dentro de los bloques “declare” para manejar
    excepciones específicas que puedan ocurrir dentro de ese
    bloque. Las rutinas de excepción pueden incluir lógica para
    manejar el error, registrar información relevante y,
    opcionalmente, propagar la excepción.
    - Bloques de excepción anidados: Los bloques begin pueden
    estar anidados, lo que permite un manejo de excepciones
    más granular. Esto significa que se pueden manejar
    diferentes excepciones en diferentes niveles de anidamiento.
    - Propagación de excepciones: En ADA, las excepciones no
    manejadas dentro de un bloque son propagadas
    automáticamente al bloque superior para su manejo. Esto
    significa que las excepciones pueden ser manejadas en el
    nivel más apropiado de la jerarquía del programa.
    - Manejo global de excepciones: ADA permite definir un
    bloque exception global al final del programa para manejar
    excepciones no capturadas en ningún otro lugar.
- Manejo de concurrencia:
    - Procesos concurrentes: En ADA, los procesos concurrentes
    se definen mediante la creación de tareas (tasks) o procesos.
    Las tareas son unidades de ejecución independientes que
    pueden ejecutarse simultáneamente con otras tareas.
    - Declaración de tareas: Las tareas se declaran utilizando la
    palabra clave “task”.
    - Comunicación entre tareas: ADA proporciona mecanismos
    seguros para la comunicación entre tareas, como el uso de
    variables compartidas protegidas (protected objects) y colas
    de mensajes (message queues).
    - Sincronización de tareas: ADA permite la sincronización
    entre tareas mediante el uso de primitivas como semáforos
    (semaphores), exclusión mutua (mutexes) y barreras
    (barriers).
    - Planificación de tareas: ADA proporciona un planificador de
    tareas incorporado que se encarga de asignar tiempo de
    CPU a las diferentes tareas en ejecución.
    - Gestión de recursos compartidos: ADA facilita la gestión de
    recursos compartidos entre tareas mediante el uso de
    objetos protegidos