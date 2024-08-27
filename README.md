# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

const hortifruti = ["banana", "morango", "uva", "melão"]
//remove o ultimo elemento e mostra o elemento removido
console.log(hortifruti.pop());

//Adicionar elementos no final da array e mostra a quantidade d array
console.log(hortifruti.push("melão"));
console.log(hortifruti)

console.log(hortifruti.sort());
console.log(hortifruti.length);

const fruta = prompt("Qual fruta você deseja")
 
  console.log("obrigado pela compra")


//FARMÁCIA

const medicamento = prompt("Qual medicamento você deseja comprar?")
const bairro = prompt("Qual o bairro em que você mora?")

switch(medicamento.toLowerCase()){
  case "zerolac":
    console.log(`O medicamento zerolac custa R$ 23,50 por unidade.`)
    break;
  case "cloridrato de trazodona":
  case "cloridrato de sertralina":
    console.log(`O medicamento ${medicamento.toLowerCase()} custa R$ 11,50 por unidade.`)
    break;
  case "lorotadina":
  case "histamin":
    console.log(`O medicamento ${medicamento.toLowerCase()} custa R$ 11,00 por unidade.`)
    break;
  default:
    console.log(`O medicamento ${medicamento.toLowerCase()} não está disponível.`)
} 

switch(bairro.toLowerCase()){
  case "janga":
  case "pau amarelo":
    console.log(`A taxa de entrega para ${bairro.toLowerCase()} fica por R$ 7,50.`)
    break;
  case "marinha farinha":
    console.log(`A taxa de entrega para ${bairro.toLowerCase()} fica por R$ 12,50.`)
    break;
  case "maranguape":
    console.log(`A taxa de entrega ${bairro.toLowerCase()} fica por R$ 10,00. `)
  default:
    console.log(`Infelizmente não fazemos entregas para ${bairro.toLowerCase()}.`)
} 

const idade = prompt(`Qual a sua idade`)


//pode entrar na festa.
//pode entrar na festa, mas não pode tomar bebida alcoólica.(else if)
// Aqui não é mirabilandia!(else)

if(idade >= 18) {  
  console.log("pode entrar na festa")
} else if(idade > 15 && idade < 18) {console.log("pode entrar na festa, mas não pode tomar bebida alcoólica") } else{ 
 console.log("aqui não é mirabiladia!")
}


## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
