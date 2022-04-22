<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/jcleston/modulo1">  
  <a href="https://github.com/jcleston/modulo1/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/jcleston/modulo1">
  </a>
   <a href="https://github.com/jcleston/modulo1/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/jcleston/modulo1?style=social">
  </a>
  <a href="https://www.linkedin.com/in/janescleston/">
    <img alt="Feito por Janes Cleston" src="https://img.shields.io/badge/feito%20por-Janes%20Cleston-%237519C1">
  </a>
</p>

# crud-nodejs-express-typeorm-postgresql
Crud completo com NodeJs + Express + TypeORM + PostgreSQL 🚀


express
typescript
typeORM

## Menu Geral
<!--ts-->
* [Instalação](#instalação)
    * [Express](#express)
    * [Typescript](#typescript)
    * [TypeORM](#typeorm)
* [Execução](#execução)
    
<!--te-->
<br /><br />

## Instalação
Para iniciar o desenvolvimento, é necessário efetuar as seguintes instalações:

```shell
//Criar o package.jsom
$ yarn init -y
```

## Express
```shell
$ yarn add express
```
## Typescript
```shell
$ yarn add typescript ts-node-dev @types/express -D
```
Para iniciar o Typescript execute o comando:
```shell
$ yarn tsc --init
```

Configure o arquivo tsconfig.json com o seguintes parâmetros:
```shell
"target": "es2021"
"strict": false
```

## TypeORM
```shell
$ yarn add typeorm reflect-metadata pg



```
Documentação oficial no link: <a href="https://typeorm.io/">typeorm.io</a>

## Execução
//Rode o seguinte comando no diretório raiz do projeto
```shell
$ yarn dev
ou 
$ yarn ts-node-dev --transpile-only src/server.ts
```