# BR_CE_CC_AltPotencia_GrupoA

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para alteração de potência no Grupo A, ocultando atributos CE específicos.

## Condições (REACondition)
- `ends-with(/Workspace/SessionParameters/Parameter[@name="adjustment"]/@value, "Potencia")`

## ProductConfiguration
- **Hidden Actions:**
  - Atributos CE: Capacidade Disjuntor BR
  - Atributos CE: Instalação Padrão
  - Atributos CE: Nivel de Tensão BR
  - Atributos CE: Tipo de Tensão BR
