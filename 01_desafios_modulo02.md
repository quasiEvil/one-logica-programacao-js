# Resolução dos Desafios do Módulo 1
### Curso Lógica de Programação (Alura + Oracle Next Education)

👉🏻 Conceitos aplicados: variáveis, condicionais (if-else), loops (while) e interações com o usuário (alert, prompt).

#### Desafios e resoluções:
1. Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".
```javascript
let diaDaSemana = prompt('Que dia é hoje?');

if (diaDaSemana == 'Sábado' || diaDaSemana == 'Domingo') {
  alert('Bom dim de semana!');
} else {
  alert('Boa semana!');
}
```

2. Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
```javascript
let numero = prompt('Digite um número.');

if (numero < 0) {
  alert('O número é negativo');
} else {
  alert('O número é positivo');
}
```

3. Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
let pontos = 0;
```javascript
if (pontos >= 100) {
  alert('Parabéns, você venceu!');
} else {
  alert('Tente novamente para ganhar.');
}
```

4. Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
```javascript
let saldo = 300;
alert(`Seu saldo atual é: R$${saldo}`);
```

5. Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
```javascript
let userName = prompt('Digite seu nome');
alert(`Boas-vindas, ${userName}`);
```