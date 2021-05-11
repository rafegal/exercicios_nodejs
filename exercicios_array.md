
# Exercicios 

## 1. Crie uma função que recebe um array de números inteiros e retorne a quantidade de elementos do array que são números negativos.

```js
function validaNumerosNegativos(array){
    // escreva seu código aqui

}
```

## 2. Crie uma função que receba um array de número que representam a temperatura mensal de uma determina cidade, retorne nesta função a maior temperatura, a menor temperatura e a média das temperaturas

```js
function validaTemperatura(temperaturas){    
    let menorTemperatura = temperaturas[0]
    let maiorTemperatura = temperaturas[0]
    let media = 0

    // escreva seu código aqui

    return {maiorTemperatura, menorTemperatura, media}
}

let temperatura = [20, 23, 12, 14, 30, 21, 31, 37, 5, 9]
let resultado = validaTemperatura(temperatura)
console.log("Maior temperatura:", resultado.maiorTemperatura)
console.log("Menor temperatura:", resultado.menorTemperatura)
console.log("Média da temperatura:", resultado.media)

```

## 3. Crie uma função que recebe um array de numeros inteiros e um valor que é um numero inteiro e então retorne a quantidade de vezes que esse valor de numero inteiro aparece no array.

**x está sendo representado pela variável de entrada numero**

```js

function validaRepeticaoNumeroNoArray(array, numero){
    // escreva seu código aqui
    
}

let array = [10, 10, 5, 2, 2, 10]
let vezesRepetidas = validaRepeticaoNumeroNoArray(array, 10)
console.log(vezesRepetidas)
```

## 4. Crie uma função que recebe um array de números e devolve a posição onde se encontra o maior valor do array. Se houver mais de um valor maior, devolver a posição da primeira ocorrência.

```js
function retornaPosicaoMaiorValor(array){
    // escreva seu código aqui
}
```

## 5. Crie uma função que recebe um array de inteiros e devolve um array de boolean onde, cada posição indique true se o elemento da posição correspondente do array for positivo e false caso seja negativo ou zero.

```js
function validaNumerosPositivos(array){
    // escreva seu código aqui
}
```

## 6. Crie um método que recebe um array de inteiros positivos e substitui seus elementos de valor ímpar por -1 e os pares por +1.

```js
function validaNumerosParesImpares(array){
    // escreva seu código aqui
}
```
