# Resolução dos desafios 2

Em uma carreira de desenvolvimento de software, a prática consistente da lógica de programação desempenha um papel fundamental na construção de bases sólidas. A lógica de programação não apenas permite a criação de algoritmos eficientes e soluções elegantes, mas também desenvolve a capacidade de pensar de forma estruturada e analítica. Essa habilidade é essencial para enfrentar desafios complexos e transformar problemas abstratos em implementações tangíveis. 

Pensando nisso, criamos uma lista de atividades (não obrigatórias) focada em prática para melhorar ainda mais sua experiência de aprendizagem.
[]()

#### Sugestões de respostas

1) Criar uma função que exibe "Olá, mundo!" no console.

```js 
function exibirOla() {
  console.log("Olá, mundo!");
}

exibirOla();
```

2) Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.

```js
function exibirOlaNome(nome) {
  console.log(`Olá, ${nome}!`);
}

exibirOlaNome("Alice");
```


3) Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.

```js 
function calcularDobro(numero) {
  return numero * 2;
}

let resultadoDobro = calcularDobro(5);
console.log(resultadoDobro);
```

4) Criar uma função que recebe três números como parâmetros e retorna a média deles.

```js
function calcularMedia(a, b, c) {
  return (a + b + c) / 3;
}

let media = calcularMedia(4, 7, 10);
console.log(media);
```

5) Criar uma função que recebe dois números como parâmetros e retorna o maior deles.

```js 
function encontrarMaior(a, b) {
  return a > b ? a : b;
}

let maiorNumero = encontrarMaior(15, 9);
console.log(maiorNumero);
```

6) Criar uma função que recebe um número como parâmetro e retorna a raiz quadrada desse número.

```js 
function quadrado(numero) {
  return numero * numero;
}

let resultado = quadrado(2);
console.log(resultado);
```
