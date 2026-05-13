# BR_CE_CC_AltTarifa_GrupoB

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Regra para alteração de tarifa no Grupo B. Destaca SubClasse BR e oculta diversos atributos CE.

## Condições (REACondition)
- `ends-with(/Workspace/SessionParameters/Parameter[@name="adjustment"]/@value, "Tarifa")`

## ProductConfiguration
- **Atributos CE:**
  - SubClasse BR
- **Hidden Actions:**
  - Atributos CE: Capacidade Disjuntor BR
  - Atributos CE: Carga KW BR
  - Atributos CE: Demanda Fora de Ponta BR
  - Atributos CE: Demanda KV BR
  - Atributos CE: Demanda Ponta BR
  - Atributos CE: Instalação Padrão
  - Atributos CE: Modalidade Tarifaria BR
  - Atributos CE: Nivel de Tensão BR
  - Atributos CE: Potencia KWA BR
  - Atributos CE: Tipo de Tensão BR
  - Atributos CE: Valor de Tensão BR
