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