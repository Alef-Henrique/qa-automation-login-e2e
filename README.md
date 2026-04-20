# Automação de Testes - Login E2E

Projeto de automação de testes web utilizando Java + Selenium + JUnit 5.

## Cenário automatizado

Login na plataforma:
https://plataforma.dev.e2etreinamentos.com.br/

## Bug encontrado

Durante os testes manuais foi identificado um comportamento inesperado:

Ao inserir credenciais válidas:

- o campo senha fica com borda vermelha
- é necessário clicar duas vezes no botão entrar
- somente após o segundo clique o login é realizado

Este comportamento indica falha na validação do formulário.

## Tecnologias utilizadas

- Java
- Selenium WebDriver
- JUnit 5
- Maven
- Page Object Model

## Estrutura do projeto

base
pages
tests

## Como executar o projeto

mvn test

## Autor

Alefe Silva
