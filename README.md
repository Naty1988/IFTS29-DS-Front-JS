# PFO3
Practica Formativa Obligatoria 3
Instrucciones
• La entrega debe hacerse subiendo a la plataforma el link de la app deployada. Basta con un simple index.html
que tenga asociado un archivo js como main.js .
• El index bastará con que tenga un par de etiquetas de encabezado con el nombre del alumno y debajo Práctica
Formativa Obligatoria 3.
• Los resultados deben mostrarse por consola, imprimiendo por consola Solucion X: y abajo la solucion mostrada
por consola. Se deben separar las soluciones con espacios y también poniendo separadores como /////////////// o
______________, separaciones y espacios que podremos poner en console.log() .
• En cada ejercicio tienen un ejemplo de la salida que debe producir. Por tanto deben incluír tres ejemplos en cada
función que hagan para demostrar que funciona con tres ejemplos distintos.
• Deben escribir en un comentario multilinea /* */ al término de su ejercicio, su proceso de pensamiento y cómo
abordaron ese ejercicio, es decir, escribir un par de párrafos acerca de cómo pensaron la consigna y cómo
idearon la solución.
1. Calcular el área de un rectángulo
Escribe una función que reciba la longitud y el ancho de un rectángulo y devuelva su área.
La funcion no debe devolver un console.log() sino retornar un valor, llamaremos a la funcion dentro de un
console.log() .
La idea de esto es comprender que algunas funciones retornan un valor y otras simplemente hacen otras cosas, como
imprimir un mensaje por consola. Las que retornan algo, deberán incluir la palabra clave return .
// Longitud = ancho x alto
console.log(calcularAreaRectangulo(5, 3)); // Resultado: 15
2. Contar palabras en una cadena
Escribe una función que reciba una cadena de texto (string) y devuelva la cantidad de palabras en la cadena.
console.log(contarPalabras("Humahuaca es un lugar copado")); // Resultado: 4
3. Invertir una cadena
Escribe una función que tome una cadena como parámetro y devuelva la cadena invertida.
console.log(invertirCadena("hola")); // Resultado: "aloh"
4. Encontrar el palíndromo
Escribe una función que reciba un string y devuelva true o false si el string es un palíndromo.
// Ejemplos, neuquen, reconocer, rallar
console.log(esPalindromo("neuquen")); // true
5. Crear un programa para convertir la edad de un perro a años humanos
Escribe una función que tome un valor de un usuario, utilizando una ventana emergente prompt y calcule la edad
canina, que equivale a 7 veces la edad humana.
Esta funcion no debe devolver un valor sino mostrar por consola un mensaje como el del ejemplo.
edadCanina(7); // Tu perro tiene 49 años humanos

