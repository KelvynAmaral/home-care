# <p align="justify">💻 Sobre o projeto</p>
Med Voll é uma APIRest de uma clínica médica. O aplicativo deve possuir funcionalidades que permitam o cadastro de médicos e de pacientes, e também o agendamento e cancelamento de consultas.


## :hammer: Funcionalidades do projeto

- `Funcionalidade 1`: Cadastro de Médicos
- `Funcionalidade 2`: Cadastro de Pacientes
- `Funcionalidade 2a`: Agendamento de consultas
- `Funcionalidade 3`: Cancelamento de consultas


## Pré-requisitos

:warning: JAVA - MySQL

## Como rodar a aplicação :arrow_forward:

No terminal, clone o projeto:
```
$ git clone https://github.com/MineiroDev/med-voll.git
```
Crie um banco de dados com o nome "vollmed_api" no seu Mysql - create database vollmed_api;

## Deploy da Aplicação no Terminal :dash:

```java -Dspring.profiles.active=prod -DDATASOURCE_URL=jdbc:mysql://localhost/vollmed_api -DDATASOURCE_USERNAME="seu usuario do mysql" -DDATASOURCE_PASSWORD="sua senha do mysql" -jar target/api-0.0.1-SNAPSHOT.jar```

## 🎨 Layout
O layout da aplicação mobile está disponível neste link: 

## 🛠 Tecnologias
As seguintes tecnologias foram utilizadas no desenvolvimento da API Rest do projeto:

Java 17- Spring Boot 3 - Maven - MySQL - Hibernate - Flyway - Lombok


<img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
