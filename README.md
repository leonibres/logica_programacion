### Resumen de los 5 Videos sobre Ciclos en JavaScript

En estos videos se cubrieron los fundamentos y aplicaciones de los ciclos en JavaScript, enfocándose en los ciclos while, do while, y for, así como en ejercicios prácticos para reforzar estos conceptos.

---

#### Video 1: Introducción a los Ciclos

En este video se introdujo la necesidad y la estructura básica de los ciclos en programación. Se discutió cómo los ciclos permiten ejecutar bloques de código repetidamente mientras se cumpla una condición específica.

---

#### Video 2: Ciclo while

El ciclo while se presentó como una estructura que ejecuta un bloque de código mientras una condición sea verdadera. Se destacó la importancia de asegurar que la condición pueda cambiar dentro del ciclo para evitar bucles infinitos.

```javascript
let i = 1;
while (i <= 10) {
    console.log(`Iteración ${i}`);
    i++;
}


Características del ciclo while:
- La condición se evalúa antes de ejecutar el bloque de código.
- Puede no ejecutarse nunca si la condición inicialmente es falsa.

---

#### Video 3: Ciclo do while

Se exploró el ciclo do while, que garantiza al menos una ejecución del bloque de código antes de verificar la condición. Esto es útil en situaciones donde se necesita ejecutar el código al menos una vez sin importar la condición inicial.

```javascript
let i = 1;
do {
    console.log(`Iteración ${i}`);
    i++;
} while (i <= 10);


Características del ciclo do while:
- Asegura al menos una ejecución del bloque de código.
- La condición se evalúa después de cada iteración.

---

#### Video 4: Ciclo for

El ciclo for se presentó como una estructura compacta que incluye la inicialización, condición y actualización de la variable de control en una sola línea. Es ideal cuando se conoce el número exacto de iteraciones que se van a realizar.

```javascript
for (let i = 1; i <= 10; i++) {
    console.log(`Iteración ${i}`);
}

Características del ciclo for:
- Estructura controlada con una variable de control definida internamente.
- Perfecto para iterar sobre arreglos y rangos predecibles.

---

#### Video 5: Ejercicio Práctico: Tabla de Multiplicar del 10

Como ejercicio práctico, se pidió imprimir la tabla de multiplicar del 10 desde el número 1 hasta 50 utilizando los ciclos aprendidos. Esto demostró cómo aplicar los ciclos para generar resultados repetitivos de manera estructurada y eficiente.

Ejemplo del ejercicio práctico:

```javascript
const base = 10;
const limite = 50;

for (let i = 1; i <= limite; i++) {
    console.log(`${base} x ${i} = ${base * i}`);
}

