# BR_CE_CargaByDefaut

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win

## Condicoes (REACondition)
- `(number(/Workspace/SessionParameters/Parameter[@name="potencia"]/@value)>number("0")) and not(ends-with(/Workspace/SessionParameters/Parameter[@name="adjustment"]/@value, "Carga"))`

## ProductConfiguration
- **Default Actions:**
  - Carga KW BR: 0

## REAAction
- **Action type:** COMPLEX SET ATTRIBUTE
- **Attribute/Node:** value
- **Destination node:** /Workspace/Products/Product/
- **Parent node:** (vazio)
- **First Parameter:** Xpath Query = /Workspace/SessionParameters/Parameter[@name="potencia"]/@value
- **Operation:** Add
- **Second Parameter:** Simple = 0
- **Expression:** /Workspace/Products/Product/Property[@name='Carga KW BR']

## Observacao
- O valor de First Parameter foi preenchido com o caminho de potencia para manter coerencia com a regra. Se quiser, posso ajustar para o caminho exato mostrado no B2Win.
