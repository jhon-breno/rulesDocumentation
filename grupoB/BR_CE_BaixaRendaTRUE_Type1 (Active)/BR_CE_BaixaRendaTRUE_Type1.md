# BR_CE_BaixaRendaTRUE_Type1

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Regra para clientes do Grupo B com TypeBx true e lowIcome false. Define categoria e classe residencial padrão.

## Condições (REACondition)
- `((/Workspace/SessionParameters/Parameter[@name="TypeBx"]/@value)="true") and not((/Workspace/SessionParameters/Parameter[@name="lowIcome"]/@value)="true")`

## ProductConfiguration
- **Default Actions:**
  - Categoria de Tarifa BR: B1_RESID - Categoria de tarifa B1 residencial
  - Classe BR: 10 - Residencial
