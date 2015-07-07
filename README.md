Aplicación que obtiene un número aleatorio entre 0 y 1, a través de la clase Math. Al final se imprime si es menor o mayor a 0.5

Código de la aplicación

var numero = Math.random();

var str =' MAYOR que 0,5';

if (numero <= 0.5){
  str = ' MENOR que 0,5';
}

console.log('\n' + numero + str + '\n');