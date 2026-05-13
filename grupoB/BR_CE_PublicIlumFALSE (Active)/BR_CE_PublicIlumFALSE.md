# BR_CE_PublicIlumFALSE

**Status:** Active  
**Grupo:** Grupo B  
**Origem:** B2Win  
**Descrição:**
Regra para identificar iluminação pública quando o parâmetro `public` for false. Define categoria de tarifa, classe e subclasse BR para iluminação pública.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="public"]/@value)="false"`

## ProductConfiguration
- **Categoria de Tarifa BR:**
  - B4B_IP - Categoria de tarifa B4b ilum. pública, B4A_IP - Categoria de tarifa B4a ilum. pública
- **Classe BR:**
  - 60 - Iluminação Pública
- **SubClasse BR:**
  - ILPUBL - Iluminação Pública
