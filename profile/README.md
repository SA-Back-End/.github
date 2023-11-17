# Skills
_Conectando para o futuro!_

A Skills é uma plataforma sem fins lucrativos para pessoas que buscam se desafiar em qualquer área para crescer pessoal e profissionalmente, através da experiência do desenvolvimento de projetos em equipes. Possibilitamos que os usuários encontrem parceiros ideais para colaborar com seus projetos pessoais através da análise de preferências e características de perfis compatíveis que facilitam sua busca.

Somos um projeto desenvolvido pela turma do SENAI/SC de Aprendizagem Industrial para Programação Back-End com o objetivo de colocar em prática nossos conhecimentos adquiridos durante o curso e exibi-los na amostra de inovação “Mundo Senai” do ano de 2023, estimulando nossos sentidos de criatividade, lógica e inovação.

<br>

## Tech

O projeto utiliza vários projetos de código aberto para funcionar corretamente:

- [ReactJS](https://react.dev/) - Sistema web responsivo para diferentes plataformas.
- [NestJS](https://nestjs.com/) - API e sistema de Back-End do projeto.
  [Prisma](https://www.prisma.io/) - ORM para PostgreSQL
- [Swagger](https://swagger.io/) - Design, Desenvolvimento, Documentação, Teste e Virtualização da API. 
- [JWT](https://jwt.io/) - Sistema de autenticação/autorização de usuário.
- [PostgreSQL](https://www.postgresql.org/) - Banco de Dados relacional do projeto.

E é claro que o próprio projeto é open source com um [repositório público](https://github.com/SA-Back-End) no GitHub.

<br>

## Instalação

Skills precisa do [Node.js](https://nodejs.org/) em sua versão v10+ para rodar.

Instale todas as dependências necessárias e inicie o servidor:

```sh 
# Na pasta do projeto

# Para instalar as dependências da API e rodá-la
cd Back-End
npm i
npx prisam migrate dev --name init
npm run start:dev
```
### *Atenção*
Para rodar a API localmente, certifique-se de alterar o arquivo `.env` do projeto para as especificações do seu banco de dados. No exemplo abaixo, é utilizado o usuário `postgres` com a senha `postgres` na porta local 5432. Além disso, tem-se o nome do banco como `minhaDB`.
```sh 
DATABASE_URL="postgresql://postgres:senai@localhost:5432/minhaDB?schema=public"
```

<br>

Como modelo para substituir as informações pelas suas, segue abaixo um link com os espaços onde se deve substituir. 
```sh 
DATABASE_URL="postgresql://<seuUsuario>:<suaSenha>@localhost:<porta>/<nomeDoBanco>?schema=public"
```

<br>

```
# Na pasta do projeto

# Para instalar as dependências do Front-End e rodá-lo
cd Front-End
npm i
npm start
```
