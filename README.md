# Modelo conceitual - BD E-commerce
Modelo conteitual de banco de dados de um e-commerce

### Objetivo:

Em relação ao Produto, é conhecido que:
- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
- Cada produto possui um fornecedor
- Um ou mais produtos podem compor um pedido

Já em relação ao Cliente, temos:
- O cliente pode se cadastrar no site com seu CPF ou CNPJ
- O Endereço do cliente irá determinar o valor do frete
- Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações


Para o Pedido, foi identificado as seguintes informações:
- O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
- Um produto ou mais compoem o pedido
- O pedido pode ser cancelado

Além disso, há as seguintes informações adicionais:
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento
- Entrega – Possui status e código de rastreio









