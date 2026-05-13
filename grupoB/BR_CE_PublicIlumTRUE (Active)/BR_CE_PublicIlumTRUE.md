# BR_CE_PublicIlumTRUE

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Regra para identificar iluminação pública. Se o parâmetro `public` for true, define Classe BR como Iluminação Pública.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="public"]/@value)="true"`

## ProductConfiguration
- **Default Actions:**
  - Classe BR: 60 - Iluminação Pública
