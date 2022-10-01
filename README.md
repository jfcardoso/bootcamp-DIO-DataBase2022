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
## Desafio#2: Diagrama ER - Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica-v.1
### Requisitos:
#### Oficina
-  Os clientes levam seus veículos à oficina mêcanica para serem
consertados ou para passarem por revisões periódicas.
- Cada veículo é designado a uma equipe de mecânicos que
identifica os serviços a serem executados e preenche uma
OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço,
consultando-se uma tabela de referência de mão-de-obra.
- O valor de cada peça também irá compor a OS.
- O cliente autoriza a execução dos serviços.
- A mesma equipe avalia e executa os serviços.
- Os mecânicos possuem código, nome, endereço e
especialidade.
- Cada OS possui: n°, data de emissão, um valor, status e uma
data para conclusão dos trabalhos.
- Uma OS pode ser composta por vários serviços e um mesmo
serviço pode estar contido em mais de uma OS.
- Uma OS pode ter vários tipos de peça e uma peça pode
estar presente em mais de uma OS.
