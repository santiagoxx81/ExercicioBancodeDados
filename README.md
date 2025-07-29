# 📦 Sistema de Vendas — Projeto de Banco de Dados (MySQL)

Este repositório contém o desenvolvimento completo de um sistema de banco de dados relacional simulado, voltado para o controle de vendas online, utilizando MySQL. O projeto foi estruturado seguindo as etapas de modelagem conceitual, lógica, física e consultas SQL.

---

## ✅ Etapas do Projeto

### 1. 📘 Modelo Conceitual
O modelo conceitual foi criado com base em 4 entidades principais:
- **Cliente**
- **Produto**
- **Pedido**
- **Pagamento**

#### Relacionamentos:
- Um cliente realiza vários pedidos.
- Cada pedido contém um único produto (modelo simplificado).
- Cada pedido possui exatamente um pagamento.

### 2. 📗 Modelo Lógico
A modelagem lógica foi construída no BR Modelo com as seguintes chaves:
- Chaves primárias (`PK`) definidas para cada tabela.
- Chaves estrangeiras (`FK`) para garantir integridade referencial entre as entidades.

### 3. 📙 Modelo Físico
Implementação do banco no MySQL com:
- Criação do banco e tabelas.
- Inserção de **10 registros por tabela**.
- Todas as restrições de integridade aplicadas corretamente.

Arquivo disponível: `modelo_vendas.sql`

---

## 📊 Consultas SQL

Foram desenvolvidas **32 consultas SQL**, cobrindo:

| Critério | Descrição |
|---------|-----------|
| Q1      | 2 consultas com `SELECT` e `WHERE` |
| Q2      | 2 consultas com `GROUP BY` e `ORDER BY` com funções de agregação |
| Q3      | 2 consultas com operadores aritméticos |
| Q4      | 3 consultas com operadores de comparação |
| Q5      | 3 consultas com operadores lógicos `AND`/`OR` |
| Q6      | 2 consultas com `NOT` |
| Q7      | 3 consultas com operadores auxiliares: `LIKE`, `BETWEEN`, `IN` |
| Q8      | 3 consultas com funções agregadas (`SUM`, `AVG`, etc.) |
| Q9      | 2 consultas com funções de data (`NOW()`, `YEAR()`, etc.) |
| Q10     | 3 subconsultas e união de dados com `IN`, `UNION` e agregação simples |
| Q11     | 3 consultas com `JOIN` |
| Q12     | 4 consultas com tipos de `JOIN`: `INNER`, `LEFT`, `RIGHT` |

Arquivo disponível: `consultas.sql`

---

## 🧰 Tecnologias Utilizadas

- MySQL 8.x
- BR Modelo (para modelagem)

