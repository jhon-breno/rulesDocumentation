# BR_CE_Depend_Carga_y_Tension_B

## Objetivo

Documentar a regra atual do B2Win para servir de insumo na migracao para um componente LWC no Salesforce.

## Status da documentacao

Documentacao parcial. Ate o momento foram registrados:

- nome e status da regra
- expressao de `REACondition` na aba `Conditions`
- os 2 itens existentes de `ProductConfiguration` na aba `Actions`

## Leitura funcional atual

A regra avalia a potencia informada em `SessionParameters` e somente segue quando:

- a potencia e menor que `75`
- o parametro `adjustment` nao termina com `Carga`

Na aba `Actions`, o conteudo identificado ate agora esta em `ProductConfiguration`. Os itens ja documentados aplicam restricoes para produtos com `Classe BR = 01-RESIDENCIAL` e `Classe BR = 02-INDUSTRIAL`, marcando como inelegiveis varias opcoes de `SubClasse CE`.

## Arquivo estruturado

Os dados extraidos foram organizados em [grupoB/BR_CE_Depend_Carga_y_Tension_B/BR_CE_Depend_Carga_y_Tension_B.json](grupoB/BR_CE_Depend_Carga_y_Tension_B/BR_CE_Depend_Carga_y_Tension_B.json).

## Pendencias

- confirmar se `BaseAction`, `SetAttribute`, `SetParameter` e `REAAction` estao vazios ou se possuem valores
- complementar a descricao funcional da regra conforme forem chegando novos prints