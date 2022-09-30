# Bootcamp Database 2022 - DIO
Atividades relacionadas ao Bootcamp DataBase 2022 da DIO
## Desafio#1: Diagrama ER em um cenário de e-commerce - v.1
### Requisitos:
#### Produto:
- Os produtos são vendidos por uma única plataforma online.
Contudo, estes podem ter vendedores distintos (terceiros).
- Cada produto possui um fornecedor.
- Um ou mais produtos podem compor um pedido.
#### Pedido:
- Os pedidos são criados por clientes e possuem informações de
compra, endereço e status da entrega.
- Um produto ou mais compoem o pedido.
- O pedido pode ser cancelado.
#### Cliente:
- O cliente pode se cadastrar no site com seu CPF ou CNPJ.
- O Endereço do cliente irá determinar o valor do frete.
- Um cliente pode comprar mais de um pedido.
- O pedido tem um período de carência para devolução do produto.
#### Desafios propostos para o refinamento do diagrama:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não
pode ter as duas informações
- Pagamento – Pode ter cadastrado mais de uma forma de
pagamento
- Entrega – Possui status e código de rastreio
