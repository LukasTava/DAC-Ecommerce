# Sistema de E-commerce

## Descrição

Este é um sistema simples de e-commerce desenvolvido com **Jakarta Persistence API (JPA)**. Ele permite gerenciar clientes, produtos, pedidos, pagamentos e entregas. O sistema também inclui funcionalidades como carrinho de compras e aplicação de cupons de desconto.

## Funcionalidades

- Cadastro de clientes com múltiplos endereços
- Listagem de produtos por categorias
- Adição de produtos ao carrinho de compras
- Criação de pedidos e pagamentos
- Aplicação de cupons de desconto
- Rastreamento e status de entregas

## Entidades

1. **Cliente**: Gerencia as informações dos clientes.
2. **Endereço**: Vários endereços para cada cliente.
3. **Produto**: Produtos disponíveis para compra.
4. **Categoria**: Categorias dos produtos.
5. **Carrinho**: Armazena os itens que o cliente deseja comprar.
6. **ItemCarrinho**: Produtos dentro do carrinho.
7. **Pedido**: Pedido realizado com base no carrinho.
8. **Pagamento**: Informações de pagamento do pedido.
9. **CupomDesconto**: Aplicação de descontos nos pedidos.
10. **Entrega**: Rastreamento da entrega do pedido.
