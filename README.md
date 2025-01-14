<h1 align="center">
  <img alt="Ignite" src=".github/logo.png" width="200px" />
</h1>

<h3 align="center">
  Desafio: Refactoring de classes e typescript
</h3>

<p align="center">Aplicação para gestão de pratos disponíveis em um restaurante</p>

<p align="center">
  <a href="#como-executar-o-projeto">Como executar o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sobre-o-desafio">Sobre o Desafio</a>
</p>

<p align="center">Front-end</p>

<p align="center">
  <img src=".github/frontend.png" width="90%">
</p>

## Como executar o projeto

### Clonar este repositório

```bash
git clone https://github.com/eliasmcastro/rocketseat-ignite-reactjs-desafio-refactoring-classes-ts.git
```

### Requisitos

- [Node.js](https://nodejs.org) na versão 16.14.0
- [Yarn](https://yarnpkg.com) na versão 1.22.5

### Passos para a execução

**1. Executar aplicação**

Instalar as dependências do projeto

```bash
yarn
```

Iniciar a Fake API

```bash
yarn server
```

A Fake API começará a ser executado em http://localhost:3333

Iniciar o servidor de desenvolvimento

```bash
yarn start
```

A aplicação começará a ser executada em http://localhost:3000

## Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação já funcional onde o seu principal objetivo é realizar dois processos de migração: de Javascript para Typescript e de Class Components para Function Components.

### O que devo editar na aplicação?

Os arquivos que devem ser editados são:

- src/components/Food/index.jsx;
- src/components/Food/styles.js;
- src/components/Header/index.jsx;
- src/components/Header/styles.js;
- src/components/Input/index.jsx;
- src/components/Input/styles.js;
- src/components/Modal/index.jsx;
- src/components/ModalAddFood/index.jsx;
- src/components/ModalAddFood/styles.js;
- src/components/ModalEditFood/index.jsx;
- src/components/ModalEditFood/styles.js;
- src/pages/Dashboard/index.jsx;
- src/pages/Dashboard/styles.js;
- src/routes/index.jsx;
- src/services/api.js;
- src/styles/global.js;
- src/App.js;
- src/index.js.

Todos esses arquivos devem ser migrados de Javascript para Typescript. Além disso, os arquivos que possuírem componentes em classe devem ser migrados para componentes funcionais.

### Preparando ambiente Typescript

Como esse é um projeto CRA sem TypeScript, você primeiro precisar instalar as dependências/tipagens e configurar o TS. Nossa sugestão é criar um novo projeto CRA com Typescript e comparar a estrutura atual com a que você precisa ter. Realizando essa comparação, facilmente você consegue ver que:

- É preciso instalar o `typescript`
- É preciso criar um arquivo de configuração `tsconfig.json`. Inclusive, você pode utilizar a configuração gerada automaticamente no CRA template Typescript para criar o seu arquivo.
- É preciso criar um arquivo `react-app-env.d.ts` com o conteúdo:

```tsx
/// <reference types="react-scripts" />
```

- É preciso instalar as tipagens das bibliotecas.

Dica: [Componentes no React](https://efficient-sloth-d85.notion.site/Componentes-no-React-6644d41da663405cb29dcaae1693bb9f)