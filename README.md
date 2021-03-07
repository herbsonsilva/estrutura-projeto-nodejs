<img alt="GoStack" src="https://images.unsplash.com/photo-1610547189313-1fbea2dcd059?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&h=300&q=80" />

<h2 align="center">
  Estrutura inicial para projetos com Node.js
</h2>

*<blockquote align="center">“Motivação é o que te faz começar, hábito é o que te faz continuar!"</blockquote>*

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/herbsonsilva/estrutura-projeto-node?color=blueviolet">

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/herbsonsilva/estrutura-projeto-node?color=blueviolet">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/herbsonsilva/estrutura-projeto-node?color=blueviolet">

  <a href="https://github.com/herbsonsilva/estrutura-projeto-node/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/herbsonsilva/estrutura-projeto-node?color=blueviolet">
  </a>

  <a href="https://github.com/herbsonsilva/estrutura-projeto-node/blob/master/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-blueviolet">
  </a>

  <a href="https://github.com/herbsonsilva/estrutura-projeto-node/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/herbsonsilva/estrutura-projeto-node?style=social">
  </a>
</p>

<p align="center">
  <a href="#rocket-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#shrug-como-utilizar">Como utilizar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-dependências">Dependências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#wrench-ferramentas">Ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-comandos-utilizados">Comandos utilizados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#scroll-licença">Licença</a>
</p>

## :rocket: Sobre

Repositório contendo toda configuração inicial necessária para começar a desenvolver um projeto com Node.js.

Desenvolvido conforme conhecimento adquirido nas aulas do GoStack Bootcamp da Rocketseat.

A idéia aqui é não ter que precisar configurar um novo projeto Node do zero, evitando a instalação de dependências e as  configurações necessárias para iniciar o desenvolvimento e testes da aplicação.

Logo abaixo você encontrará a relação das dependências, ferramentas e extenções utilizadas neste projeto.

## :shrug: Como utilizar

Faça o download do arquivo .zip e descompacte-o em um local de sua preferência ou clone o repositório e, no terminal, na pasta raiz do projeto, digite o comando `yarn` para baixar todas as dependências necessárias.

## :books: Dependências

Nome | Ambiente | Descrição
--- | --- | ---
**`typescript`** | Desenvolvimento | Uso de tipos.
**`express`** | Aplicação | Controle de rotas.
**`@types/express`** | Desenvolvimento | Tipagens do express.
**`ts-node-dev`** | Desenvolvimento | Converte typescript para javascript nativo e observa mudanças no código.

## :wrench: Ferramentas

Nome | Descrição
--- | ---
**`EditorConfig`** | Padroniza configurações entre diferentes editores de código.

## :computer: Comandos utilizados

Comando | Descrição
--- | ---
**`$ git init`** | Inicia o `controle de versão` do Git no projeto.
**`$ touch .gitignore`** | Cria o arquivo `.gitignore` que conterá a lista de arquivos e pastas a serem ignorados no controle de versão do projeto.
**`$ yarn init -y`** | Inicia o projeto criando o arquivo `package.json`
**`$ yarn add typescript -D`** | Adiciona o `typescript` como dependência de desenvolvimento.
**`$ yarn tsc --init`** | Inicializa o typescript criando o arquivo `tsconfig.json`
**`$ yarn add express`** | Adiciona o `express` como dependência da aplicação.
**`$ yarn add @types/express -D`** | Adiciona as declarações de tipos do `express` como dependência de desenvolvimento.
**`$ yarn add ts-node-dev -D`** | Adiciona funcionalidades de `conversão de código` typescript para javascript nativo como dependência de desenvolvimento. Também `observa as mudanças` no código realizando restart automático.

## :scroll: LICENÇA

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../master/LICENSE) para mais detalhes.

---

Feito com ♥ by [Herbson Silva](https://www.linkedin.com/in/herbsonsilva/) :wave::wave::wave:
