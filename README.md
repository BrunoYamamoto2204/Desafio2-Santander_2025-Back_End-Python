# 💰 Desafio 2 - Sistema Bancário Simples em Python

Este é um projeto de sistema bancário desenvolvido para o **Bootcamp Santander 2025 - Back-End com Python**, com o objetivo de demonstrar a aplicação de conceitos fundamentais da linguagem Python e lógica de programação. O sistema simula operações bancárias básicas, como **depósito**, **saque**, **extrato**, **cadastro de usuários e contas**, além de **listagem dos dados cadastrados**.

---

## ⚙️ Funcionalidades

- **Depósito:** Permite adicionar fundos à conta, com validação para garantir que o valor seja positivo.
- **Saque:** Permite retirar dinheiro da conta, respeitando o saldo disponível, limite por operação e quantidade de saques diários.
- **Extrato:** Exibe todas as movimentações realizadas, com saldo atual.
- **Cadastro de Usuário:** Cadastra um novo usuário com CPF, nome, data de nascimento e endereço. O CPF é usado como chave única.
- **Cadastro de Conta:** Cria contas bancárias vinculadas a um usuário existente. Um usuário pode ter múltiplas contas.
- **Listagem de Contas:** Exibe todas as contas bancárias registradas, com número, agência, CPF e nome do titular.
- **Listagem de Usuários:** Exibe os usuários cadastrados, com seus dados pessoais.

---

## 🆕 Atualizações do Desafio 2

O código original foi **refatorado e expandido** com novas funcionalidades e estrutura modular:

- ✅ **Modularização com Funções:** O código foi dividido em funções para melhorar a legibilidade, reutilização e organização do sistema.
- ✅ **Criação de Usuários:** Agora é possível cadastrar usuários com nome, CPF, data de nascimento e endereço.
- ✅ **Validação por CPF:** O sistema impede o cadastro de usuários com CPF já existente.
- ✅ **Criação de Contas Bancárias:** Um usuário pode ter várias contas, mas cada conta pertence a um único usuário.
- ✅ **Listagem de Usuários e Contas:** É possível visualizar todos os usuários e suas contas associadas.
- ✅ **Melhoria na Interação com o Usuário:** O menu foi atualizado para incluir todas as operações disponíveis.

Essas atualizações visam aproximar o projeto de um sistema real, reforçando boas práticas de programação e separação de responsabilidades.

---

## 🚀 Como Executar

1. Certifique-se de que o **Python 3** está instalado na sua máquina.
2. Salve o código em um arquivo chamado, por exemplo, `banco.py`.
3. Execute no terminal com:

   ```bash
   python banco.py
   ```
4. Utilize o menu interativo para realizar operações como depósito, saque, cadastro e listagens.

📌 Regras do Sistema
- Só é possível sacar até 3 vezes por dia.
- O valor máximo por saque é de R$ 500.
- O usuário é identificado unicamente pelo CPF.
- Uma conta sempre pertence a apenas um usuário, mas um usuário pode ter várias contas.
---
## 🛠 Tecnologias Utilizadas
- Python: A linguagem de programação principal utilizada para desenvolver o sistema.
