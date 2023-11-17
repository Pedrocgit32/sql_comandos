
# Comando SQL

* Para executar os comandos pressione CTRL + Enter

### Criar database
```
create database NOME_DATABASE;
```

### Definir a database de uso
```
use NOME_DATABASE;
```

### Criar tabela de usuários
```
create table usuarios(
 id int not null auto_increment,
 nome varchar(120) not null,
 email varchar(120) not null,
 senha varchar(120) not null,
 dt_nascimento date,
 primary key(id)
);
```
### Insert dados
```
INSERT INTO usuarios(nome, email, senha, dt_nascimento)
VALUES ('Andrei', 'andreivupt@gmail.com', 'sucesso', '1994-09-13');
```

### Listar dados da tabela de usuarios
```
select * from usuarios;
```