
# variaveis, constanters, tipos, calculos e concatenações.

Em programação fazemos calculos e armazenamos informações, enquando o programa está em execução nos armazenamos dados, por exemplo, vamos fazer uma soma entre dois numeros, esses dois numeros em algum momento ficarão armazenados em memoria.

Em programação utilizamos nomes para referenciar o endereço de memória onde o dado está armazenado. 

Esse dado pode ser variado ou constante. 
Variado é quando ele em tempo de execução pode ser alterado, ou seja, mantemos a referencia (nome) mas mudando o endereço de memoria (sempre que um dado é alterado o endereço de memória muda, por isso chamamos de variável). Já a constante nasce e morre com o mesmo endereço de memória ou seja o dado nunca pode ser alterado.

Para declarar variáveis e constantes em javascript usamos:

```js
var nomeVariavel
let nomeVariavel
const NomeConsntante
```

**var:** declara a variável e deixa ela disponível a todo escopo (falaremos sobre isso mais tarde). O nome var é uma encurtação de variable (variavel em ingles)

**let:** declara variáveis que funcionam apenas dentro do escopo (falaremos sobre isso mais tarde), por enquanto, pense que let é o tipo de declaração de variável mais nova e é a mais recomendada a ser utilizada, usaremos apenas ela e const daqui pra frente.

**const:** const é a diminuição de constant (constante em ingles) e é utilizada para declarar um dado constante, um contra ponto as variáveis. Enquanto as variáveis podem ter seu valor alterado após sua declaração, as constantes depois de declaradas não podem ter seu valores alterados.

Com o let podemos fazer a declaração e depois alterar o valor da variável
```js
let a = 10
a = 10 + 1
```

Com o const temos uma constante, depois da reclaração, se tentarmos alterar o valor como no código abaixo, iremos ter um erro ao executar o nosso programa. Assim, ao declarar uma constante saiba que o valor nunca mais será alterado. Constante são importantes quando você não quer que algo mude de valor.
```js
const a = 10
a = 10 + 1
```

Um exemplo claro de quando se utilizar constante, vamos supor que esteja fazendo um programa que em algum momento você precise fazer um calculo com o valor de PI, sabemos que PI é sempre 3.14... ou seja, PI nunca muda seu valor, não tem um valor variável, então ao declarar PI ao invés de utilizar let se utiliza const pois PI é um valor constante que nunca irá mudar.
```js
const pi = 3.14159265359
```

## 1.

```javascript
let numberA = 10
let numberB = 20
let soma = numberA + numberB
let subtracao = soma - numberA - numberB
console.log(subtracao)
```

## 2.

```javascript
let nome = "Rafael"
let sobrenome = "Galleani"
let nomeCompleto = nome + " " + sobrenome
let idade = 31
console.log(nomeCompleto, "-", idade)
```

## 3.

Dado as variáveis numberA e numberB armazene em outras 4 variáveis a soma, subtração, multiplicação e divisão entre numberA e numberB e as imprima na tela

```javascript
let numberA = 10
let numberB = 32
```

## 4.

Dado as variáveis abaixo, crie uma variável que receba o valor da variável nome e idade de forma que ela fique com o seguinte formato: "Oliver - 2 anos"
Imprima a variável criada na tela.

```javascript
let nome = "Oliver"
let idade = 2
```

## 5.

Utilizando do mesmo conceito do exercício acima, imprima na tela "Oliver - 2 anos" mas sem criar uma terceira variável, utilizando apenas as variáveis disponíveis abaixo:

```javascript
let nome = "Oliver"
let idade = 2
```

## 6.

Utilizando do mesmo conceito do exercício acima, imprima na tela "Oliver - 2 anos" mas sem criar uma terceira variável, utilizando apenas as variáveis disponíveis abaixo:

```javascript
let nome = "Oliver"
let idade = 2
```

# Conversão de dados.

Em linguagens de programação temos tipos de dados, no javascript temos alguns como:

**string:** São textos. Exemplo: "Rafael", "Galleani", "", " ", " - ", "10"
**Number:** São números. Exemplo: 10, 100, -20, 10.5
**Boolean:** São binários, ou seja, podem apenas se verdadeiros ou falsos. Exemplo: true, false
**object:** Qualquer outro tipo diferente dos acimas, um array por exemplo é do tipo object.

Os tipos ajudar o interpretador da linguagem a decidir como irá processar ações entre os tipos.  
Exemplo: se eu tenho variáveis do tipo string e tentar fazer uma soma, será feita uma concatenação devido ao tipo delas, para eu fazer uma soma de fato é necessário converter para número.

## 1.

Dado o código abaixo, qual o valor da variavel soma?

```javascript
let numberA = "10"
let numberB = "45"
let soma = numberA + numberB
```

## 2.

Dado o código abaixo, qual o valor da variavel soma?

```javascript
let numberA = "10"
let numberB = "45"
let soma = Number(numberA) + Number(numberB)
```

## 3.

Dado o código abaixo, qual o valor da variavel subtracao?

```javascript
let numberA = "10"
let numberB = "2"
let subtracao = numberA - numberB
```

## 4.

Dados as variáveis abaixo, grave em uma variável nova com o valor da soma de stringA e stringB e imprima na tela o resultado.

```javascript
let stringA = "10"
let stringB = "45"
```
## 5.

Dados as variáveis abaixo, retorne em uma variável nova a juncao de numberA e numberB e imprima na tela o resultado.
O resultado deverá ser: "100400"

```javascript
let numberA = 100
let numberB = 400
```

# Auto incremento

Auto incremento encurta a forma como fazemos cálculos que envolver o incremento da própria variável no calculo onde ela mesmo irá receber o valor do calculo.

## 1.

Dado o código abaixo qual será o valor final da variável numberA?

```javascript
let numberA = 10
numberA += 20
```

## 2.

Dado o código abaixo qual será o valor final da variável numberA?

```javascript
let numberA = 10
numberA++
```

## 3.

Dado o código abaixo qual será o valor final da variável numberA?

```javascript
let numberA = 10
numberA++
```

## 4.

Dado o código abaixo qual será o valor final da variável numberA?

```javascript
let numberA = 10
numberA -= 5
numberA--
numberA *= 2
```

## 5.

Dado numberA e numberB realiza a soma de numberA e numberB mantendo o resultado em numberA. Utilize auto incremento.

```javascript
let numberA = 10
let numberB = 5
```

## 6.

Dado numberA e numberB realize a subtração de numberA e numberB mantendo o resultado em numberA e depois incrimenta +1 ao resultado final
de numberA. Utilize auto incremento.

```javascript
let numberA = 10
let numberB = 5
```

# Arrays

Array é um tipo muito usado na programação, também conhecido como vetor ou lista.
Um array pode armazena uma lista de objetos, que podem ser número, nomes, ou qualquer outra coisa.  
Listas são como trens, trens possuem nenhum ou muitos vagões e cada vagão pode possuir tipos diferentes de conteúdo.


## 1.

Dado o código abaixo, qual o valor da variável resultado?

```javascript
let array = [10, 4, 5, 7, 2]
let resultado = array[2]
```

## 2.

Dado o código abaixo, qual o valor da variável resultado?

```javascript
let array = [10, 4, 5, 7, 2]
let resultado = array[2]
resultado += array[1]
```

## 3.

Dado o código abaixo, qual o valor da variável resultado?

```javascript
let array = [10, 4, 5, 7, 2]
let resultado = array[2]
resultado += array[4]
resultado--
```

## 4.

Dado a variável array abaixo, imprima na tela a posição 3 do array.

```javascript
let array = [1, 10, "rafael", "Oliver", 10]
```

## 5.

Dado o array abaixo crie uma variável soma e armazene o valor da primeira posição com o valor da terceira posição.

```javascript
let array = [10, 5, 4, 2, 10]
```

## 6.

Dado o array abaixo crie duas variaveis, nomeCompleto e nomeCompleto B, os valores finais delas devem ser:
nomeCompleto = "Rafael Galleani"
nomeCompletoB = "Oliver Villares"

A atribuição de valores das variáveis devem necessariamente vir dos valores do array.

```javascript
let array = ["Rafael", "Galleani", "Oliver", "Villares"]
```

## Condicional

Condicionais são utilizadas para validar determinado fluxo. Vamos ver na prática:

## 1.

Vamos pensar em um mapa mental, eu quero beber água, para isso antes eu preciso pegar a garra de água e depois abrir a garra, colocar a água no copo e
então tomar a água. Vamos encurtar isso tudo, para eu tomar água eu preciso que tenha água no meu copo, vamos por isso em códio.

```javascript
let copoAgua = false
let tomoAgua = false

if (copoAgua){
    tomoAgua = true
}
console.log(tomoAgua)
```

```javascript
let copoAgua = true
let tomoAgua = false

if (copoAgua){
    tomoAgua = true
}
console.log(tomoAgua)
```

## 2.

Dado o código abaixo, qual será o valor da variável ligaMotor?

```javascript
let carroGasolina = true
let ligaMotor = false

if (carroGasolina){
    ligaMotor = true
}
console.log(tomoAgua)
```


## 3.

Dado o código abaixo, qual será o valor da variável resultado?

```javascript
let numero = 10
let resultado
if (numero % 2 == 0){
    resultado = "P"
}else{
    resultado = "I"
}
console.log(resultado)
```
## 4. 

Dado o código abaixo, qual será o valor da variável resultado?

```javascript
let numero = 10
let next = false
let resultado
if (numero % 2 == 0 && next){
    resultado = "P"
}else{
    resultado = "I"
}
console.log(resultado)
```

## 5.

Dado o código abaixo, qual será o valor da variável resultado?

```javascript
let numero = 10
let next = false
let resultado
if (numero % 2 == 0 && !next){
    resultado = "P"
}else{
    resultado = "I"
}
console.log(resultado)
```

## 6.

Dado o código abaixo, qual será o valor da variável resultado?

```javascript
let numero = 9
let next = false
let resultado
if (numero % 2 == 0 && !next){
    resultado = "P"
}else{
    resultado = "I"
}
console.log(resultado)
```

## 7.

Crie uma variável menorValor e armazene o menor valor entre numberA e numberB e imprima na tela para o usuário. Use condicional.

```javascript
let numberA = 10
let numberB = 5
```

## 7.

Crie uma variável maiorValor e armazene o maior valor entre numberA e numberB. 
Imprima na tela se a variável imprimeNumero for verdadeira, caso seja falsa imprima numberA. Use condicional.

```javascript
let numberA = -5
let numberB = 0
let imprimeNumero = false
```

## 7.

Crie uma variável que receba a soma entre numberA e numberB e imprima na tela se o resultado da soma é um número impar ou um número par.

```javascript
let numberA = 15
let numberB = 10
```

## 8.

Declare uma variável com o nome menorValor e usando condicional armazena nela o menor valor entre o resultado da soma entre numberA e numberB e a soma entre numberC e numberD. Imprima na rela o resultado de menorValor

```javascript
let numberA = 10
let numberB = 5

let numberC = 7
let numberD = 15
```

## 9.

Dado o código abaixo, qual será o valor da variável resultado?

```javascript
let nome = "Rafael"
let resultado = nome.length
console.log(resultado)
```

## 10.

Declare uma variável que concatene as variáveis nome e sobrenome contendo espaço entre elas, em seguida crier uma variavel que armazene o total
de caracteres da concatenação e imprima se o total de caracters é um número par ou um número impar.

```javascript
let nome = "Oliver"
let sobrenome = "Galleani"
```

## 11.

Declare uma variável que concatene as variáveis nome e sobrenome contendo espaço entre elas, em seguida criae uma variavel que armazene o total
de caracteres da concatenação e multiplique pela variável número e então e imprima se o total de caracteres é um número par ou um número impar.
Caso o resultado seja um número par, imprima também o resultado da multiplicação.

```javascript
let nome = "Oliver"
let sobrenome = "Galleani"
let numero = 10
```

# Input

Existe um forma de solicitar input do usuário em javascript, utilizando o metodo prompt. 
Vamos ver aqui ver uma outra abordagem do prompt utilizando nodejs.

`npm install prompt-sync`

```javascript
const prompt = require('prompt-sync')({sigint: true});
let nome = prompt('Qual seu nome: ');
console.log("Olá " + nome + "!")
```

```javascript
const prompt = require('prompt-sync')(); 
let a = Number(prompt('Entre com o primeiro número: '));
let b = Number(prompt('Entre com o segundo número: '));
let soma = a + b
console.log("A soma é: ", soma)
```

Agora é possível solicitar ao usuário que digite input de dados para o nosso programa.
Com essa possibilidade, vamos treinar um pouco.

## 1.

Faça um programa que solicite o primeiro nome do usuário, depois o segundo nome do usuário e por último a idade do usuário e no fim mostre o nome completo do usuário e a idade na mesma linha, no padrão abaixo:  
Rafael Galleani - 31 anos

## 2.

Faça um programa que peça ao usuário dois número e mostre a ele duas opções, de soma e subtração.
Se ele digitar 1, deve-se fazer uma soma e mostrar o resultado para o usuário, se ele digitar 2 deve-se fazer uma subtração e mostrar o resultado para o usuário.
Exemplo da como deve ser mostrado a opção de soma e subtração ao usuário:

```
1. Soma  
2. Subtração

Selecione a operação desejada: 
```

Dica: Utilize console.log() para escrever as opções de operações e prompt para solicitar a operação desejada.

## Laço de repitição (loop)

Laço de repetição ou loop é muito usado em programação para repetir rotinas sem a necessidade de repetir código. É muito utilizado para percorrer arrays/list.
Os tipos mais utilizados de laço de repetição são for e while. 
Por enquanto vamos focar no for.

Existem duas formas de percorrer uma lista, vamos ve-las:

```javascript
let array = [10, 20, 5, 30];
for (let i = 0; i < array.length; i++) {
  console.log("Posição " + i + ": " + array[i]);
}
```

```javascript
let array = [10, 20, 5, 30]
for (let elemento of array){
    console.log(elemento)
}
```

## 1.

```javascript
let array = [10, 10, 5, 5, 10];
let resultado = 0
for (let i = 0; i < array.length; i++) {
  resultado += array[i]
}
console.log(resultado)
```

## 2.

```javascript
let array = [10, 10, 5, 5, 10];
let resultado = 0
for (let elemento of array) {
  resultado += elemento
}
console.log(resultado)
```

## 3.

```javascript
let array = [10, 5, 7, 14, 8];
let resultado = 0
for (let elemento of array) {
  if (elemento > resultado){
      resultado = elemento
  }
}
console.log(resultado)
```

## 4.

```javascript
let array = [10, 5, 7, 14, 8];
let resultado = 0
for (let i = 0; i < array.length; i++) {
  if (array[i] > resultado){
      resultado = i
  }
}
console.log(resultado)
```

## 5.

Dado o array abaixo, armazena em uma variavel o maior elemento do array e em outra a soma de todos os elementos do array.

```javascript
let array = [10, 5, 7, 14, 8]
```

## 6.

Dado o array abaixo armazena em uma variavel a posição do primeiro menor valor do array.

```javascript
let array = [10, 5, 7, 14, 8]
```

## 7.

Dado o array abaixo, armazena em uma variável os nomes concatenados separados por virgula, resultado deverá ser:
Rafael, Oliver, Galleani, Teste.

```javascript
let array = ["Rafael", "Oliver", "Galleani", "Teste"]
```

## 8.

Dado o array abaixo, armazena em uma variável se o nome digitado pelo usuário se encontra no array onde o array representa nossa base de dados e retorne se o nome se encontra ou não na base de dados.

```javascript
let array = ["Rafael", "Oliver", "Galleani", "Teste"]
let a = Number(prompt('Entre com o nome para a busca: '));
let nomeEncontrado = false
```

## 9.

Faça um programa que retorne a media das notas dos alunos e o valor da nota mais alta. 
Nota: retorne é mostrar o valor para o usuário, lembrese que você terá que usar variaveis para armazenas o valor e media das notas, é comum o enunciado não ter essa informação e fica a cargo do desenvolvedor pensar quando é necessário gravar um dado em variavel.

```javascript
let notas = [10, 5, 3, 2, 7, 7, 8, 9, 10]
```

## 10.

Repita o exercicios acima, mas dessa vez retornando o id do aluno que teve a nota mais alta, onde id do aluno é o indice do array.

```javascript
let notas = [10, 5, 3, 2, 7, 7, 8, 9]
```

## 11.

Faça o mesmo do exercicio 9, mas dessa vez retorne todos os alunos com a nota mais alta e a nota mais baixa.
Nota: Como não sabemos quantos alunos possam ter tirado nota 10 por exemplo, vamos gravar os dados em um novo array. Para adicionar item no array deve utilizar: `array.push(valor)`

```javascript
let notas = [10, 5, 3, 2, 7, 7, 8, 9, 10]
let notasAltas = []
let notasBaixas = []
let media = 0
```

## 12.

Faça um programa que percorra o array de numeros e armazena em variaveis diferentes do tipo array os numeros pares e numeros impares, se o número for zero ou maior que 100 ele não deverá aparece em nenhum dos arrays.

```javascript
let numeros = [10, 5, 3, 2, 87, 17, 28, 9, 0, 10, 2, 1, 101, 32, 6, 7]
let pares = []
let impares = []
```

## Funções

Funções são utilizadas para podermos fazer reuso de código/algoritmo.  
Por exemplo: Digamos que você tem um programa que necessita diversas vezes executar uma concatenação de strings, você pode criar uma função que realiza essa operação e então chamar essa função em diferentes trechos do seu código.

Vamos ver mais exemplos.

Vamos super que temos que pedir três números ao usuário e informar se aquele número é par ou impar, mas tenho que informar logo após a digitação de cada número, pra isso fazemos o código abaixo:

```javascript
const prompt = require('prompt-sync')({sigint: true});

let resultado
let numeroA = prompt("Digite primeiro número: ")
if (Number(numeroA) % 2 == 1){
    resultado = "Impar"
}else{
    resultado = "Par"
}
console.log("O número " + numeroA + " é um número " + resultado)

let numeroB = prompt("Digite segundo número: ")
if (Number(numeroB) % 2 == 1){
    resultado = "Impar"
}else{
    resultado = "Par"
}
console.log("O número " + numeroB + " é um número " + resultado)

let numeroC = prompt("Digite terceiro número: ")
if (Number(numeroC) % 2 == 1){
    resultado = "Impar"
}else{
    resultado = "Par"
}
console.log("O número " + numeroC + " é um número " + resultado)
```

Podemos ver no código acima que estamos repetindo a condicional que verifica se o número digitado é par ou impar, para que isso não aconteça, podemos transformar apenas esse trecho em uma função e então passaríamos a chamar a função ao invés de todo esse código.  

```javascript
const prompt = require('prompt-sync')({sigint: true});

function verificaNumeroImparPar(numero){
    if (Number(numero) % 2 == 1){
        return "Impar"
    }else{
        return "Par"
    }
}
let numeroA = prompt("Digite primeiro número: ")
console.log("O número " + numeroA + " é um número " + verificaNumeroImparPar(numeroA))

let numeroB = prompt("Digite segundo número: ")
console.log("O número " + numeroB + " é um número " + verificaNumeroImparPar(numeroB))

let numeroC = prompt("Digite terceiro número: ")
console.log("O número " + numeroC + " é um número " + verificaNumeroImparPar(numeroC))
}
```

Agora temos um código muito menor.  
A função deve ser utilizada para reaproveitamento de código, sempre que você precisar usar o mesmo algoritmo em mais de um lugar, pense em transformá-lo em uma função.  
Funções além de ajudar no reaproveitamento de código, também ajuda na organização e leitura de código, quando você olha para uma função cujo nome seja soma, subtração, concatenaNome, ligaMotor, acendaLuz, você já sabe o que aquele trecho de código dentro da função faz antes mesmo de precisar ler o código dentro da função, então, utilize função para organizar seu código da mesma forma que você organiza caixas, pratilheiras, armário, etc...


## Arrows functions

```js
var funcA = x => x * x;
var funcB = (x, y) => { return x + y; };
console.log(funcA(10))
console.log(funcB(10, 20))
```
