MongoDB com Node.js
===================

Curso de MongoDB com Node.JS da MongoDB University módulo M101JS.

Como iniciar um projeto MongoDB com Node.js

OBS: Crie um diretório que será o seu projeto, dentro dele teram os sequintes arquivos "app.js" e "package.json" que seram explicados mais a frente.

Passo 1

Precisa ter o arquivo "package.json" com algumas configurações:

{
  "name": "node-js",
  "version": "0.0.0",
  "description": "npm introduction",
  "version": "0.2.0",
  "main": "app.js",
  "dependencies": {
    "consolidate": "~0.9.1",
    "express": "~3.2.6",
    "mongodb": "~1.3.10"
  },
  "author": "Armando Couto",
  "license": "BSD"
}

E o arquivo "app.js" com essas configuraçÕes:

var express = require('express'),
    cons = require('consolidate'),
    mongodb = require('mongodb');

Passo 2

Ir no terminal e executar esses comandos:

npm install express

obs: Caso de algum erro pode ter haver com o package.json.

Passo 3

Será criado um diretório no diretório aonde você estava.

node_modules
	consolidate
	express
	mongodb
