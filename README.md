# Cálculo de Área com POO
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-%20Finalizado-green?style=for-the-badge)

Este projeto foi o meu primeiro programa utilizando classes e métodos para entender como a **Programação Orientada a Objetos (POO)** funciona na prática com Java. 

O objetivo é ler as medidas de dois triângulos, calcular suas áreas e exibir os resultados, utilizando classes para representar o objeto.

## O que este projeto demonstra:
* **Criação de Classes**: A classe `Triangle` define os atributos de um triângulo (lados a, b, c).
* **Métodos com Retorno**: O cálculo da área foi isolado em um método dentro da classe `Triangle`.
* **Reutilização de Código**: Em vez de repetir a fórmula duas vezes no código principal, basta chamar `x.area()` e `y.area()`.

## Tecnologias
* Java 21 (JDK)
* IDE Eclipse

## Como funciona o cálculo
A área é calculada através da Fórmula:
$$p = \frac{a + b + c}{2}$$
$$area =  \sqrt{p(p - a)(p - b)(p - c)}$$
