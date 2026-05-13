# BR_CE_CC_AltDemanda_GrupoA

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para alteração de demanda no Grupo A, ocultando atributos CE específicos.

## Condições (REACondition)
- `ends-with(/Workspace/SessionParameters/Parameter[@name="adjustment"]/@value, "Demanda")`

## ProductConfiguration
- **Hidden Actions:**
  - Atributos CE: Capacidade Disjuntor BR
  - Atributos CE: Categoria de Tarifa BR
  - Atributos CE: Classe BR
  - Atributos CE: Instalação Padrão
  - Atributos CE: Modalidade Tarifaria BR
  - Atributos CE: Nivel de Tensão BR
  - Atributos CE: SubClasse BR
  - Atributos CE: Tipo de Tensão BR
  - Atributos CE: Valor de Tensão BR
  - Atributos CE: Potencia KWA BR
