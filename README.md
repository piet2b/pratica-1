# pratica-1
organiza isso pqp

```ruby

// Crie um programa que dado um número imprima a sua tabuada. 

const numero = 7

for(let i = 0; i <= 10 ; i++){
    console.log(i * numero)
}

// Crie um programa que seja capaz de percorrer uma lista de números e imprima cada número e se é par ou ímpar.

const numero = [1 , 2 ,3 ,4 ,5 ,6 ,7 ,8, 9, 10]
for (let i = 0; i < numero.length; i++) {
  const item = numero[i];
if (item % 2 === 0) {
  console.log (item + ' é par')
  } else {
      console.log (item +' é ímpar')
  }
}

*/ desafios faceis
*/

//  Retorne o valor da soma de todos múltiplos de "A" até o seu limite "N".

var a = parseInt(gets());
var N = parseInt(gets());

let soma = 0

for (i = a; i <= N; i++) {
  if (i % a === 0) {
    soma += i
  }
}

print(soma)

// Caso o valor não seja múltiplo de 3 ou 5, exiba o número, conforme o enunciado.
    
   // Se o número for um múltiplo de 3 e 5 -> "FizzBuzz" ; 
   // Se o número for apenas múltiplo de 3 -> "Fizz" ; 
   // Se o número for apenas múltiplo de 5 -> "Buzz"; 
   // Se o número não for um múltiplo de 3 ou 5, o número deve ser exibido; 

let resultado = gets();
print(fizzBuzz(resultado));

function fizzBuzz(valor) {
  if (resultado % 3 === 0 && resultado % 5 === 0) {
    return 'FizzBuzz'
  }
  else if (resultado % 3 === 0) {
    return 'Fizz'
  }
  else if (resultado % 5 === 0) {
    return 'Buzz'
  }
  else {
    return resultado
  }
}

// Implemente um método que calcule o somatório de um número usando recursividade:

let n = parseInt(gets());

let soma = 0

function somatorio(n){

for (let i = n; i >= 0; i--) {
    soma += i
  }
  print(soma)
}
somatorio(n)

// Imprima se os valores numéricos passados são iguais ou não.

let A = gets();
let B = gets();

function verificarNums(a, b) {
  if (a === b) {
    return 'Sao iguais!'
  }
  else {
    return 'Nao sao iguais!'
  }
}

print (verificarNums(A, B))

// Retorne o valor do elemento no Array junto de sua respectiva posição.

let elementos = [64, 137, -16, 43, 67, 81, -90, 212, 10, 75]; 

let valor = parseInt(gets());

let encontrado = elementos.find(elemento => elemento === valor);

if (encontrado !== undefined){
  let index = elementos.indexOf(encontrado)
  print(`Achei ${encontrado} na posicao ${index}`)
} else {
  print(`Numero ${valor} nao encontrado!`)
}













```
