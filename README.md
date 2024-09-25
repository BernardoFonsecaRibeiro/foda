# Banco.1

# Exercicio 1
````sql
create table cientes (
codigo int primary key,
nome varchar (100),
email varchar (150),
dataNacimento date,
telefone varchar (15)
);
````
# Exercicio 2
````sql
create table produtos (
codigo int primary key,
nomeProduto varchar (100),
precoProduto decimal (8,2)
);
````
# Exercicio 3
```sql
create table fatura (
codigo int primary key,
DataCriacao date,
valorFatura decimal (10,2)
);
```

# Exercicio Complementares

# Exercicio 1
```sql
create table funcionarios (
id int primary key,
nome varchar (100),
sobrenome varchar (150),
salario decimal (10,2)
);
```
# Modificação exercicio 1
```sql
alter table funcionarios add DataNacimento varchar (8);
alter table funcionarios add IDDepartamentos int; 
alter table funcionarios rename column sobrenome to Apelido;
```
# Exercicio 2
```sql
create table departamento (
id int primary key,
Nome varchar (100)
);
```
# Exercicio 3
```sql
create table Projetos (
id int primary key,
NomeProjeto varchar (130)
);
```
# Modificação Exercicio 3
```sql
alter table Projetos add IDClientes varchar (100);
```
# Exercicio 4
```sql
create table Cliente (
id int primary key,
NomeCliente varchar (100)
);
```
# Exercicio 5
```sql
create table Enderecos (
id int primary key,
Rua varchar (100),
Cidade varchar (100),
CEP varchar (11)
);
```
