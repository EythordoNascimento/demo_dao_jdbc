# Projeto DAO JDBC - Demo

Este projeto é uma demonstração prática de acesso a banco de dados em Java utilizando o padrão **DAO (Data Access Object)**.  
O objetivo é implementar operações CRUD (Create, Read, Update, Delete) para entidades relacionadas a um sistema simples de vendas

---

## 📌 Estrutura do Projeto

- **Entidades**
  - `Department`: representa um departamento da empresa.
  - `Seller`: representa um vendedor, associado a um departamento.

- **DAO Interfaces**
  - `DepartmentDAO`: define operações de acesso a dados para a entidade `Department`.
  - `SellerDAO`: define operações de acesso a dados para a entidade `Seller`.

- **Implementações**
  - `DepartmentDaoJDBC`: implementação da interface usando JDBC.
  - `SellerDaoJDBC`: implementação da interface usando JDBC.

---

## 🚀 Funcionalidades

- Criar, atualizar, deletar e buscar departamentos.
- Criar, atualizar, deletar e buscar vendedores.
- Associação entre vendedores e departamentos.
- Uso de **PreparedStatement** para evitar SQL Injection.
- Tratamento de exceções com classes personalizadas.

---

## 🛠️ Tecnologias Utilizadas

- **Java SE**
- **JDBC**
- **MySQL** (ou outro banco relacional configurado em `db.properties`)
- **Eclipse IDE**
