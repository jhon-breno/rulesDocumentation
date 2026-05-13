# BR_CE_Other_Depencies_A

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra de outras dependências para Grupo A, incluindo elegibilidade por classe/modalidade e definição de nível de tensão por valor de tensão.

## ProductConfiguration (4)

### 1
- **Ineligibility Actions:**
  - Classe BR: 11 - Residencial Baixa Renda
  - Modalidade Tarifaria BR: HORO AZUL
- **Required Actions:**
  - Atributos CE: Classe BR
  - Atributos CE: Modalidade Tarifaria BR
  - Atributos CE: SubClasse BR
  - Atributos CE: Valor de Tensão BR
- **Hidden Actions:**
  - Atributos CE: Capacidade Disjuntor BR
  - Atributos CE: Instalação Padrão
- **Read Only Actions:**
  - Atributos CE: Nivel de Tensão BR

### 2
- **Product Conditions:**
  - Valor de Tensão BR: 127 V,220 V,380 V
- **Default Actions:**
  - Nivel de Tensão BR: Baixa Tensão

### 3
- **Product Conditions:**
  - Valor de Tensão BR: 11.4 KV,13.8 KV,34.5 KV
- **Default Actions:**
  - Nivel de Tensão BR: Média Tensão

### 4
- **Product Conditions:**
  - Valor de Tensão BR: 69 KV,138 KV,230 KV
- **Default Actions:**
  - Nivel de Tensão BR: Alta Tensão
