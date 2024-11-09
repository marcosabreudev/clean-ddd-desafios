# clean-ddd-desafios

# Mapeando o domínio

## Entities

- Product
    - id
    - color
    - size

- Inventory
    - productId
    - minAvaliable
    - available

## Use Cases

- ProductInventoryUseCase() : mostra o estoque de um determinado produto
- ProductInventoryNotifyUseCase() : alerta quando um determinado produto atingiu a quantidade mínima no estoque
- ProductSalesHistoryUseCase() : mostra o histórico de vendas de um determinado produto
- ProductInventoryHistoryUseCase() : mostra o histórico do estoque de um determinado produto
