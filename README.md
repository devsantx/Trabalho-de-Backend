
---

# API de Controle de Pessoas

Kauan Alves — 01710611  
Wesley José — 01709983

## 📄 Visão Geral

Esta aplicação expõe uma API REST voltada ao gerenciamento de pessoas no contexto universitário. O propósito do projeto é colocar em prática os conhecimentos adquiridos em desenvolvimento com Spring Boot e integração com banco de dados MySQL.

O sistema trabalha com uma única entidade, chamada **Pessoa**, composta pelos seguintes atributos:

- nome  
- cpf  
- idade  

---

## 🛠️ Tecnologias e Ferramentas

- Java  
- Spring Boot (módulos Spring Web e Spring Data JPA)  
- MySQL  
- Lombok  
- Maven  

---

## 🗂️ Estrutura de Componentes

A aplicação está organizada nos seguintes módulos:

- **Entidade (Entity):** Classe `Pessoa`, que modela a estrutura da tabela no banco.  
- **DTO (Data Transfer Object):** Classe `PessoaDTO`, usada para transportar os dados da entidade.  
- **Repositório:** Interface `PessoaRepository`, que herda de `JpaRepository` para operações no banco.  
- **Controlador (Controller):** Classe `PessoaController`, onde estão definidos os endpoints da API.  

---

## 🔗 Rotas da API

- `POST /api/pessoas`  
  Registra uma nova pessoa na base de dados.

- `GET /api/pessoas/{id}`  
  Busca os dados de uma pessoa a partir de seu identificador único.

---
