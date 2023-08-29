/*⚠️ NO MODIFIQUES EL NOMBRE DE LAS DECLARACIONES ⚠️*/
/*1️⃣ EJERCICIO 01 1️⃣*/

// En los siguientes ejercicios deberás reemplazar el valor null
// por el correspondiente.

// Crea una variable de tipo string.
const nuevoString = "string de prueba"

// Crea una variable de tipo number.
const nuevoNumero = 34;

// Crea una variable de tipo boolean.
const nuevoBoolean = true;

// Resuelve el siguiente problema matemático.
const nuevaResta = 10 - 7 === 3;

// Resuelve el siguiente problema matemático.
const nuevaMultiplicacion = 10 * 4 === 40;

// Resuelve el siguiente problema matemático.
const nuevoModulo = 21 % 5 === 1;

/*⚠️ NO MODIFIQUES NADA DEBAJO DE ESTO ⚠️*/
module.exports = {
   nuevoString,
   nuevoNumero,
   nuevoBoolean,
   nuevaResta,
   nuevaMultiplicacion,
   nuevoModulo,
};


/*⚠️ NO MODIFIQUES EL NOMBRE DE LAS DECLARACIONES ⚠️*/
/*2️⃣ EJERCICIO 02 2️⃣*/

function devolverString(string) {
    // Debe retornar un string.
    // Tu código:
    return string;
 }
 
 // ⛔️ "X" e "Y" son números.
 
 function suma(x, y) {
    // Retorna el resultado de su suma.
    // Tu código:
    return x + y;
 }
 
 function resta(x, y) {
    // Retorna el resultado de la resta.
    // Tu código:
    return x - y;
 }
 
 function divide(x, y) {
    // Retorna el resultado de su división.
    // Tu código:
    return x / y;
 }
 
 function multiplica(x, y) {
    // Retorna el resultado de su multiplicación.
    // Tu código:
    return x * y;
 }
 
 function obtenerResto(x, y) {
    // Obten el resto de la división de "x" entre "y".
    // Tu código:
    return x % y;
 }
 
 /*⚠️ NO MODIFIQUES NADA DEBAJO DE ESTO ⚠️*/
 module.exports = {
    devolverString,
    suma,
    resta,
    divide,
    multiplica,
    obtenerResto,
 };




 /*⚠️ NO MODIFIQUES EL NOMBRE DE LAS DECLARACIONES ⚠️*/
/*3️⃣ EJERCICIO 03 3️⃣*/

function sonIguales(x, y) {
    // Retorna true si "x" e "y" son iguales.
    // De lo contrario, retorna false.
    // Tu código:
    if (x === y){
       return true;
    } else{
       return false;
    }
 }
 
 function tienenMismaLongitud(str1, str2) {
    // Retorna true si los dos strings tienen la misma longitud.
    // De lo contrario, retorna false.
    // Tu código:
    if (str1.length === str2.length){
       return true;
    } else {
       return false
    }
    
    
 }
 
 function menosQueNoventa(num) {
    // Retorna true si el argumento "num" es menor que noventa.
    // De lo contrario, retorna false.
    // Tu código:
    if ( num < 90){
       return true;
    }else return false;
 }
 
 function mayorQueCincuenta(num) {
    // Retorna true si el argumento "num" es mayor que cincuenta.
    // De lo contrario, retorna false.
    // Tu código:
    if ( num > 50){
       return true;
    } else {
       return false;
    }
 }
 
 function esPar(num) {
    // Retorna true si "num" es par.
    // De lo contrario, retorna false.
    // Tu código:
    if (num % 2 === 0){
       return true;
    } else{
       return false;
    }
 }
 
 function esImpar(num) {
    // Retorna true si "num" es impar.
    // De lo contrario, retorna false.
    // Tu código:
    if ( num % 2 != 0){
       return true;
    } else{
       return false;
    }
 }
 
 /*⚠️ NO MODIFIQUES NADA DEBAJO DE ESTO ⚠️*/
 module.exports = {
    tienenMismaLongitud,
    sonIguales,
    menosQueNoventa,
    mayorQueCincuenta,
    esPar,
    esImpar,
 };

 


 /*⚠️ NO MODIFIQUES EL NOMBRE DE LAS DECLARACIONES ⚠️*/
/*4️⃣ EJERCICIO 04 4️⃣*/

// ⛔️ Recuerda que debes utilizar el objeto global "Math".

function elevarAlCuadrado(num) {
    // Retorna el valor de "num" elevado al cuadrado.
    // Tu código:
    return Math.pow(num,2);
 }
 
 function elevarAlCubo(num) {
    // Retorna el valor de "num" elevado al cubo.
    // Tu código:
    return Math.pow(num,3);
 }
 
 function elevar(num, exponent) {
    // Retorna el valor de "num" elevado al exponente "exponent".
    // Tu código:
    return Math.pow(num,exponent);
 }
 
 function redondearNumero(num) {
    // Redondea "num" al entero más próximo y retórnalo.
    // Tu código:
    return Math.round(num);
 }
 
 function redondearHaciaArriba(num) {
    // Redondea "num" hacia arriba y retórnalo.
    // Tu código:
       return Math.ceil(num);
 }
 
 function numeroRandom() {
    // Genera un número al azar entre 0 y 1 y retórnalo.
    // Tu código:
    return Math.random();
 }
 
 /*⚠️ NO MODIFIQUES NADA DEBAJO DE ESTO ⚠️*/
 module.exports = {
    elevarAlCuadrado,
    elevarAlCubo,
    elevar,
    redondearNumero,
    redondearHaciaArriba,
    numeroRandom,
 };


 /*⚠️ NO MODIFIQUES EL NOMBRE DE LAS DECLARACIONES ⚠️*/
/*5️⃣ EJERCICIO 05 5️⃣*/

function esPositivo(num) {
    // La función recibe un entero. Devuelve como resultado un string que indica si el número
    // es positivo o negativo.
    // Si el número es positivo ---> "Es positivo".
    // Si el número es negativo ---> "Es negativo".
    // Si el número es 0, devuelve false.
    // Tu código:
    if (num > 0){
       return("Es positivo");
    } else if (num < 0){
       return("Es negativo");
    }else{
       return false;
    }
 }
 
 function agregarSimboloExclamacion(str) {
    // Agrega un símbolo de exclamación al final del string "str" y retórnalo
    // Ejemplo: "hello world" ---> "hello world!"
    // Tu código:
    completo = str + "!";
    return completo
 }
 
 function combinarNombres(nombre, apellido) {
    // Retorna "nombre" y "apellido" combinados en un mismo string pero separados por un espacio.
    // Ejemplo: ("Soy", "Henry") ---> "Soy Henry"
    // Tu código:
    return nombre + " " + apellido;
 }
 
 function obtenerSaludo(nombre) {
    // Toma el string "nombre" y concatena otra string en la cadena para que tome la siguiente forma:
    // Ejemplo: "Martin" ---> "Hola Martin!"
    // Tu código:
    str1 = "Hola"
    return str1 + " " + nombre + "!";
 }
 
 function obtenerAreaRectangulo(alto, ancho) {
    // Retornar el área de un rectángulo teniendo su altura y ancho.
    // Tu código:
    area = (alto * ancho)
    return area;
 }
 
 function retornarPerimetro(lado) {
    // La función recibe como argumento la medida de un lado de un cuadrado.
    // Debes retornar su perímetro.
    // Tu código:
    area = lado * 4
    return area;  
 }
 
 function areaDelTriangulo(base, altura) {
    // Calcula el área de un triángulo y retorna el resultado.
    // Tu código:
    area = (base * altura) / 2
    return area;
 }
 
 function deEuroAdolar(euro) {
    // Supongamos que 1 euro equivale a 1.20 dólares.
    // Debes calcular el valor recibido como argumento pasándolo a dolares.
    // Tu código:
    valorDolar = euro * 1.2
    return valorDolar;
 }
 
 function esVocal(letra) {
    // Escribe una función que reciba una letra y, si es una vocal, muestre el mensaje “Es vocal”.
    // Si el usuario ingresa un string de más de un caracter debes retornar el mensaje: "Dato incorrecto".
    // Si no es vocal, tambien debe retornar "Dato incorrecto".
    // Tu código:
    var vocal = ["a","e","i","o","u"]
 
    if (letra.lenght >1){
       return ("Dato incorrecto")
    }else if (vocal.includes(letra)){
       return("Es vocal")
    } else {
       return ("Dato incorrecto")
    }
    
 
   
    
 }
 
 /*⚠️ NO MODIFIQUES NADA DEBAJO DE ESTO ⚠️*/
 module.exports = {
    esPositivo,
    agregarSimboloExclamacion,
    combinarNombres,
    obtenerSaludo,
    obtenerAreaRectangulo,
    retornarPerimetro,
    areaDelTriangulo,
    deEuroAdolar,
    esVocal,
 };

 

 /*⚠️ NO MODIFIQUES EL NOMBRE DE LAS DECLARACIONES ⚠️*/

function obtenerMayor(x, y) {
    // "x" e "y" son números enteros.
    // Retornar el número más grande.
    // Si son iguales, retornar cualquiera de los dos.
    // Tu código:
    numeroMax = Math.max(x,y)
    if (x === y){
       return x
    } else return numeroMax
 }
 
 function mayoriaDeEdad(edad) {
    // Determinar si la persona puede ingresar al evento según su edad.
    // Si tiene 18 años ó más debe retornar el string: "Allowed".
    // Caso contrario: "Not allowed".
    // Tu código:
    if (edad >= 18){
       return ("Allowed")
       } else return ("Not allowed")
    
 }
 
 function conection(status) {
    // El argumento "status" representa el estado de conexión de un usuario.
    // Si el estado es igual a 1, el usuario está "Online".
    // Si el estado es igual a 2, el usuario está "Away".
    // De lo contrario, presumimos que el usuario está "Offline".
    // Retornar el estado de conexión del usuario.
    // Tu código:
    if (status === 1){
       return ("Online")
       }else if (status ===2){
          return ("Away")
       } else return ("Offline")
    
 }
 
 function saludo(idioma) {
    // Retornar un saludo en tres diferentes lenguajes:
    // Si "idioma" es "aleman", devuelve "Guten Tag!".
    // Si "idioma" es "mandarin", devuelve "Ni Hao!".
    // Si "idioma" es "ingles", devuelve "Hello!".
    // Si "idioma" no es ninguno de los anteriores o es `undefined` devuelve "Hola!".
    // Tu código:
    if (idioma === "aleman"){
       return ("Guten Tag!")
    }else if (idioma ==="mandarin"){
       return ("Ni Hao!")
    }else if (idioma === "ingles"){
       return ("Hello!")
    } else return ("Hola!")
 }
 
 function colors(color) {
    // La función recibe un color. Retornar el string correspondiente:
    // En caso que el color recibido sea "blue"   --> "This is blue".
    // En caso que el color recibido sea "red"    --> "This is red".
    // En caso que el color recibido sea "green"  --> "This is green".
    // En caso que el color recibido sea "orange" --> "This is orange".
    // Si no es ninguno de esos colores           --> "Color not found".
    // IMPORTANTE: utilizar el statement SWITCH.
    // Tu código:
    var color 
    switch (color){
 
       case "blue":
          return("This is blue");
       case "red":
          return("This is red");
       case "green":
          return ("This is green");        
       case "orange":
          return ("This is orange");      
       default:
          return("Color not found");
    }
 }
 
 function esDiezOCinco(num) {
    // Retornar true si "num" es 10 o 5.
    // De lo contrario, retornar false.
    // Tu código:
    if (num === 10 || num === 5){
       return true;
    } else return false;
 }
 
 function estaEnRango(num) {
    // Retornar true si "num" es menor que 50 y mayor que 20.
    // De lo contrario, retornar false.
    // Tu código:
    if (num >20 && num <50){
       return true;
    }else return false;
 }
 
 function esEntero(num) {
    // Retornar true si "num" es un entero, ya sea positivo, negativo o cero.
    // Ejemplo: 0.8   ---> false
    // Ejemplo: 1     ---> true
    // Ejemplo: (-10) ---> true
    // De lo contrario, retorna false.
    // Tu código:
    return Number.isInteger(num);
 }
 
 function fizzBuzz(num) {
    // Si "num" es divisible entre 3, retorna "fizz".
    // Si "num" es divisible entre 5, retorna "buzz".
    // Si "num" es divisible entre 3 y 5 (ambos), retorna "fizzbuzz".
    // De lo contrario, retorna false.
    // Tu código:
    if (num % 3 === 0 && num % 5 === 0){
       return("fizzbuzz");
    }else if (num % 3 === 0){
       return ("fizz");
    }else if (num % 5 === 0){
       return("buzz");
    }else return false;
    
 }
 
 function operadoresLogicos(num1, num2, num3) {
    // La función recibe tres números distintos.
    // Si num1 es mayor a num2 y a num3, y además es positivo, retornar ---> "Numero 1 es mayor y positivo".
    // Si alguno de los tres números es negativo, retornar ---> "Hay negativos".
    // Si num3 es más grande que num1 y num2, aumentar su valor en 1 y retornar el nuevo valor.
    // Si todos los argumentos son cero, retornar ---> "Error".
    // Si no se cumple ninguna de las condiciones anteriores, retornar false.
    // Tu código:
    if (num1 > num2 && num1 > num3 && num1 >0){
       return("Numero 1 es mayor y positivo");
    }else if (num1 <0 || num2 <0 || num3 <0){
       return ("Hay negativos")
    }else if (num3 > num1 && num3 > num2){
       num3 ++;
       return num3;
    } else if (num1 === 0 && num2 ===0 && num3 === 0){
       return ("Error");
    }else return false;
 }
 
 function esPrimo(num) {
    // Retornar true si "num" es primo.
    // De lo contrario retorna false.
    // [Pista 1]: un número primo sólo es divisible por sí mismo y por 1.
    // [Pista 2]: puedes resolverlo utilizando un `bucle for`.
    // [Nota]: los números negativos, 0 y 1 NO son números primos.
    // Tu código:
    var i = 2
    if (num <=1){
        return false;
    }
    for (i ; i<num ; i++){
        if(num % i === 0){
            return false;
        }
    }
    return true;
 }
 
 function esVerdadero(valor) {
    // Si "valor" es verdadero retornar "Soy verdadero".
    // Caso contrario, retornar "Soy falso".
    // Tu código:
    if (valor){
       return ("Soy verdadero");
    }else return ("Soy falso")
 
 }
 
 function tieneTresDigitos(num) {
    // Si el número recibido tiene tres dígitos retornar true.
    // Caso contrario, retornar false.
    // Tu código:
    if (num >= 100 && num <= 999){
       return true;
    }else return false;
 }
 
 function doWhile(num) {
    // Implementar una función que aumente el valor recibido en 5 hasta un límite de 8 veces.
    // Retornar el valor final.
    // Utilizar el bucle Do-While.
    // Tu código:
    let iteracion = 0;
    do{
       num +=5
       iteracion ++;
    } while (iteracion <8);
    return num;
 }
 
 /*⚠️ NO MODIFIQUES NADA DEBAJO DE ESTO ⚠️*/
 module.exports = {
    obtenerMayor,
    mayoriaDeEdad,
    conection,
    saludo,
    colors,
    esDiezOCinco,
    estaEnRango,
    esEntero,
    fizzBuzz,
    operadoresLogicos,
    esPrimo,
    esVerdadero,
    tieneTresDigitos,
    doWhile,
 };
 
