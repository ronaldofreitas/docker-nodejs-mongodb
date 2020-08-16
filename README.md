# docker-nodejs-mongodb
Aplicação com NodeJs (com PM2) e MongoDb rodando em containers Docker através do docker-composer


PM2 - O PM2 é uma ferramenta open source completa para o gerenciamento e deploy de aplicações Node
module esm - ECMAScript module loader, utilizado para permitir que o Node tenha acesso a features mais recentes do JS, uma alternativa ao Babel

Os comandos do docker-composer estarão separados no Makefile, facilitando a execução

Após clonar esse repositório, dentro da própria pasta execute: 

* levantar os containers (aplicação e banco)
$ make up 

* derrubar os containers
$ make down

* analisar logs
$ make logs

