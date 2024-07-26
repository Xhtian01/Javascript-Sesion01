# FUNDAMENTOS DE PROGRAMACIÓN

## QUE ES PROGRAMACIÓN

Es el proceso de crear instrucciones detalladas y organizadas para que una computadora realice tareas específicas.

## QUE ES UN LENGUAJE DE PROGRAMACIÓN

Es un conjunto de reglas y sintaxis que permiten a los programadores escribir código para comunicarse con computadoras para crear aplicaciones.

## TIPOS DE LENGUAJE DE PROGRAMACIÓN

- ### Lenguaje de Alto Nivel

  Son fáciles de leer y escribir para los humanos, y requieren traducción a lenguaje de máquina. Ejemplos: Python, Java, C++.

- ### Lenguajes de Bajo Nivel

  Se acercan más al lenguaje de máquina, con instrucciones específicas de hardware. Ejemplos: Ensamblador, C.

- ### Lenguajes Interpretados

  Se ejecutan mediante un intérprete, línea por línea. Ejemplos: JavaScript, Python, Ruby.

- ### Lenguajes Compilados

  Se convierten a código máquina mediante un compilador antes de ser ejecutados. Ejemplos: C, C++, Rust.

- ### Lenguajes de Propósito General

  Pueden ser usados para desarrollar una amplia variedad de aplicaciones. Ejemplos: Java, Python, C#.

- ### Lenguajes de Propósito Específico

  Diseñados para tareas específicas. Ejemplos: SQL (bases de datos), HTML (marcación de documentos web).

- ### Lenguajes de Programación Funcional

  Se basan en funciones matemáticas y evitan el estado y los efectos secundarios. Ejemplos: Haskell, Lisp, Erlang.

- ### Lenguajes Orientados a Objetos

  Se basan en objetos que encapsulan datos y comportamiento. Ejemplos: Java, C++, Python.

- ### Lenguajes de Script

  Utilizados principalmente para automatización y scripting. Ejemplos: JavaScript, Bash, Perl.

- ### Lenguajes Declarativos

  Se centran en el qué hacer más que en el cómo hacerlo. Ejemplos: SQL, HTML, Prolog.

## JAVASCRIPT

JavaScript es un lenguaje de programación utilizado para crear páginas web interactivas. Es interpretado, dinámico y se ejecuta del lado del cliente en los navegadores web, aunque también puede funcionar del lado del servidor con entornos como Node.js.  
JavaScript es conocido por su naturaleza basada en prototipos, permitiendo herencia y reutilización de código sin el uso de clases tradicionales. Su versatilidad y compatibilidad con estándares como HTML y CSS lo convierten en un componente esencial en el desarrollo web moderno.

### VARIABLES

- #### VAR

  Es una palabra clave en JavaScript utilizada para declarar variables. Las variables declaradas con 'var' pueden ser redeclaradas y actualizadas dentro de su ámbito. Actualmente no es recomendable usarla ya que pertenece a ES5.

  ```js
  var mensaje = 'Hola, mundo!';
  onsole.log(mensaje); // Imprime: Hola, mundo!

  var mensaje = 'Adiós, mundo!';
  console.log(mensaje); // Imprime: Adiós, mundo!
  ```

- #### LET

  #s una palabra clave en JavaScript usada para declarar variables con un alcance de bloque, es decir, que solo están disponibles dentro del bloque en el que se definen. A diferencia de 'var', 'let' no permite redeclarar la misma variable dentro del mismo bloque.

  ```js
  let mensaje = 'Hola, mundo!';
  console.log(mensaje); // Imprime: Hola, mundo!

  let nombre = 'adios'; // no se va a poder redeclarar la variable
  ```

- #### CONST

  Es una palabra clave en JavaScript utilizada para declarar variables cuyo valor no puede ser modificado una vez asignado. Las variables declaradas con const tienen un alcance de bloque, similar a let, y deben ser inicializadas al momento de la declaración.

  ```js
  const mensaje = 'Hola, mundo!';
  console.log(mensaje); // Imprime: Hola, mundo!
  ```

### TIPO DE DATO

- #### STRING

  Representa una secuencia de caracteres, como letras, números y símbolos, encerrados entre comillas simples, dobles o invertidas.

  - #### DECLARACIÓN

    ```js
    let saludo = 'Hola, mundo!';
    console.log(saludo); // Imprime: Hola, mundo!
    ```

  - #### CONCATENACIÓN
    ```js
    let nombre = 'Juan';
    let saludo = 'Hola, ' + nombre + '!';
    console.log(saludo); // Imprime: Hola, Juan!
    ```
  - #### TEMPLATE STRING
    ```js
    let nombre = 'Ana';
    let saludo = `Hola, ${nombre}!`;
    console.log(saludo); // Imprime: Hola, Ana!
    ```

### NOMBRAMIENTOS DE VARIABLES

- #### PASCALCASE

  ```js
  let MyVariableName = 'valor';
  ```

- #### CAMELCASE

  ```js
  let myVariableName = 'valor';
  ```

- #### UNDER-SCORE

  ```js
  my_variable_name = 'valor';
  ```
