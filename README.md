```sql
require 'redcaroet'
markdown = redcarpet.new("hello world!")
puts markdown.to_html
```

```sql
-- Criando banco de dados
create database trabalho;

-- usar banco de dados
use trabalho;
```

```sql
exercício 1
-- criar tabela clientes
create table clientes (
codigo int primary key,
nome varchar (100),
email varchar (150),
dataNascimento date,
telefone varchar (15)
);
```

```sql
exercício 2
-- criando tabela do exercicio 2
create table produtos (
codigo int primary key,
nome varchar (100),
preco decimal (8,2)
);
```

```sql
exercício 3
-- criando tabela do exercicio 3
create table faturas (
codigo int primary key,
dataCriacao date,
valor decimal (10,2)
);
```

```sql
exercicios complementares

-- criando tabela exercicios complementares
create table funcionarios (
codigo int primary key,
nome varchar (100),
sobrenome varchar (100),
salario decimal(10,2)
);
```

```sql
-- adicionando uma coluna na tabela funcionarios
alter table funcionarios add dataNascimento date;
```

```sql
-- adicionando uma coluna a mais na tabela funcionarios
alter table funcionarios add idDepartamento int;
```

```sql
-- renomeando uma coluna
alter table apelido rename column sobrenome to funcionarios;
```

```sql
-- adicionando uma coluna na tabela
alter table funcionarios add idEndereco varchar(100);
```

```sql
-- criando tabela departamemento
create table departamento (
codigo int primary key,
nome varchar (100)
);
```

```sql
create table alocacoes (
codigo primary key 
);
```

```sql
-- criando tabela projeto
create table projeto (
codigo int primary key,
nome varchar (100)
);
```

```sql
alter table projeto add IDCliente varchar (100);
```

```sql
create table pedidos (
id int primary key,
data_pedido date
);
```

```sql
create table endereco(
codigo primary key
rua varchar(50)
cidade varchar(50)
cep  int 
);
```

```sql
create table intenspedidos (
codigo primary key
);
```

```sql
create table estoques(
 ID_produtos int primary key,
 quantidade_produtos
 );
 ```

 ```sql
 alter table estoques add IDprodutos int;
 ```

 ```sql
 -- criando a tabela vendas
create table vendas (
codigo int primary key,
dataVendas date
);
```

```sql
alter table vendas add IDCliente varchar (100);
```



