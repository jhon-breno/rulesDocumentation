# BR_CE_WhiteRateTRUE

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para cliente com tarifa branca ativa. Bloqueia modalidades tarifarias especificas.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="white"]/@value)="true"`

## ProductConfiguration
- **Ineligibility Actions:**
  - Modalidade Tarifaria BR: Horosazonal Azul,Horosazonal Verde,HORO AZUL
