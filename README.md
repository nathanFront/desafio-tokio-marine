# Custumer Service

### Requisitos

1. JDK 8
1. Maven 3

### Rodando

1. Clone o projeto: `https://github.com/allanalves92/practical-test.git`
1. Entre na pasta `practical-test` e execute: `mvn spring-boot:run`
1. Acesse: `http://localhost:8080/customers`

## ROTAS 

/customers - Listar todos os clientes;
/custormers/id - Listar clientes por id
/customers/pages - Lista com as paginas
/customers/save - Salvar um novo cliente

{
    "name": "Nathan",
    "email": "nathan10borges@hotmail.com",
	"address": [
	     {"cep":"03922000"}, 
		 {"cep":"03288030"}
	]
 
 /customers/update - Atualizar Cliente
 /customers/delete/:id - Deletar Cliente

