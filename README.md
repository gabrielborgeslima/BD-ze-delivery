# Zé Delivery ![Logo Zé Delivery](https://github.com/gabrielborgeslima/banco_de_dados/blob/32081987c0638bed60fda523efddbf25be2de33f/icon-ze-deliveryrd.png)

Trata-se do banco de dados do app Zé Delivery, onde o público-alvo típico é composto por adultos que desejam comprar bebidas alcoólicas para consumo em suas casas ou em eventos sociais. A plataforma oferece a conveniência de encomendar bebidas geladas online e tê-las entregues, no local escolhido, em pouco tempo.

Em resumo, o banco de dados permite o gerenciamento de pedidos, estoque, vendedores e estabelecimentos parceiros.


## Requisitos do Sistema

- Os clientes podem se registrar no sistema, fornecendo informações como login, senha, nome, CPF, email, endereço e telefone.
- Os clientes podem fazer pedidos, adicionando várias bebidas ao carrinho. Cada pedido inclui detalhes como códigos de produtos, nomes de produtos, quantidades e valores.
- Os pedidos registram data e hora do pedido, bem como o tempo de espera atual.
- Os pedidos incluem um valor total da compra.
- Os pedidos têm um status que pode ser: PEDIDO REALIZADO, EM ANDAMENTO, A CAMINHO ou ENTREGUE.
- Os fornecedores de bebidas e o estoque são registrados, incluindo a quantidade disponível de cada produto para delivery.
- Os vendedores também podem se registrar no sistema, com informações como código do vendedor, código da loja física, nome do vendedor e telefone. Alguns vendedores podem ter permissão de administrador.
- As lojas físicas são registradas com informações como código da loja, nome da loja, endereço e telefone.
- Um relatório mensal de vendas é gerado para acompanhar as informações das lojas que estão vendendo mais bebidas, incluindo o valor total de vendas, data de início e data de fim do relatório.


## Estrutura do Banco de Dados

O sistema utiliza um banco de dados relacional que inclui as seguintes tabelas principais:

- Tabela "USUARIO"
- Tabela "VENDEDOR"
- Tabela "LOJA"
- Tabela "RELATORIO"
- Tabela "ESTOQUE"
- Tabela "PRODUTO"
- Tabela "ITEM_PEDIDO_VENDA"
- Tabela "PEDIDO_VENDA"

As tabelas estão relacionadas de acordo com as necessidades do sistema e conforme representado abaixo:

![Representação do Banco de Dados](https://github.com/gabrielborgeslima/BD-ze-delivery/blob/6088d72c0c68ba2981668fdbf661133c5ebf3caa/BD_ze-delivery.png)


## Como Usar

Você pode usar este banco de dados para gerenciar pedidos de bebidas, acompanhar as vendas das lojas físicas, manter o controle do estoque, gerar insights de inteligência de mercado e outras estatísticas relevantes para o sucesso do negócio.


## Autor

[Gabriel Lima](https://github.com/gabrielborgeslima)
