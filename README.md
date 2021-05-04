<h1 align="center">Chatty 📣</h1>

<p align="center">
    Projeto desenvolvido durante a 5º Edição do Evento Next Level Week (Trilha Node JS), da Rocketseat, com a Instrutora <a href="https://github.com/danileao">Daniele Leão</a>. 🚀
</p>

<p align="center">
    <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=00008B&labelColor=000000&style=for-the-badge" />
    <img src="https://img.shields.io/static/v1?label=rocketseat&message=NLW05&color=00008B&labelColor=000000&style=for-the-badge" />
</p>

<p align="center">
    <a href="#-o-projeto">O Projeto</a> •
    <a href="#-tecnologias">Tecnologias</a> •
    <a href="#-como-usar">Como Usar</a> •
    <a href="#-licença">Licença</a>
</p>

<h2>🚀 O Projeto</h2>

<p>O projeto Chatty é um chat em tempo real, onde os clientes podem entrar em contato e os atendentes podem conversar com eles.</p>

<h2>🔨 Tecnologias</h2>

<p>O projeto foi desenvolvido utilizando as seguintes tecnologias:</p>

- [Node.js](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Socket.io](https://github.com/socketio/socket.io)
- [SQLite3](https://www.sqlite.org/index.html)
- [TypeORM](https://typeorm.io/#/)
- [UUID](https://www.npmjs.com/package/uuid)
- [DBeaver](https://dbeaver.io/)

<h2>🔧 Como Usar</h2>

<h3>Pré-Requisitos</h3>

<p>Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:</p>

- [GIT](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)
- [VSCode](https://code.visualstudio.com/)

<p>Caso não queira o npm como o seu gerenciador de pacotes, pode utilizar também o:</p>

- [Yarn](https://yarnpkg.com/)

<h3>Rodando o Servidor</h3>

```bash
# Clone este repositório
$ git clone https://github.com/guilhermegregory/rocketseat-nlw05-nodejs

# Acesse a pasta do projeto pelo terminal
$ cd rocketseat-nlw05-nodejs

# Instale as dependências com yarn
$ yarn add

# Ou, se preferir, instale as dependências com npm
$ npm install

# Rode as migrations com yarn
$ yarn typeorm migration:run

# Ou, se preferir, rode as migrations com npx
$ npx typeorm migration:run

# Inicie o servidor com yarn
$ yarn dev

# Ou, se preferir, inicie o servidor com npm
$ npm run dev

# O servidor iniciará na porta 3333 - acesse http://localhost:3333/
```
<h2>📄 Licença</h2>

<p>
    Este projeto está sob a licença MIT. Para mais detalhes, veja o arquivo <a href="LICENSE.md">LICENSE</a>.
</p>

---

<h4 align="center">
    Feito com 💙 by <a href="https://www.linkedin.com/in/guilherme-gregory-3873b1171/">Guilherme Gregory</a>.
</h4>