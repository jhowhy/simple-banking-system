# Sistema Bancário - Desafio Python

## Descrição
Fomos contratados por um grande banco para desenvolver seu novo sistema bancário. O objetivo é modernizar as operações utilizando a linguagem Python.  

A primeira versão do sistema (V1) implementa **três operações básicas**: depósito, saque e extrato.  

Este desafio faz parte da **Digital Innovation One (DIO)**, em parceria com a **Santander Open Academy**.

---

## Funcionalidades

### 1. Depósito
- Permite depositar valores **positivos** na conta bancária.
- A V1 do projeto trabalha apenas com **um usuário**, portanto não é necessário informar agência ou número da conta.
- Todos os depósitos são armazenados em uma variável e exibidos na operação de extrato.

### 2. Saque
- Permite realizar até **3 saques diários**.
- Limite máximo de **R$ 500,00 por saque**.
- Caso o saldo seja insuficiente, o sistema exibe uma mensagem informando que não é possível realizar o saque.
- Todos os saques são armazenados em uma variável e exibidos na operação de extrato.

### 3. Extrato
- Lista todos os depósitos e saques realizados na conta.
- Ao final, exibe o **saldo atual**.
- Se não houver movimentações, exibe a mensagem:  
  `Não foram realizadas movimentações.`
- Todos os valores são exibidos no formato `R$ XXX.xx`, por exemplo: `1500.45 = R$ 1500.45`.

---

## Regras do Sistema
1. Apenas um usuário.
2. Depósitos devem ser positivos.
3. Limite de 3 saques por dia.
4. Limite de saque de R$ 500,00.
5. Saldo insuficiente impede saque.
