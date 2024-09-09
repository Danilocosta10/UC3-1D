# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.
1. Variavel
As variáveis como nomes simbólicos para os valores em sua aplicação. O nome das variáveis, chamados de identificadores, obedecem determinadas regras.

Var: é usado para criar uma variável e inicializá-la com um valor.

```js
var a = 5;
var b = 10;
var soma = a + b;
console.log('Soma:', soma); // Soma: 15
```
let: Permite declarar variáveis com escopo de bloco. Ideal para variáveis que mudam de valor.

```js
let a = 5;
let b = 10;
let soma = a + b;
console.log('Soma:', soma); // Soma: 15
```

const: Declara constantes com escopo de bloco. O valor não pode ser alterado após a atribuição inicial.

```js
const x = 10;
const y = 5;

const soma = x + y;
const subtracao = x - y;
const multiplicacao = x * y;
const divisao = x / y;
const resto = x % y;

console.log('Soma:', soma); // Soma: 15
console.log('Subtração:', subtracao); // Subtração: 5
console.log('Multiplicação:', multiplicacao); // Multiplicação: 50
console.log('Divisão:', divisao); // Divisão: 2
console.log('Resto:', resto); // Resto: 0
```

2.String: é um tipo de dado que representa uma sequência de caracteres, Elas podem ser envolvidas por aspas simples ('), aspas duplas ("), ou crases (`), que são conhecidas como template literals.

```js
let string1 = 'Olá, mundo!';      // Aspas simples
let string2 = "JavaScript é divertido!";  // Aspas duplas
let string3 = `Usando template literals`;  // Crases
````
3. Number:  é usado para representar valores numéricos. ele é um dos tipos de linguagem mais primitivos e poder ser ultilizados para operações matematicas
```js
let a = 10;
let b = 5;

let soma = a + b;        // Adição
let subtracao = a - b;   // Subtração
let multiplicacao = a * b; // Multiplicação
let divisao = a / b;    // Divisão
let resto = a % b;      // Módulo (resto da divisão)

console.log('Soma:', soma);            // Soma: 15
console.log('Subtração:', subtracao);  // Subtração: 5
console.log('Multiplicação:', multiplicacao); // Multiplicação: 50
console.log('Divisão:', divisao);      // Divisão: 2
console.log('Resto:', resto);          // Resto: 0
````

4. Switch case: O switch case é uma estrutura de controle que define o código a ser executado com base em uma comparação de valores.

````
let dia = 3; // Supondo que 1 = Domingo, 2 = Segunda, 3 = Terça, etc.

switch (dia) {
    case 1:
        console.log('Domingo');
        break;
    case 2:
        console.log('Segunda-feira');
        break;
    case 3:
        console.log('Terça-feira');
        break;
    case 4:
        console.log('Quarta-feira');
        break;
    case 5:
        console.log('Quinta-feira');
        break;
    case 6:
        console.log('Sexta-feira');
        break;
    case 7:
        console.log('Sábado');
        break;
    default:
        console.log('Dia inválido');
}
````
5.if e else: A condicional if é uma estrutura condicional que executa a afirmação, dentro do bloco, se determinada condição for verdadeira. Se for falsa, executa as afirmações dentro de else.
````js
let idade = 18;

if (idade >= 18) {
    console.log('Você é maior de idade.');
} else {
    console.log('Você é menor de idade.');
}
````

6. Prompt:exibe uma caixa de diálogo, solicitando a entrada do usuário e retorna o valor de entrada se o usuário clicar em “OK”.

```js
let nome = prompt("Qual é o seu nome?");
console.log("Olá, " + nome + "!");
````

7. Concatenação: Concatenação é um termo usado em computação para designar a operação de unir o conteúdo de duas strings

````js
   let primeiroNome = 'João';
let sobrenome = 'Silva';

let nomeCompleto = primeiroNome + ' ' + sobrenome;
console.log(nomeCompleto); // João Silva
````

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
