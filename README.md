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
alter table funcionarios add IDDepartamentos int (15); 
alter table funcionarios rename column sobrenome to Apelido;
alter table funcionarios add IDEndereco int (15);
```
# Exercicio 3
```sql
create table departamento (
id int primary key,
Nome varchar (100)
);
```
# Exercicio 5
```sql
create table Projetos (
id int primary key,
NomeProjeto varchar (130)
);
```
# Modificação Exercicio 5
```sql
alter table Projetos add IDClientes varchar (100);
```
# Exercicio 8
```sql
create table Cliente (
id int primary key,
NomeCliente varchar (100)
);
```
# Modificação Exercicio 8
```sql
alter table Cliente rename column NomeCliente to NomeEmpresa;
```
# Exercicio 10
```sql
create table Enderecos (
id int primary key,
Rua varchar (100),
Cidade varchar (100),
CEP varchar (11)
);
```
# Exercicio 13
```sql
create table Pedidos (
Id int primary key,
DataPedidos date
);
```
# Modificação Exercicio 13
```sql
alter table funcionarios add IDClientes varchar (15);
```
# Exercicio 15
```sql
create table ItensPedido (
Id int primary key,
IDPedido date
);
```
# Exercicio 16
```sql
create table Produtos (
Id int primary key,
NomeProduto varchar (100),
QuantidadeProduto decimal (1000),
ValorProduto decimal (10,2)
);
```
# Modificação Exercicio 16
```sql
alter table Produtos rename column NomeProduto to DescricaoProduto;
```
# Exercicio 18
```sql
create table Estoques (
Id int primary key,
Quantidade decimal (1000)
);
```
# Modificação Exercicio 18
```sql
alter table  Estoques add IDProduto varchar (15);
```
# exercicio 20
```sql
create table Vendas (
Id int primary key,
DataVEndas date
);
```
# Modificação Exercicio 20
```sql
alter table  Vendas add IDCliente varchar (15);
```