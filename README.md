# Ciclos en JavaScript: while, do while, for.
En este repositorio encontrarás ejemplos y explicaciones detalladas sobre los ciclos en JavaScript: while, do while y for.

## Ciclo while 🔄
El ciclo while se utiliza cuando queremos que un bloque de código se repita mientras una condición sea verdadera.

~~~~
let i = 1;
while (i <= 10) {
    console.log(`Iteración ${i}`);
    i++;
}
~~~~

### Características:
La condición se evalúa antes de ejecutar el bloque de código.
Puede no ejecutarse nunca si la condición inicialmente es falsa.


## **Ciclo do while** 🔄
El ciclo do while es similar al while, pero garantiza que el bloque de código se ejecute al menos una vez, ya que la condición se evalúa después de ejecutar el bloque.

~~~~
let i = 1;
do {
    console.log(`Iteración ${i}`);
    i++;
} while (i <= 10);
~~~~

### Características:
Asegura al menos una ejecución del bloque de código.
La condición se evalúa después de cada iteración.

## Ciclo for 🔄
El ciclo for es ideal cuando conocemos el número exacto de iteraciones que queremos realizar. Es una estructura compacta que incluye la inicialización, la condición y el incremento de la variable de control en una sola línea.

~~~~
for (let i = 1; i <= 10; i++) {
    console.log(`Iteración ${i}`);
}
~~~~

### Características:
Estructura controlada con una variable de control definida internamente.
Perfecto para iterar sobre arreglos y rangos predecibles.

## Ejercicio: Tabla de multiplicar del 10 📊
Como ejercicio práctico, se pide imprimir la tabla de multiplicar del 10 desde el número 1 hasta 50 utilizando cualquier ciclo de los mencionados.

~~~~
const base = 10;
const limite = 50;

for (let i = 1; i <= limite; i++) {
    console.log(`${base} x ${i} = ${base * i}`);
}
~~~~
Este ejercicio demuestra cómo aplicar los conceptos de ciclos para generar resultados repetitivos de manera estructurada.


