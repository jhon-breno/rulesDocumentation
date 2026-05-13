# BR_CE_FreeClientFALSE

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para clientes nao livres. Bloqueia categorias de tarifa livre quando o parametro free estiver false.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="free"]/@value)="false"`

## ProductConfiguration
- **Ineligibility Actions:**
  - Categoria de Tarifa BR: A1_LVVD - Categoria de tarifa A1 horo verde livre,A2_LVVD - Categoria de tarifa A2 horo verde livre,A3A_LVVD - Categoria de tarifa A3a horo verde livre,A3_LVVD - Categoria de tarifa A3 horo verde livre,A4_LVVD - Categoria de tarifa A4 horo verde livre,A2_LVAZ - Categoria de tarifa A2 horo azul livre,A1_LVAZ - Categoria de tarifa A1 horo azul livre,A3A_LVAZ - Categoria de tarifa A3a horo azul livre,A3_LVAZ - Categoria de tarifa A3 horo azul livreAS,A4_LVAZ - Categoria de tarifa A4 horo azul livre,A3_LVAZ - Categoria de tarifa A3 horo azul livre
