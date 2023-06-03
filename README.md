# Projeto E-commerce - Prova N2
#   Aluno: André Matos
###07. Sistema de Loja Online:

Classes: Loja, Cliente, Produto, Carrinho
Relações: Associação entre Loja e Cliente, Associação entre Loja e Produto, Associação entre Cliente e Carrinho, Associação entre Carrinho e Produto

Sistema de Loja Online:

Loja:
nome: string
endereco: string
Cliente:
nome: string
endereco: string
Produto:
nome: string
preco: float
Carrinho:
cliente: Cliente
produtos: Produto[]

## Banco de dados

![Modelo de banco de dados](./assets/image/banco-ads4-n2.png "Modelo de banco de dados escrito na 3ª Forma Normal - 3FN")

## UML

![Uml do projeto](./assets/image/uml-ads4-n2.png "Modelo UML")

## Tecnologias utilizadas

**
* C - create
* R - readById
* R - Read()
* U - update
* D - delete
* microserviço

*>>  http://localhost:8080/swagger-ui.html#/
 *>>  http://localhost:8080/h2-console/login.jsp?jsessionid=dcaf7daf6390f19ae45e75984693dc9d
