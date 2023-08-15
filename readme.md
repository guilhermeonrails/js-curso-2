# Resolução dos desafios 1

Em uma carreira de desenvolvimento de software, a prática consistente da lógica de programação desempenha um papel fundamental na construção de bases sólidas. A lógica de programação não apenas permite a criação de algoritmos eficientes e soluções elegantes, mas também desenvolve a capacidade de pensar de forma estruturada e analítica. Essa habilidade é essencial para enfrentar desafios complexos e transformar problemas abstratos em implementações tangíveis. 

Pensando nisso, criamos uma lista de atividades (não obrigatórias) focada em prática para melhorar ainda mais sua experiência de aprendizagem.
[]()

#### Sugestões de respostas
2) 
```js
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';
```
3) No `index.html`, adicionamos no onclick o seguinte código:

```html 
<button onclick="exibirMensagemNoConsole()" class="button">Console</button>
```

- Já no `app.js`:

```js
function exibirMensagemNoConsole() {
    console.log('O botão foi clicado!')
}
```

4) No `index.html`, adicionamos no onclick o seguinte código:

```html 
<button onclick="exibirAlerta()" class="button">Alert</button>
```

- Já no `app.js`:

```js 
function exibirAlerta() {
    alert('Eu amo Js')
}
```

5) No `index.html`, adicionamos no onclick o seguinte código:

```html 
<button onclick="exibirPrompt()" class="button">Prompt</button>
```

- Já no `app.js`:

```js
function exibirPrompt() {
    let nomeDaCidade = prompt('Digite o nome de uma cidade do Brasil que você gosta muito:')
    alert(`Estive em ${nomeDaCidade} e lembrei de você`)
}
```

6) No `index.html`, adicionamos no onclick o seguinte código:

```html 
 <button onclick="somandoDoisNumeros()" class="button">Soma</button>
```

- Já no `app.js`:

```js 
function somandoDoisNumeros() {
    let primeiroNumero = parseInt(prompt('Digite o primeiro número'));
    let segundoNumero = parseInt(prompt('Digite o segundo número'));
    let resultado = primeiroNumero + segundoNumero;
    alert(`${primeiroNumero} + ${segundoNumero} = ${resultado}`)
}
```

