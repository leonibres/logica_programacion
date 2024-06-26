
#### Introducción a los Ciclos

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

### Características:
- La condición se evalúa antes de ejecutar el bloque de código.
- Puede no ejecutarse nunca si la condición inicialmente es falsa.
