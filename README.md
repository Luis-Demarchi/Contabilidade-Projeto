# Contabilidade-Projeto
Novo projeto realizado em React, Typescript e Express, com conexão no MySql utilizando o Prisma, e também utilizando Docker.

First I am configuring the database with prisma, to install in the run development environment:
npm i prisma -D

And start the prisma with your database environment:
npx prisma init --datasource-provider mysql

To migrate to main application, i runned:
npx prisma migrate dev
