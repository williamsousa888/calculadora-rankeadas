# 🧮 Calculadora de Partidas Rankeadas

Projeto desenvolvido como parte do desafio da plataforma [DIO - Digital Innovation One](https://www.dio.me/), com o objetivo de praticar lógica de programação com JavaScript.

## 📝 Descrição

A **Calculadora de Partidas Rankeadas** é uma função que recebe como parâmetros a quantidade de **vitórias** e **derrotas** de um jogador, calcula o **saldo de vitórias** e classifica o jogador em um **nível de ranque** com base na sua performance.

### ✅ Lógica utilizada:
- **Saldo de Vitórias** = `vitórias - derrotas`
- A classificação é feita conforme as regras abaixo:

| Vitórias           | Nível     |
|--------------------|-----------|
| Menor que 10       | Ferro     |
| 11 a 20            | Bronze    |
| 21 a 50            | Prata     |
| 51 a 80            | Ouro      |
| 81 a 90            | Diamante  |
| 91 a 100           | Lendário  |
| 101 ou mais        | Imortal   |

---

## 💻 Tecnologias Utilizadas

- JavaScript
- Node.js para execução

## 🎯 O que foi Entregue:

- Variáveis - Let 
- Estrutura de Decisões - if / else if
- Funções - function calcularRanking(){}
- Operadores - Operadores matemático(Subtração a-b);
  Operadores lógicos(&&);
  Operadores relacionais(<, >=, <=).
