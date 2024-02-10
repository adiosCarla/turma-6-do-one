<h1>Desafios Turma 6 do ONE</h1>

Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".
```ruby
let dia = prompt("Digite o dia da semana:");

if (dia == "Sábado") {
    alert("Hoje é Sábado, Bom fim de semana!");
} else if (dia == "Domingo") { 
    alert("Hoje é Domingo, Bom fim de semana!");
} else {
    alert(`Hoje é ${dia}, Boa semana!`);
}
```

Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
```ruby
let numero = prompt("Digite um número:");

if (numero > 0) {
    alert("O número digitado é positivo!");
} else {
    alert("O número digitado é negativo!");
}
```

Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
```ruby
let pontuacao = prompt("Digite um número:");

if (pontuacao >= 100) {
    console.log("Parabéns, você venceu!");
} else {
    console.log("Tente novamente para ganhar.");
}
```

Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
```ruby
let saldo = 1500;

alert(`O valor do seu saldo bancário é de: R$${saldo}`);
```

Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
```ruby
let nome = prompt("Digite o seu nome:");

alert(`Boas-vindas, ${nome}!`);
```

Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.
```ruby
let contador = 1;

while (contador <= 10) {
  console.log(contador);
  contador++;
}
```
Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```ruby
let contador = 10;

while (contador >= 0) {
  console.log(contador);
  contador--;
}
```

Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```ruby
let numero = prompt("Digite um número:");

while (numero >= 0) {
  console.log(numero);
  numero--;
}
```

Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```ruby
let numero = prompt("Digite um número:");
let contador = 0;

while (contador <= numero) {
  console.log(contador);
  contador++;
}
```

Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.
```ruby
let valor1 = 16;
let valor2 = 19;
resultado = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`);
```

Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.
```ruby
let valor1 = 19;
let valor2 = 16;
resultado = valor1 - valor2;

console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}.`);
```

Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.
```ruby
let idade = prompt("Insira sua idade:");

if (idade >= 18) {
    console.log("Maior de idade.");
} else {
    console.log("Menor de idade.");
}
```

Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.
```ruby
let numero = parseFloat(prompt("Digite um número:"));

if (numero > 0) {
    console.log("Número positivo.");
} else if (numero < 0) {
    console.log("Número negativo.");
} else {
        console.log("Zero.");
}
```

Use um loop while para imprimir os números de 1 a 10 no console.
```ruby
let contador = 1;

while (contador <= 10) {
  console.log(contador);
  contador++;
}
```

Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.
```ruby
let nota = 10;

if (nota >= 7) {
    console.log("Aprovado.");
} else {
    console.log("Reprovado.");
}
```

Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.
```ruby
let numero = Math.random();

console.log(numero);
```

Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.
```ruby
let numero = parseInt(Math.random() * 10 + 1);

console.log(numero);
```

Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.
```ruby
let numero = parseInt(Math.random() * 1000 + 1);

console.log(numero);
```

Altere o conteúdo da tag h1 com document.querySelector e atribua o seguinte texto: Hora do Desafio.
```ruby
let titulo = document.querySelector("h1");

titulo.innerHTML = "Hora do Desafio";
```

Crie uma função que exiba no console a mensagem O botão foi clicado sempre que o botão Console for pressionado.
```ruby
<button onclick="verificarConsole()" class="button">Console</button>

function verificarConsole() {
    console.log("O botão foi clicado");
}
```

Crie uma função que exiba um alerta com a mensagem: Eu amo JS, sempre que o botão Alerta for pressionado.
```ruby
<button onclick="verificarAlerta()" class="button">Alert</button>

function verificarAlerta() {
    alert("Eu amo JS");
}
```

Crie uma função que é executada quando o botão prompt é clicado, perguntando o nome de uma cidade do Brasil. Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: Estive em {cidade} e lembrei de você.
```ruby
<button onclick="verificarPrompt()" class="button">Prompt</button>

function verificarPrompt() {
    let cidade = prompt("Digite o nome de uma cidade do Brasil:");
    alert(`Estive em ${cidade} e lembrei de você.`);
}
```

Ao clicar no botão soma, peça 2 números e exiba o resultado da soma em um alerta.
```ruby
<button onclick="verificarSoma()" class="button">Soma</button>

function verificarSoma() {
    let num1 = parseInt(prompt("Digite um número:"));
    let num2 = parseInt(prompt("Digite outro número:"));
    let soma = num1 + num2;
    alert(`O resultado da soma de ${num1} + ${num2} é: ${soma}.`);
}
```

Criar uma função que exibe "Olá, mundo!" no console.
```ruby
function olaMundo() {
    console.log("Olá, mundo!");
}

olaMundo();
```

Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
```ruby
function exibirNome(nome) {
    console.log(`Olá, ${nome}!`);
}

exibirNome("Carla");
```

Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
```ruby
function dobroNumero(numero) {
    return numero * 2;
}

let resultado = dobroNumero(5);
console.log(resultado);
```

Criar uma função que recebe três números como parâmetros e retorna a média deles.
```ruby
function mediaNumeros(a, b, c) {
    return (a + b + c) / 3;
}

let media = mediaNumeros(2, 3, 4);
console.log(media);
```

Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
```ruby
function maiorNumero(a, b) {
    return a > b ? a : b;
}

let maior = maiorNumero(10, 5)
console.log(maior);
```

Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo.
```ruby
function multiplicacao(numero) {
    return numero * numero;
}

let resultado = multiplicacao(2);
console.log(resultado);
```
