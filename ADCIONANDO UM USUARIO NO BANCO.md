# CursoNodeJsAula06
CONECTANDO O ARQUIVO APP.JS AO BANCO DE DADOS MySQL ( Workbench)
Adcionando um usuario para acesso ao banco de dados
PASSO 1º
CREATE USER 'jader'@'localhost' IDENTIFIED WITH mysql_native_password BY '123456';

PASSO 2º
ADCIONANDO A PERMISSAO
GRANT ALL PRIVILEGES ON *.* 'jader'@'localhost'; 


3º PASSO
PASSANDO INFORMAÇÕES PARA DENTRO DA TABELA ATRAVES DO TERMINAL
INSERT INTO users (nome, email) VALUES ('jader','jader@gmail.com')
