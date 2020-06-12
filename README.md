# tcc-graphql

Vídeo:
https://drive.google.com/file/d/11TY1NUOALq5tFd4owhuY-eLMKQaPbkRW/view

Procedimento:

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

