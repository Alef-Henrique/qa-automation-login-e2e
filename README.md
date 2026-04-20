# 🧪 Automação de Testes - Login (E2E Treinamentos)

Projeto de automação de testes web utilizando **Java + Selenium WebDriver + JUnit 5**, com foco em validação de fluxo de login e identificação de bug real.

---

## 🔍 Objetivo

Validar o comportamento do fluxo de autenticação da plataforma:

https://plataforma.dev.e2etreinamentos.com.br/

---

## 🐞 Bug identificado

Durante testes manuais, foi encontrado o seguinte problema:

Ao inserir credenciais válidas:

- o campo senha é destacado com borda vermelha
- o sistema indica erro visual indevido
- é necessário clicar duas vezes no botão **"Entrar"**
- somente após o segundo clique o login é realizado

---

## 📊 Impacto

- experiência do usuário prejudicada
- comportamento inconsistente
- possível aumento de erros percebidos pelo usuário

---

## 🧪 Cenários automatizados

- ✅ Login com sucesso
- ⚠️ Tratativa para bug de duplo clique
- (em evolução)
  - ❌ Login inválido
  - ❌ Campos obrigatórios
  - ❌ Senha incorreta

---

## 🧰 Tecnologias utilizadas

- Java 17
- Selenium WebDriver
- JUnit 5
- Maven
- Page Object Model (POM)

Álefe Silva
