# 🎬 Gerenciador de Filmes - Projeto de Treino MVC em Java

Este é um projeto simples desenvolvido com o objetivo de treinar e entender a arquitetura MVC utilizando Java puro, sem frameworks. O projeto simula um gerenciador de filmes com uma funcionalidade básica.

## 📌 Objetivo

- Praticar a separação de responsabilidades usando o padrão MVC.
- Exercitar a criação de classes em Java com boas práticas.
- Compreender a interação entre Model, View e Controller.

## 🧱 Arquitetura

O projeto é dividido nas seguintes camadas:

- **Model**: Representa a entidade `Filme` com atributos como título, diretor e ano.
- **Controller**: A classe `FilmeController` possui o método `addFilme`, que realiza a adição de novos filmes.
- **Service**: Camada intermediária que contém as regras de negócio.
- **Repository**: Responsável por armazenar os dados dos filmes (simulado em memória).

## 🚀 Funcionalidade

Atualmente, o projeto permite:

- Adicionar um novo filme à lista por meio do método `addFilme` no `FilmeController`.
