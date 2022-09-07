# Repositório do projeto Docker ToDo List!

Bloco 19 - Docker: Utilizando Containers

## Habilidades

  * Usar comandos dockers no CLI - Interface de linha de comando;
  * Criar um contêiner Docker para uma aplicação de front-end;
  * Criar um contêiner Docker para uma aplicação de back-end;
  * Criar um contêiner Docker para uma aplicação de testes;
  * Orquestrar os três contêineres utilizando o Docker compose.

---

## O que foi desenvolvido

Foram "conteinerizadas" as aplicações de frontend, backend e testes fornecidas pela Trybe e criada uma conexão entre elas orquestrando seu funcionamento. Este repositório contém uma série de comandos ultilizados para "conteinerizar" uma aplicação.

---

## Instruções
**⚠️ Importante ⚠️**
Para que funcione corretamente, é importante que a instalação do Docker seja feita corretamente.
Aqui também é importante que o seu usuário esteja no grupo `docker` (para que não haja a necessidade de rodar comandos utilizando o `sudo`)

Nesse projeto, temos uma aplicação completa *(Um aplicativo de tarefas)* que precisa ser conteinerizada para funcionar, aqui, forma desenvolvidos os respectivos arquivos de configuração para cada frente específica: `Front-end`, `Back-end` e no nosso caso um aplicativo de teste que deve validar se as aplicações estão se comunicando.

1. Clone o repositório
  * `git@github.com:matteusfernandes/docker-todo-list.git`.

2. Entre na pasta do repositório que você acabou de clonar:
  * `cd docker-todo-list`

3. Instale as dependências
  * `npm install`
---

## Comandos docker

#### 1. Cria um novo container de modo interativo sem roda-lo nomeando-o como `01container` utilizando a imagem `alpine` usando a versão `3.12`

#### 2. Inicia o container `01container`

#### 3. Lista os containers filtrando pelo nome `01container`

#### 4. Executa o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

#### 5. Remove o container `01container` que está em andamento.

#### 6. Faz o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.

#### 7. Roda um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.

#### 8. Para o container `02images` que está em andamento.
---

## Dockerfile

#### 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.

#### 10. Gera uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.

#### 11.Gera uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.
---

### Docker-compose

#### 12. Sube uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.

---

## Linter

Para garantir a qualidade do código, foi utilizado neste projeto o  [ESLint](https://eslint.org/). Assim o código está alinhado com as boas práticas de desenvolvimento, sendo mais legível e de fácil manutenção! 

Este projeto já vem com as dependências relacionadas ao _linter_ configuradas no arquivo `package.json`.

Para poder rodar o `ESLint` no projeto basta executar o comando `npm install` dentro do projeto e depois `npm run lint`. Se a análise do `ESLint` encontrar problemas no seu código, tais problemas serão mostrados no seu terminal. Se não houver problema no seu código, nada será impresso no seu terminal.

Você pode ler mais sobre o `EsLint` e como instalá-lo [aqui](https://app.betrybe.com/course/real-life-engineer/eslint) ou também pode ir em extensions e baixar o [plugin `ESLint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) no `VSCode`.

---

#### Para visualizar o **Pull Request** original aberto no repositório da Trybe e tomar nota da avaliação e dos testes, acesse: [Docker ToDo List](https://github.com/tryber/sd-013-b-project-docker-todo-list/pull/48)
#### 💻 **Desenvolvido por** [@matteusfernandes](https://github.com/matteusfernandes) • 2022 🔗 [LinkedIn](https://www.linkedin.com/in/matteusfernandes/)
