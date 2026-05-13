# BR_CE_CC_AltTarifa_GrupoA

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para alteração de tarifa no Grupo A. Oculta atributos CE específicos.

## Condições (REACondition)
- `ends-with(/Workspace/SessionParameters/Parameter[@name="adjustment"]/@value, "Tarifa")`

## ProductConfiguration
- **Hidden Actions:**
  - Atributos CE: Capacidade Disjuntor BR
  - Atributos CE: Instalação Padrão
  - Atributos CE: Nivel de Tensão BR
  - Atributos CE: Potencia KWA BR
  - Atributos CE: Tipo de Tensão BR
  - Atributos CE: Valor de Tensão BR
