# Aula Prática de TDD

Este repositório contém a implementação do exercício de TDD (Test-Driven Development) baseado no livro de Kent Beck, adaptado pelo Prof. Marco Tulio Valente para a disciplina de Engenharia de Software Moderna.

## Objetivo
Reproduzir uma sessão de desenvolvimento de software seguindo o fluxo TDD (Red, Green, Refactor), evoluindo o código desde a implementação básica de uma classe `Dollar` até uma estrutura consolidada na classe `Money`, capaz de manipular diferentes moedas e realizar operações matemáticas.

## Resumo das Etapas (Roteiro)
O desenvolvimento seguiu os passos do Capítulo 1 ao 11 do livro original:

1.  **Vermelho (Red)**: Criação de testes falhos (ex: `testMultiplication`, `testEquality`).
2.  **Verde (Green)**: Implementação simples para fazer os testes passarem.
3.  **Refactor**: Melhoria do design, incluindo:
    *   Criação de superclasse `Money`.
    *   Extração de lógica para métodos fábrica (`Money.dollar`, `Money.franc`).
    *   Remoção de duplicação através da consolidação de subclasses (`Dollar`, `Franc`) na classe `Money`.
    *   Tratamento de moedas (`currency`) e igualdade de objetos.

## Estrutura do Projeto
*   `Money.java`: Classe final que encapsula a lógica de valor e moeda.
*   `MoneyTest.java`: Suite de testes unitários em JUnit.

## Como executar
O projeto foi desenvolvido em Java. Para rodar os testes, recomenda-se o uso de uma IDE (IntelliJ, Eclipse) ou compilador online configurado com JUnit.
