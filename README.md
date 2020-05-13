# tcc-graphql

BackEnd

1 - No MySQL
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '12345678';
FLUSH PRIVILEGES;


2 - Executar no NodeJS 

* Baixar dependencias;
npm i

* Executar as migrations
npx knex migrate:latest

* Start
npm start


FrontEnd

1 - Executar no NodeJS 

* Baixar dependencias;
npm i

* Startar aplicação
npm run serve
