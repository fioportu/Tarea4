# Tarea Programada 4 - Números Pares, Impares, Primos

**Nombre:** Fiorella Portuguez Rojas  
**Carné:** FI22024660
**Repositorio:** [https://github.com/fioportu/Tarea4.git]


## Objetivo

Aplicar el uso de la biblioteca jQuery para manipular elementos HTML y trabajar con los conceptos matemáticos de:
- Números pares
- Números impares
- Números primos


## Enlaces Utilizados

- JQuery API: https://jquery.com/
- Node.js: https://nodejs.org/es
- Http-server npm: https://www.npmjs.com/
- Criba de Eratóstenes: https://study.com/academy/lesson/the-sieve-of-eratosthenes-lesson-quiz.html 

## Prompts Utilizados

**¿Cómo funciona `.append()` en jQuery?**

Respuesta:
Agrega contenido (texto, HTML o elementos) al final de un elemento seleccionado.
$("#lista").append("<li>Nuevo elemento</li>");

-----------------------------------------

**¿Cómo funciona `.toggleClass()` en jQuery?**

Respuesta:
Agrega o elimina una clase en un elemento dependiendo de si ya la tiene o no.
También acepta una condición booleana para forzar agregar o quitar.
$(".par").toggleClass("oculto", !checkbox.checked);

-----------------------------------------

**¿Qué hace `for (let i = 2; i * i <= 100; i++)`?**

Respuesta: 
Es una parte del algoritmo **Criba de Eratóstenes**.
Itera desde 2 hasta la raíz cuadrada de 100. Esto es eficiente porque no se necesita verificar más allá de la raíz cuadrada al buscar múltiplos.
for (let i = 2; i * i <= 100; i++) { ... }

-----------------------------------------

**¿Qué es `this.checked`?**

Respuesta: 
`this.checked` es una propiedad booleana de los inputs tipo checkbox.
Devuelve `true` si está activado, `false` si no.

if (this.checked) { ... }
