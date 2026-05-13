# BR_CE_Dep_Tarifa_GroupA-B

**Status:** Active  
**Grupo:** Grupo A-B  
**Origem:** B2Win  
**Descrição:**
Regra de dependência de tarifa para classes e subclasses dos Grupos A e B.

## ProductConfiguration (11)

1. SubClasse BR: RESBOPT - Residencial B-Optante
- Default Actions: Categoria de Tarifa BR = B1_RESID - Categoria de tarifa B1 residencial
- Read Only Actions: Atributos CE = Categoria de Tarifa BR

2. SubClasse BR: REPLN - Residencial Pleno

3. Modalidade Tarifaria BR: (vazio)
- Default Actions: Classe BR, SubClasse BR, Categoria de Tarifa BR (vazios)
- Read Only Actions: Atributos CE = Classe BR, SubClasse BR, Categoria de Tarifa BR

4. Classe BR: (vazio)
- Default Actions: SubClasse BR, Categoria de Tarifa BR (vazios)
- Read Only Actions: Atributos CE = SubClasse BR, Categoria de Tarifa BR

5. SubClasse BR: (vazio)
- Default Actions: Categoria de Tarifa BR (vazio)
- Read Only Actions: Atributos CE = Categoria de Tarifa BR

6. SubClasse BR: lista de optantes B
- Default Actions: Categoria de Tarifa BR = B3_OUTROS - Categoria de tarifa B3 outros
- Read Only Actions: Atributos CE = Categoria de Tarifa BR

7. SubClasse BR: lista geral (industrial/comercial/rural/poder público/serviço público/consumo próprio)
- Ineligibility Actions: Categoria de Tarifa BR = B3_OUTROS - Categoria de tarifa B3 outros

8. SubClasse BR: RURBOPT - Rural B-Optante, RUAQCOPT - Rural Optante Aquicultura / Irrigante
- Default Actions: Categoria de Tarifa BR = B2_RUR - Categoria de tarifa B2 rural
- Read Only Actions: Atributos CE = Categoria de Tarifa BR

9. Modalidade Tarifaria BR: OPTANTE
- Ineligibility Actions: Categoria de Tarifa BR (lista), Classe BR (lista), SubClasse BR (lista)

10. Modalidade Tarifaria BR: Horosazonal Azul
- Ineligibility Actions: Categoria de Tarifa BR (lista), SubClasse BR (lista)

11. Modalidade Tarifaria BR: Horosazonal Verde
- Ineligibility Actions: Categoria de Tarifa BR (lista), SubClasse BR (lista)

## Observação
- No item 10, como o texto veio sem rótulo explícito de ação após as listas, foi estruturado como Ineligibility Actions em 2 entradas para preservar integralmente os dados enviados.
