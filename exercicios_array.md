
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

## 6. Crie uma função que recebe um array de inteiros positivos e substitui seus elementos de valor ímpar por -1 e os pares por +1.

```js
function validaNumerosParesImpares(array){
    // escreva seu código aqui
}
```

## 7. Crie uma função que recebe um array de números e retorne um novo array com o mesmo números porém sem duplicar nenhum número.
## Exemplo: 
          input:  [1, 2, 2, 3, 10, 5, 10, 4]
          output: [1, 2, 3, 10, 5, 4]

```js
function removeNumerosDuplicados(array){
    // escreva seu código aqui
}
```

## 8. Crie uma função que receba um array de string e retorne a string com mais caracteres.
## Exemplo: 
          input:  ["Gato", "Cachorro", "Zebra", "Boi"]
          output: "Cachorro"

```js
function identificaMaiorString(array){
    // escreva seu código aqui
} 
```

## 9. Crie uma função que receba uma array e um número como input e retorne o array sem o numero informado no input

## Exemplo: 
          input:  [3, 4, 2, 7, 10, 14], 7
          output: [3, 4, 2, 10, 14]

```js
function removeElementoDoArray(array, numero){
    // escreva seu código aqui
}
```

## 10. Crie uma função que retorne um array com os números pares de 0 a 100.

## Exemplo: 
          output: [2, 4, 6, 8, 10, 12...]

```js
function retornaNumerosPares(array){
    // escreva seu código aqui
}
```

## 11. Crie uma função que receba dois arrays como input, retorne a intersecção desses dois arrays.
## Intersecção: Intersecção é o que tem nos dois conjuntos, nos caso nos dois array.
## Exemplo:
        input:  [10, 20, 21, 23, 32, 34]
                [10, 19, 21, 24, 31, 34]
        output: [10, 21, 34]

```js
function retornaInterseccao(arrayA, arrayB){
    // escreva seu código aqui
}
```

## 11. Crie uma função que receba dois arrays como input, retorne um array com a união desses dois arrays, ou seja, um novo array com os elementos dos dois arrays.
## Exemplo:
        input:  [10, 20, 30, 31]
                [35, 40, 50]
        output: [10, 20, 30, 31, 35, 40, 50]

```js
function retornaUniao(arrayA, arrayB){
    // escreva seu código aqui
}
```

## 12. Crie uma função que receba dois array como input, retorne um novo array com os dados que existem no primeiro array mas não existem no segundo array
## Exemplo:
        input:  [5, 10, 20, 30, 31]
                [1, 2, 10, 20]
        output: [5, 30, 31]

```js
function retornaDiferenca(arrayA, arrayB){
    // escreva seu código aqui
}
```


## 13. Crie uma função que receba um array e retorne um novo array com os valores dobrados. Utilize função map.
## Exemploa
        input:  [1, 2, 3, 10, 12]                
        output: [2, 4, 6, 20, 24]

```js
function retornaArrayDobrado(array){
    // escreva seu código aqui
}
```


## 14. Crie uma função que receba um array e um novo array apenas com os números pares. Utilize função filter.
## Exemploa
        input:  [1, 2, 3, 10, 12]                
        output: [2, 10, 12]

```js
function retornaNumerosPares(array){
    // escreva seu código aqui
}
```


## 14. Crie uma função que receba um array e um novo array apenas com os números pares. Utilize função filter.
## Exemploa
        input:  [1, 2, 3, 10, 12]                
        output: [2, 10, 12]

```js
function retornaNumerosPares(array){
    // escreva seu código aqui
}
```

## 15. Crie uma função que um número e imprima na tela a tabuado daquele número do 1 ao 10.
            

```js
function tabuada(numero){
    // escreva seu código aqui
}
```