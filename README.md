## INE5646 - 2023.1

#### Trabalho prático de implementação da disciplina INE5646 - Programação para Web, semestre 2023.1. A aplicação consiste em um `kanban board` simples, permitindo cadastro de tarefas e movimentação entre estágios (similar ao Trello)

<br/>

### Tecnologias utilizadas
- front-end em Vue.js
- backend em golang

### Requisitos para ambiente de desenvolvimento

- `golang`
- `make`
- `docker`
- `docker-compose` *version above 1.22.0*

#### Como rodar localmente

- Utilizando linha de comando
```sh
git clone git@github.com:nascivini/ine5646-20231.git
make Makefile.mk start
```
    
Para conectar no banco de dados do container:
- user: `postgres`
- password: `postgres`
- host: `localhost:5432`

#### Documentação das APIs
> [Swagger - TODO]()