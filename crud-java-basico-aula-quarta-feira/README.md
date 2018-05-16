
Crud Basico usando JTABLES e componentes do Swing toolkit em java, insercao, atualizacao.

O dump do banco esta junto 

```sql
create database db_usuario;

use db_usuario;

CREATE TABLE usuario (
id BIGINT(10) AUTO_INCREMENT,
nome VARCHAR(255),
cpf VARCHAR(255),
email VARCHAR(255),
telefone VARCHAR(255),
PRIMARY KEY (id)
);
```
