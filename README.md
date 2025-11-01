# Refinando um modelo lógico de banco de dados voltado a um site de E-commerce

Primeiro desafio do projeto da plataforma [DIO](https://www.dio.me/) curso "SQL Database Specialist".

## 🛒 E-Commerce 

- **Entidades:** Produto, Estique, Fornecedor, Pedido, Cliente. 

## 📖 Narrativa

**1. Produto**

- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros).
- Cada produto possui um fornecedor.
- Um ou mais produtos podem compor um pedido.

**2. Cliente**
- O cliente pode se cadastrar no site com seu CPF ou CNPJ. 
- O Endereço do cliente irá determinar o valor do frete.
- Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

**3. Pedido**

- Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega.
- Um produto ou mais compoem o pedido.
- O pedido pode ser cancelado. 

## ✍️ Descrição do desafio 
 
Refinamento do modelo lógico aprimorando o funcionamento utilizando os seguintes requisitos:

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações.
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento.
- Entrega – Possui status e código de rastreio.

## 💡Solução

<img align="center" src="https://github.com/rodrigo-sza-almeida/DIO_sql_database_specialist_e-commerce_esquema/blob/main/e_commerce.png" width=""/> 

## 🧑‍💻 Tecnologia utilizada 

![MySQL Workbench](https://img.shields.io/badge/MySQL%20Workbench-ffffff?style=for-the-badge&logo=mysql&logoColor=black)
