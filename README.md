# Docker Todo List

Essa aplicação foi feita usando um frontend em React pré-desenvolvido pela TRYBE, nosso objetivo era criar a conexão em backend.

![preview](.github/preview.gif)

Aplicação que consiste em fazer uma "Conteinerização" de aplicações de frontend, backend e testes com o uso de Docker, criando uma conexão entre elas e orquestrando seu funcionamento.

O projeto foi desenvolver uma aplicação em backend usando comandos Docker na CLI, criar as imagens Docker das aplicações, criar e executar contêineres Docker e orquestrar containeres utilizando o Docker Compose.


## 🚀 Tecnologia

- ⚡ Docker é uma plataforma open source que facilita a criação e administração de ambientes isolados dentro de um container.

## ✋🏻 Pré-requisitos

- [git](https://git-scm.com/downloads): Ferramenta para gerenciar o código-fonte

- [Visual Studio Code](https://code.visualstudio.com/): Editor de Código Fonte

- [Docker](https://www.docker.com/): Software de código aberto usado para implantar aplicativos dentro de containers virtuais.

## :hammer_and_wrench: Antes de iniciar o projeto.

No diretório do projeto, instale as dependências e inicialize o projeto:

### `npm install`

Instala as dependências.

### `cd docker`

Entra na pasta da aplicação.

### `docker-compose up -d`

Sobe e orquestra os containers.

### `docker attach docker_todotests_1`

Executa todos os testes presentes na aplicação.

Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo em seu navegador.
