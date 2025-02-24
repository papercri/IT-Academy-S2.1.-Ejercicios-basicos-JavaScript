# Ejercicios de JavaScript

Este repositorio contiene una serie de ejercicios para practicar conceptos clave de JavaScript, como funciones de flecha, operador ternario, callbacks, operadores Rest y Spread, transformaciones de arrays, bucles y promesas.

## Requisitos
- Tener instalado [Node.js](https://nodejs.org/) para probar los ejercicios en un entorno local.
- Un editor de código como [VS Code](https://code.visualstudio.com/).

## Estructura del Repositorio
Cada conjunto de ejercicios está organizado en carpetas según el tema:

```
/js-exercises
  ├── 01-arrow-functions
  ├── 02-ternary-operator
  ├── 03-callbacks
  ├── 04-rest-spread
  ├── 05-array-transformations
  ├── 06-loops
  ├── 07-promises-async-await
```

Cada carpeta contiene un archivo `index.js` con los ejercicios a resolver.

## Cómo Usar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/js-exercises.git
   cd js-exercises
   ```
2. Navegar hasta la carpeta del ejercicio que deseas resolver:
   ```bash
   cd 01-arrow-functions
   ```
3. Ejecutar el archivo con Node.js:
   ```bash
   node index.js
   ```
4. Modificar el código en `index.js` para completar los ejercicios.

## Requisitos de Realización
Para completar estos ejercicios y recibir una calificación, es necesario resolver los ejercicios propuestos y subir la solución a un repositorio en GIT.

## Objetivos
- Comprender y practicar el uso de las funciones de flecha.
- Aprender y aplicar el operador ternario en distintos contextos.
- Entender y practicar con callbacks.
- Conocer y utilizar los operadores Rest y Spread.
- Familiarizarse con los bucles y transformaciones en arrays.

## Ejercicio 1.1: Arrow Functions

### Nivel 1
1. **Conversión de funciones:** Convertir la función `add` en una función de flecha.
2. **Función de flecha sin parámetros:** Crear una función `randomNumber` que devuelva un número aleatorio entre 0 y 100.
3. **Uso de `this` en funciones de flecha:** Crear una clase `Person` con una propiedad `name` y una función `greet` que use una función de flecha para imprimir un saludo con el nombre.

### Nivel 2
4. **Función de flecha dentro de un loop:** Crear la función `printNumbers` que imprima los números de un array con `for` y una función de flecha.

### Nivel 3
5. **Función de flecha con `setTimeout`:** Crear una función que imprima un mensaje después de 3 segundos.

---

## Ejercicio 1.2: Operador Ternario

### Nivel 1
1. **Operador ternario básico:** Crear la función `puedeConducir(edad)`.
2. **Uso con operadores de comparación:** Determinar el número mayor entre `num1` y `num2`.

### Nivel 2
3. **Uso enlazado de operadores ternarios:** Determinar si un número es positivo, negativo o cero.
4. **Operador ternario con funciones:** Crear `encontrarMaximo(a, b, c)` para hallar el máximo.

### Nivel 3
5. **Operador ternario en un bucle:** Funcíon `parOImpar` que recorra un array y determine si cada número es par o impar.

---

## Ejercicio 1.3: Callbacks

### Nivel 1
1. **Callback básico:** Función `procesar(num, callback)` que llama a `callback` con `num`.
2. **Callbacks con operaciones matemáticas:** Funcíon `calculadora(num1, num2, callback)`.

### Nivel 2
3. **Uso de callbacks en funciones asíncronas:** `esperarYSaludar(nombre, callback)`, espera 2 segundos y llama al `callback`.
4. **Callbacks con arrays:** `procesarElements(array, callback)`, llama `callback` por cada elemento.

### Nivel 3
5. **Procesar cadenas:** `procesarCadena(cadena, callback)`, convierte `cadena` a mayúsculas y llama al `callback`.

---

## Ejercicio 1.4: Rest & Spread Operators

### Nivel 1
1. **Spread en Arrays:** Combinar `array1` y `array2`.
2. **Rest en funciones:** Crear `suma(...numeros)` que devuelva la suma de todos los argumentos.

### Nivel 2
3. **Copiar objetos con Spread:** Crear `objeto2` basado en `objeto1` y modificarlo.
4. **Resto en Destructuring:** Asignar primeros dos elementos de un array a variables y el resto a otra variable.

### Nivel 3
5. **Spread en funciones:** Llamar una función con un array usando Spread.
6. **Fusionar objetos con Spread:** Combinar dos objetos en uno solo.

---

## Ejercicio 1.5: Transformaciones de Arrays

### Nivel 1
1. **Map:** Crear un array con los cuadrados de `[1, 2, 3, 4]`.
2. **Filter:** Filtrar números pares en `[1, 2, 3, 4]`.
3. **Find:** Encontrar el primer número mayor a 10 en `[1, 10, 8, 11]`.
4. **Reduce:** Sumar los números en `[13, 7, 8, 21]`.

### Nivel 2
5. **Filtrado, multiplicación y reducción en una línea:** Operaciones encadenadas en `[1, 3, 7, 10, 15, 17, 11, 5, 8, 12, 9]`.

### Nivel 3
6. **Every / Some:** Verificar si todos o algunos números en `[11, 12, 13, 14]` son mayores que 10.

---

## Ejercicio 1.6: Bucles en Arrays

### Nivel 1
1. **forEach:** Imprimir nombres en consola.
2. **for-of:** Recorrer un array de nombres.
3. **Filter:** Filtrar números pares en un array.

### Nivel 2
4. **for-in:** Recorrer claves y valores de un objeto.
5. **for-of con break:** Detener el bucle al encontrar el número 5.

### Nivel 3
6. **for-of con índice:** Imprimir cada elemento y su posición en un array.

---

## Ejercicio 1.7: Promesas y Async/Await

### Nivel 1
1. **Creación de una promesa:** Resolver una promesa en 2 segundos con el mensaje "Hola, mundo".
2. **Utilización de una promesa:** Usar `.then()` para imprimir el resultado.
3. **Promesa con reject:** Resolver si la entrada es "Hola", rechazar en otros casos.
4. **Uso de async/await:** Crear una función asíncrona que use `await` para esperar el resultado de la promesa.

### Nivel 2
5. **Gestón de errores con async/await:** Capturar errores usando `try/catch`.

### Nivel 3
6. **Promise.all:** Crear dos promesas con tiempos distintos y esperar ambas con `Promise.all()`.

---

## Entrega
Subir la solución al **repositorio GIT** y compartir el enlace para su evaluación.

