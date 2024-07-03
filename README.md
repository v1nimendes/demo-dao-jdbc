# Projeto Java DAO 

Este projeto foi desenvolvido durante um curso abrangente de Java ministrado pelo porfessor Nelio Alves.
Ele demonstra conceitos-chave no desenvolvimento em Java, particularmente o padrão Data Access Object (DAO). O projeto envolve a gestão de entidades Seller e Department usando JDBC para operações de banco de dados.

## Introdução
Este projeto demonstra a implementação do padrão DAO para interagir com um banco de dados relacional. 
A aplicação gerencia vendedores e departamentos, fornecendo operações básicas de CRUD (Create, Read, Update, Delete). Serve como um exemplo prático de como estruturar uma aplicação Java com separação de responsabilidades, utilizando JDBC para acesso ao banco de dados.

## Tecnologias
•Java

•JDBC

•MySQL

•Maven

## Estrutura do Projeto
O projeto está organizado em vários pacotes:

•application: Contém as classes principais para executar a aplicação.

•db: Gerencia a conexão com o banco de dados e funções utilitárias.

•model.dao: Define interfaces DAO e classes de fábrica.

•model.dao.impl: Implementa interfaces DAO usando JDBC.

•model.entities: Define as entidades Seller e Department.

## Funcionalidades
### Operações de Vendedor
•Encontrar Vendedor por ID.

•Encontrar Vendedores por Departamento.

•Encontrar Todos os Vendedores.

•Inserir Vendedor.

•Atualizar Vendedor.
