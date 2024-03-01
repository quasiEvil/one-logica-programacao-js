# Resolução dos Desafios do Módulo 1
### Curso Lógica de Programação (Alura + Oracle Next Education)

👉🏻 Conceitos aplicados: variáveis, condicionais (if-else), loops (while) e interações com o usuário (alert, prompt).

#### Desafios e resoluções:
1. Mostre um alerta com a mensagem "Bem-vindo ao nosso site!".
```javascript
alert('Boas-vindo ao nosso site!');
```

2. Declare uma variável chamada `nome` e atribua a ela o valor "Lua".
```javascript
let nome = 'Lua';
```

3. Crie uma variável chamada `idade` e atribua a ela o valor 25.
```javascript
let idade = 25;
```

4. Defina uma variável ``numeroDeVendas` e atribua a ela o valor 50.
```javascript
let numeroDeVendas = 50;
```

5. Defina uma variável `saldoDisponivel` e atribua a ela o valor 1000.
```javascript
let saldodisponivel = 1000;
```

6. Exiba um alerta com o texto "Erro! Preencha todos os campos."
```javascript
alert('Erro! Preencha todos os campos.');
```

7. Declare uma variável chamada `mensagemDeErro` e atribua a ela o valor "Erro! Preencha todos os campos." Agora exiba um alerta com o valor da variável `mensagemDeErro`.
```javascript
let mensagemDeErro = 'Erro! Preencha todos os campos.';
alert(mensagemDeErro);
```

8. Use um prompt para perguntar o nome do usuário e armazená-lo na variável `nome`.
```javascript
let nome = prompt('Digite seu nome');
```

9. Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável `idade`.
```javascript
let idade = prompt('Digite sua idade');
```

10. Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável `idade`. Agora, a idade seja maior ou igual que 18, exiba um alerta com a mensagem "Pode tirar a habilitação!".
```javascript
let idade = prompt('Digite sua idade');
if (idade >= 18) {
  alert('Pode tirar a habilitação!');
}
```