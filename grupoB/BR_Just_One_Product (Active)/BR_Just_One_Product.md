# BR_Just_One_Product

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Permite apenas um produto do Grupo B no carrinho. Torna inelegível se houver mais de um.

## Condições (CartComposition)
- Cart: contains
- Type: product
- IfNotPresent: False
- Product Name: Grupo B
- Qty: >= 1

## Ações (BaseAction)
- Elegível: Não (not eligible)
- Visível: Sim
- Comentário: Só é permitido incluir um produto do Grupo B no carrinho.
