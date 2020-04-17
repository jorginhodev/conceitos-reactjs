<h1 align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</h1>

<h3 align="center">
  Conceitos do ReactJS
</h3>

<p align="center">Desafio 03: Conceitos do ReactJS, aplicado no <a href="https://rocketseat.com.br/bootcamp">Bootcamp GoStack</a> 🎓</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalacao-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-sobre-o-desafio">Sobre o desafio</a>
</p>

## 🖥 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [ReactJS](https://reactjs.org/)
- [Axios](https://github.com/axios/axios)

## 🚀 Instalação e execução

1. Faça um clone desse repositório;
2. Entre na pasta rodando `cd conceitos-reactjs`;
3. Rode `yarn` para instalar as dependências;
4. Rode `yarn start` para iniciar o servidor;
5. Rode `yarn test` para rodar os testes.

## 🚀 Sobre o desafio

Nesse desafio, foi criada uma aplicação para treinar o que foi aprendido até agora no ReactJS!

Consiste em continuar desenvolvendo a aplicação que irá armazenar repositórios do portfólio, que foi desenvolvido o backend no último desafio utilizando o Node.js.

### Funcionalidades da aplicação

- **`Listar os repositórios da API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na API (foram adicionados a listagem os campos **url** e **techs**).

- **`Adicionar um repositório na API`**: Deve ser capaz de adicionar um novo item na API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do frontend e da API.

### Específicação dos testes

Em cada teste, tem uma breve descrição no que a aplicação deve cumprir para que o teste passe.

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, a aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, a aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.

Feito com 💜 by Jorge Ramos
