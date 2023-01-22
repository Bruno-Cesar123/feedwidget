<h1 align="center">FEEDWIDGET</h1>

<p align="center">
  <a href="#-descricao">Descrição</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar-backend">Como executar Backend</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

## 📜 Descrição

- API para envios de feedbacks com notificação de e-mail.

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Nodejs](https://nodejs.org/en/)
- [Mailtrap](https://mailtrap.io/)
- [Express](https://expressjs.com/pt-br/)
- [Typescript](https://www.typescriptlang.org/)
- [PRISMA](https://www.prisma.io/)
- [SQLITE](https://www.sqlite.org/index.html)
- [JEST](https://jestjs.io/pt-BR/)


## 🎲 Rodando o Projeto

```bash
# Clone este repositório
$ git clone https://github.com/Bruno-Cesar123/feedwidget_api.git

# Acesse a pasta do projeto no terminal/cmd
$ cd server

# Instale as dependências
$ npm install ou yarn

# Crie um arquivo .env e configure suas credenciais de acordo com o arquivo .env.example

# rode as migrations
$ npm run prisma migrate dev ou yarn prisma migrate dev

# Comando para rodar os teste
$ npm run test ou yarn test

# Execute a aplicação em modo de desenvolvimento
$ npm run dev ou yarn dev

# O servidor inciará na porta:3000 - acesse <http://localhost:3333>

```
- [front-end](https://github.com/Bruno-Cesar123/feedwidget_web)



Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](license) para mais detalhes.

---

Feito por **Bruno Cesar** [**LinkedIn**](https://www.linkedin.com/in/bruno-cesar-b0039715a/)