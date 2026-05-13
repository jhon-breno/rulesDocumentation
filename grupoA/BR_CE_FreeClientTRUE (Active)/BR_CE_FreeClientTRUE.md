# BR_CE_FreeClientTRUE

**Status:** Active  
**Grupo:** Grupo A  
**Origem:** B2Win  
**Descrição:**
Regra para clientes livres. Restringe categorias de tarifa quando o parâmetro free está true.

## Condições (REACondition)
- `(/Workspace/SessionParameters/Parameter[@name="free"]/@value)="true"`

## ProductConfiguration
- **Ineligibility Actions:**
  - Categoria de Tarifa BR: A1_AZ - Categoria de tarifa A1 horosazonal azul,A1_CONV - Categoria de tarifa A1 convencional,A1_VD - Categoria de tarifa A1 horosazonal verde,A2_AZ - Categoria de tarifa A2 horosazonal azul,A2_CONV - Categoria de tarifa A2 convencional,A2_GER - Categoria de tarifa A2 gerador,A2_GERAZ - Categoria de tarifa A2 gerador azul,A2_GERVD - Categoria de tarifa A2 gerador verde,A2_VD - Categoria de tarifa A2 horosazonal verde,A3A_AZ - Categoria de tarifa A3a horosazonal azul,A3A_CONV - Categoria de tarifa A3a convencional,A3A_GER - Categoria de tarifa A3a gerador,A3A_GERAZ - Categoria de tarifa A3a gerador azul,A3A_GERVD - Categoria de tarifa A3a gerador verde,A3A_VD - Categoria de tarifa A3a horo verde,A3_AZ - Categoria de tarifa A3 horosazonal azul,A3_CONV - Categora de tarifa A3 convencional,A3_GER - Categoria de tarifa A3 gerador,A3_GERAZ - Categoria de tarifa A3 gerador azul,A3_GERVD - Categoria de tarifa A3 gerador verde,A3_VD - Categoria de tarifa A3 horosazonal verde,A4_AZ - Categoria de tarifa A4 horosazonal azul,A4_CONV - Categoria de tarifa A4 convencional,A4_GER - Categoria de tarifa A4 gerador,A4_GERAZ - Categoria de tarifa A4 gerador azul,A4_GERVD - Categoria de tarifa A4 gerador verde,A4_VD - Categoria de tarifa A4 horosazonal verde,B1_RESID - Categoria de tarifa B1 residencial,B2_RUR - Categoria de tarifa B2 rural,B3_OUTROS - Categoria de tarifa B3 outros,B4A_IP - Categoria de tarifa B4a ilum. pública,B4B_IP - Categoria de tarifa B4b ilum. pública,DUMMY - Categoria de tarifa DUMMY,ELE_LIST - CATEGORIA TARIFFA A LISTINO - FORMAT,ELE_PRICE - CATEGORIA TARIFFA A PREZZO - FORMAT,GAS_MM - CATEGORIA TARIFFA GAS MM - FORMAT,GAS_PROC - CATEGORIA TARIFFA GAS PROCEDURE,MED_FISCAL - Categoria de Tarifa Medição Fiscal,MIGRADO - Categoria de tarifa para dados Migrados,A1_GERAZ - Categoria de tarifa A1 gerador azul
  - Modalidade Tarifaria BR: OPTANTE
