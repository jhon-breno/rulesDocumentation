# BR_CE_Depend_Carga_y_Tension_A

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para dependência de carga e tensão no Grupo A quando potência for maior ou igual a 75.

## Condições (REACondition)
- `number(/Workspace/SessionParameters/Parameter[@name="potencia"]/@value)>=number("75")`

## ProductConfiguration

### 1
- **Ineligibility Actions:**
  - Valor de Tensão BR: 127 V,220 V,380 V
- **Required Actions:**
  - Atributos CE: Valor de Tensão BR

### 2
- **Default Actions:**
  - Tipo de Tensão BR: Trifásica
- **Read Only Actions:**
  - Atributos CE: Tipo de Tensão BR
