# 🏦 Banco Digital - Hackathon Java

Bem-vindo ao **Banco Digital**, um projeto simples de simulação bancária em Java, desenvolvido para desafios de Hackathon. O sistema permite cadastro de clientes, criação de contas, depósitos, saques, transferências, consulta de saldo, extrato e listagem de clientes.

---

## 🚀 Funcionalidades

- 👤 Cadastro de clientes com verificação de CPF único
- 💳 Criação de contas bancárias com numeração automática
- 💰 Realização de depósitos
- 💸 Saques com validação de saldo
- 🔄 Transferência entre contas
- 📊 Consulta de saldo
- 🧾 Geração de extrato com data e tipo de transação
- 📋 Listagem de todos os clientes cadastrados

---

## 🧱 Estrutura do Projeto

```plaintext
br/com/BancoDigital/
├── BancoDigitalHackaton.java   # Classe principal com menu e lógica do sistema
├── Cliente.java                # Classe Cliente com CPF como identificador único
├── Conta.java                  # Classe Conta bancária com saldo e extrato
├── Transacao.java              # Classe Transação, registra operações financeiras

✨🏦=== MENU BANCO DIGITAL ===🏦✨
👤 1 - Cadastrar Cliente
💳 2 - Cadastrar Conta
💰 3 - Depósito
💸 4 - Saque
🔄 5 - Transferência
📊 6 - Consultar Saldo
🧾 7 - Extrato
📋 8 - Listar Clientes
🚪 9 - Sair
👉 Escolha: 

Tecnologias Utilizadas
Java 24
IntelliJ IDEA

## Observações

- O número das contas começa em 1001 e é incrementado automaticamente.
- O CPF é usado para identificar unicamente cada cliente.
- As transações armazenam informações como data, tipo, valor, e contas de origem e destino.
- O sistema não possui persistência, ou seja, os dados são perdidos ao fechar o programa.

---

## Autor

 — matheusdanireis@gmail.com

---
