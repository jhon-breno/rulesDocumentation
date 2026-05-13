# BR_CE_CC_AltCarga_GrupoB

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Regra para alteração de carga no Grupo B. Inabilita SubClasse BR para Residencial Desconto Social e oculta diversos atributos CE.

## Condições (REACondition)
- `ends-with(/Workspace/SessionParameters/Parameter[@name="adjustment"]/@value, "Carga")`

## ProductConfiguration
- **Ineligibility Actions:**
  - SubClasse BR: RBXRDS - Resid. Desconto Social
- **Hidden Actions:**
  - Atributos CE: Capacidade Disjuntor BR
  - Atributos CE: Categoria de Tarifa BR
  - Atributos CE: Classe BR
  - Atributos CE: Demanda Fora de Ponta BR
  - Atributos CE: Demanda KV BR
  - Atributos CE: Demanda Ponta BR
  - Atributos CE: Instalação Padrão
  - Atributos CE: Modalidade Tarifaria BR
  - Atributos CE: Nivel de Tensão BR
  - Atributos CE: Potencia KWA BR
  - Atributos CE: SubClasse BR
  - Atributos CE: Valor de Tensão BR
