# Banco Digital com Java e Programação Orientada a Objetos (POO)

Este projeto é uma implementação prática dos pilares da Programação Orientada a Objetos (POO) em Java, simulando o funcionamento básico de um banco digital. A proposta segue como referência o projeto original de [falvojr/dio-live-20210802](https://github.com/falvojr/dio-live-20210802), com possíveis melhorias e personalizações.

## 💡 Objetivo

Reforçar os conhecimentos em POO com Java, praticando os quatro pilares fundamentais:

- **Abstração**
- **Encapsulamento**
- **Herança**
- **Polimorfismo**

## 🧱 Estrutura do Projeto

O projeto está organizado com as seguintes classes e interfaces:

- `IConta`: Interface que define o comportamento básico de uma conta bancária.
- `Conta`: Classe abstrata que implementa a interface `IConta` com comportamento comum.
- `ContaCorrente`: Herda de `Conta` e representa uma conta corrente.
- `ContaPoupanca`: Herda de `Conta` e representa uma conta poupança.
- `Cliente`: Armazena informações do titular da conta.
- `Banco`: Armazena uma lista de contas vinculadas ao banco.
- `Main`: Executa uma simulação de uso do sistema.

## 📦 Funcionalidades

- Criar contas correntes e poupança.
- Realizar depósito, saque e transferência entre contas.
- Emitir extrato com informações da conta.

## 📁 Estrutura de Arquivos
```
uml-banco-digital/
│
├── src/
├── Banco.java
├── Cliente.java
├── Conta.java
├── ContaCorrente.java
├── ContaPoupanca.java
├── IConta.java
└── Main.java
```

## ✍️ Autor

Desenvolvido por **Geovanni Marques** 🚀  
Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/geovanni-marques/)