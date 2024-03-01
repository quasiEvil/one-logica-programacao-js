# Resolução dos Desafios do Módulo 1
### Curso Lógica de Programação (Alura + Oracle Next Education)

👉🏻 Conceitos aplicados: variáveis, condicionais (if-else), loops (while) e interações com o usuário (alert, prompt).

#### Desafios e resoluções:
1. Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.
```javascript
let contador = 1;

while (contador <= 10) {
  console.log(contador);
  contador++;
}
```

2. Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```javascript
let contador2 = 10;

while (contador2 >= 0) {
  console.log(contador2);
  contador2--;
}
```

3. Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```javascript
let numero = prompt('Digite um número positivo');

while (numero >= 0) {
  console.log(numero);
  numero--;
}
```

4. Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```javascript
let numero2 = prompt('Digite um número positivo');
let contador3 = 0;

while (contador3 <= numero2) {
  console.log(contador3);
  contador3++;
}
```