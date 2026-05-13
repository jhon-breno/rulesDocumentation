# BR_CE_PublicIlumTRUE

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para iluminação pública quando o parâmetro public for true, com bloqueio de categorias/classes/subclasses e definição de classe padrão.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="public"]/@value)="true"`

## ProductConfiguration
- **Ineligibility Actions (3):**
  - Categoria de Tarifa BR: lista completa enviada
  - Classe BR: 10 - Residencial,11 - Residencial Baixa Renda,20 - Industrial,30 - Comercial,40 - Rural,50 - Poder Público,70 - Serviço Público,80 - Consumo Próprio,9 - REVENDA
  - SubClasse BR: lista completa enviada
- **Default Actions (1):**
  - Classe BR: 60 - Iluminação Pública
