📌 Sistema de Chamados – Spring Boot

API REST desenvolvida com Java e Spring Boot para gerenciar usuários e chamados, aplicando regras de negócio comuns em sistemas reais. O projeto inclui validação, relacionamentos, filtros e operações completas de CRUD.

🚀 Tecnologias

Java 17

Spring Boot:

  Spring Web

  Lombok

  Spring Dev Tools

  Spring Data JPA

  Bean Validation

PostgreSQL

🔧 Funcionalidades
Usuários

Criar, listar, buscar por ID, atualizar e remover

Impede exclusão caso seja solicitante/responsável de algum chamado

Chamados

Criar, listar, buscar por ID, atualizar e excluir

Status inicial ABERTO

Atualização automática de createdIn e updatedIn

Filtros:

  /chamados/status/{status}

  /chamados/solicitante/{id}

  /chamados/responsavel/{id}

📦 Como rodar
mvn spring-boot:run

📄 Sobre

Projeto criado para treino e portfólio, seguindo boas práticas de backend e lógica aplicada no mercado.
