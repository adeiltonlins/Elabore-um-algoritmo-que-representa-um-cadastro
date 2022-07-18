# Elabore-um-algoritmo-que-representa-um-cadastro
create table dbo.cadastro
( 
chave_pl int not null IDENTITY('1,1) primary Key,
nome: varchar(500) not null,
sobrenome: varchar(500)not null,
endereço: varchar(500) not null
cidade:varchar(500) not null
CPF:varchar(500) not null
Rg:varchar(500) not null
idade:varchar(500) not null
nome do pai:varchar(500) not null
nome da mae:varchar(500) not null
peso:varchar(500) not null
renda bruta:varchar(500) not null
INSET INTO [dbo].[cadastro]
([nome]
,[sobrenome]
,[endereço]
,[idade]
,[nome do pai]
,[nome da mãe]
,[peso]
,[renda bruta] )
VALUES
('joão'
, 'santos'
, 'rua da soledade'
, '25'
, 'jose'
, 'Clara'
, ' 80 ' 
, ' 2.000,00')
