## 🏦 Sistema Bancário em Python (POO)

Este projeto implementa um **sistema bancário simples em Python**, desenvolvido durante o **Bootcamp Santander – Trilha Python (DIO)**.
O foco está na aplicação prática dos **princípios de Programação Orientada a Objetos (POO)**, simulando funcionalidades essenciais de um banco, como **criação de usuários e contas**, **depósitos**, **saques** e **emissão de extratos**.

---

## 📋 Funcionalidades

* 👤 Criar clientes (usuários)
* 🏦 Criar contas bancárias para clientes
* 💰 Realizar depósitos
* 💸 Realizar saques
* 📄 Consultar extrato de movimentações
* 📋 Listar contas cadastradas

---

## 🧠 Tecnologias e Conceitos Utilizados

* **Python 3.x**
* **Programação Orientada a Objetos (POO)**:

  * Herança
  * Encapsulamento
  * Polimorfismo
  * Abstração com `ABC`
* **Boas práticas de organização**:

  * Separação de responsabilidades
  * Classes bem definidas para regras de negócio

---

## 🗂️ Estrutura do Projeto

```text
sistema-bancario-poo/
├── sistema_bancario_POO.py   # Arquivo principal do sistema
└── README.md                 # Documentação do projeto
```

---

## ▶️ Como Executar

### Pré-requisitos

* Python **3.x** instalado no sistema

### Passos

1. Clone ou baixe este repositório.

2. Acesse a pasta do projeto:

```bash
cd sistema-bancario-poo
```

3. Execute o sistema:

```bash
python sistema_bancario_POO.py
```

*(ou `python3 sistema_bancario_POO.py`, dependendo do seu sistema operacional)*

---

## 💻 Interface via Menu

Ao executar o programa, um menu interativo é exibido no terminal:

```text
=============== MENU ===============
[d]    Depositar
[s]    Sacar
[e]    Extrato
[nc]   Nova conta
[lc]   Listar contas
[nu]   Novo usuário
[q]    Sair
```

---

## 👤 Clientes e Contas

* Cada cliente é identificado de forma única pelo **CPF**
* Um cliente pode possuir **múltiplas contas**
* Cada conta é uma instância da classe `ContaCorrente`
* O usuário pode escolher com qual conta deseja operar

---

## 📌 Regras de Negócio

* 💸 **Limite de saque:** R$ 500,00 por operação
* 🔢 **Quantidade máxima:** 3 saques por conta
* ✅ Depósitos e saques aceitam apenas valores **positivos**
* 📄 O extrato exibe:

  * Histórico completo de transações
  * **Data e hora**
  * Saldo final

---

## 🛠️ Possíveis Melhorias Futuras

* Persistência de dados em arquivos:

  * `JSON`
  * `CSV`
* Integração com banco de dados:

  * `SQLite`
  * `MySQL`
* Autenticação de usuários com **login e senha**
* Interface gráfica ou versão web do sistema

---

## ⭐ Considerações Finais

Este projeto é ideal para quem deseja praticar **POO em Python**, aplicando regras de negócio reais de forma organizada e didática.
Ótimo para compor **portfólio de estudos** e demonstrar evolução em programação.

---
