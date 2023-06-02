# CursoNodeJsAula06
COMANDOS PARA SEREM UTILIZADOS.

CRIANDO A node_modules
1- PASSO
npm install express --save

2- PASSO
npm istall -g nodemon




CONECTANDO O ARQUIVO APP.JS AO BANCO DE DADOS MySQL ( Workbench)
Adcionando um usuario para acesso ao banco de dados
PASSO 1º
CREATE USER 'jader'@'localhost' IDENTIFIED WITH mysql_native_password BY '123456';

PASSO 2º
ADCIONANDO A PERMISSAO
GRANT ALL PRIVILEGES ON *.* TO 'jader'@'localhost'; 


3º PASSO
PASSANDO INFORMAÇÕES PARA DENTRO DA TABELA ATRAVES DO TERMINAL
INSERT INTO users (nome, email) VALUES ('jader','jader@gmail.com')

4ª CRIANDO UM USUARIO
CREATE USER 'usuario'@'localhost' IDENTIFIED WITH mysql_native_password BY 'senha do banco de dados'

5ª Liberando privilegios para o usuario no banco: 
GRANT ALL PRIVILEGES ON * . * TO ' jader'@'localhost'; 
