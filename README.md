# Projeto
Projeto integrado 

### Criação física da base de Dados.

CREATE SCHEMA IF NOT EXISTS totaI_heaIth DEFAULT CHARACTER SET utf8 ;
USE ”Total_health”

CREATE TABLE IF NOT EXISTS TotaI_heaIth”.”GrupoDeAIimentos” (
”idGrupoAlimentos INT NOT NULL AUTO_INCREMENT, Nome VARCHAR(30) NOT NULL,
PRIMARY KEY ( idGrupoAlimentos ));

CREATE TABLE IF NOT EXISTS Total_health . Alimentos (
idAlimentos INT NOT NULL AUTO_INCREMENT, Nome VARCHAR(80) NOT NULL, ”Quantidade” DOUBLE(3,1) NOT NULL,
GrupoDeAIimentos_idGrupoAIimentos” INT NOT NULL,
PRIMARY KEY ( idAlimentos ),
FOREIGN KEY ( GrupoDeAIimentos_idGrupoAIimentos”)
REFERENCES ”TotaI_heaIth”.”GrupoDeAIimentos ( idGrupoAlimentos )):

CREATE TABLE IF NOT EXISTS Total_health”.”Nutricionista” (
idNutricionista INT NOT NULL AUTO_INCREMENT, Nome VARCHAR(45) NOT NULL,
”Nascimento DATE NOT NULL,
'DataCadastro'TIMESTAMP NULL DEFAULT CURRENT_TIMESTAMP,
'Especialidade' VARCHAR (30) NULL,
PRIMARY KEY ('idNutricionista));

CREATE TABLE IF NOT EXISTS 'To-al_head-h'.'Usuario'(
'idUsuario' INT NOT NULL AUTO_INCREMENT,
'Nome' VARCHAR(45) NOT NULL,

       
         



