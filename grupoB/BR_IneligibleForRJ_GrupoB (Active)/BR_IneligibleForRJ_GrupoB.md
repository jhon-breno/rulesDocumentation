# BR_IneligibleForRJ_GrupoB

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Regra para tornar inelegível Grupo B no RJ quando Valor de Tensão BR for 380 V.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="companyid"]/@value)="2005"`

## ProductConfiguration
- **Ineligibility Actions:**
  - Valor de Tensão BR: 380 V
