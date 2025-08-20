# 💰 Sistema Bancário em Python - Versão 2

Este projeto foi desenvolvido como parte de um **desafio prático da DIO (Digital Innovation One)**.  
O objetivo foi **modularizar o sistema bancário** e adicionar novas funcionalidades, aplicando boas práticas de organização em Python.  
Assim como na versão inicial, não foi utilizado banco de dados ou bibliotecas externas — apenas lógica de programação.

## 🚀 Funcionalidades

O sistema simula um caixa eletrônico e agora conta com as seguintes operações:

- **Depósito** 💵  
  - Função que recebe argumentos apenas por **posição**
- **Saque** 🏧  
  - Função que recebe argumentos apenas por **nome**
  - Limite de R$ 500 por saque
  - Máximo de 5 saques diários
- **Extrato** 📄  
  - Função que mistura argumentos **posicionais e nomeados**
  - Lista todas as movimentações realizadas e mostra o saldo atual
- **Cadastro de Usuário** 👤  
  - Armazena nome, CPF (apenas números), data de nascimento e endereço
  - Garante que não haja dois usuários com o mesmo CPF
- **Cadastro de Conta Corrente** 🏦  
  - Vincula uma conta a um usuário já existente
  - Número da conta é sequencial (iniciando em 1)
  - Agência fixa: `0001`
  - Um usuário pode ter várias contas
- **Listar Contas** 📋  
  - Exibe todas as contas criadas com seus respectivos titulares
- **Sair do sistema** ❌  
  - Encerramento com confirmação antes de sair

## 🧠 Aprendizados

Este desafio permitiu reforçar conceitos importantes como:

- Criação e chamada de funções em Python
- Passagem de parâmetros de diferentes formas:
  - Apenas por posição (`/`)
  - Apenas por nome (`*`)
  - Combinação de ambos
- Estruturação e modularização do código
- Manipulação de listas e dicionários para armazenar dados
- Organização de um sistema que simula múltiplos usuários e contas bancárias

## 🛠 Tecnologias Utilizadas

- **Python 3**

## 📦 Como executar

1. Certifique-se de ter o Python instalado.
2. Clone este repositório:
```bash
https://github.com/Lipebarreiro/Sistema_bancario_DIO_v2.git
