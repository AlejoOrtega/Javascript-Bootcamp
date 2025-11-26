# Tipos de variables
1) let - Variable reasignable - Forma mas comun de crear variables
2) const - Variable NO reasignable - Ideal para valores que NO deben cambiar

A la variable se le debe colocar un nombre y asignar un valor

## Como crear mi primera variable?
Para crear tu primera variable debes entender los conceptos de Declaracion, Inicializacion y Asignacion

__DECLARACION__ - Declarar una variable significa crear un espacio en la memoria para guardar un dato y darle un nombre para poder usarlo después.
```js
let nombre;
```

__INICIALIZACION__ - Inicializar una variable significar asignarle un valor inicial
```js
nombre = 'alex';
```

(!) Declarar e Inicializar una variable
```js
let nombre = 'alex'
```

__ASIGNACION__ - Asignarle un valor a una variable que ya tenia un valor
```js
let nombre = 'alex' (declarazion e inicializacion)
nombre = 'carlos' (asignacion)
```

## Realice los siguientes ejercicios
### Como debo entregar mis respuestas?
Crea un nuevo archivo dentro del modulo con tu nombre **tuNombre.js**. Ejemplo **alejandro.js**

### Usa console.log() para validar todas tus respuestas

1) Declara una variable de tipo *let* sin valor alguno

2) Declara una variable de tipo *let* e inicializalo con el texto *programador* en una sola linea

3) Declara una variable de tipo *const* e inicializalo con el texto *bootcamp*

4) Declara una variable de tipo *let* sin valor alguno y luego asiganle el texto *valorant*

5) Declara una variable de tipo *let* e inicializo con el texto *lolsito* y despues asignarle el texto *REPO*

6) Declara una variable que sea reasignable

7) Declara una variable que sea constante e inicializo con un valor

8) Declara una variable con texto *peso pluma* y despues cambiale el valor a la misma variable y colocale *peso pesado*

9) Declara una variable constante con el texto *sorpresa*. Declara una segunda variable e inicialo con la variable antes mencionada

10) Teniendo las siguentes variables
- let primero = 'papel'
- let segundo = 'tinta'

Busca la manera de intercambiar los valores entre las las variables.

### Preguntas de Analisis
Crea un nuevo archivo dentro del modulo con tu nombre **tuNombre.txt**. Ejemplo **alejandro.txt**

11) Que pasaria si despues de declarar e inicializar una variable constante, queremos asignarle otro valor?

12) Cuantas veces se puede reusar una variable reasignable?

13) Explica con tus palabras la diferencia entre declarar, inicializar y asignar.

14) Observa el siguiente código y explica qué está pasando en cada línea:
```js
let total;
total = 5;
total = total + 3;
```
¿Qué representa cada operación y por qué es válida?

15) Analiza este fragmento de código:
```js
let precio = 20;
precio = 20;
```
¿Hay alguna diferencia real entre inicializar y volver a asignar el mismo valor?

16) ¿Por qué const obliga a inicializar al momento de declararla?

17) Si una variable puede ser reasignada más adelante, ¿por qué sería mejor usar let en vez de var?

18) ¿Por qué este código falla?
```js
const edad;
console.log(edad);
```
