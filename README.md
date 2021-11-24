# projeto
teste
BANCO DE DADOS MYSQL>>>

criar banco
CREATE SCHEMA `construpbd` ;

criar tabela

CREATE TABLE `construpbd`.`materiais` (
  `id` INT NOT NULL AUTO_INCREMENT,
  `nome` VARCHAR(45) NOT NULL,
  `descricao` VARCHAR(45) NOT NULL,
  `marca` VARCHAR(45) NOT NULL,
  `valor` VARCHAR(45) NOT NULL,
  `data` VARCHAR(10) NOT NULL,
  PRIMARY KEY (`id`));

APP>>>

Roda o npm install 

acesse a pasta API e execute npx nodemon

com OUTRO terminal acesse a pasta construp e execute npm rum serve

-----API rodara da porta 8080 e VUE na porta 8081----

