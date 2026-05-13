# BR_IneligibleFor_GrupoB

## Objetivo

Documentar a regra atual do B2Win para servir de insumo na migracao para um componente LWC no Salesforce.

## Status da documentacao

Documentacao parcial. Ate o momento foram registrados:

- nome e status da regra
- expressao de `REACondition` na aba `Conditions`
- 1 item de `ProductConfiguration` na aba `Actions`

## Leitura funcional atual

A regra valida o `companyid` em `SessionParameters` e somente segue quando o valor for diferente de `2005`.

Na aba `Actions`, o item documentado em `ProductConfiguration` registra uma acao de inelegibilidade para `Valor de Tensao BR = 127 V`.

## Arquivo estruturado

Os dados extraidos foram organizados em [grupoB/BR_IneligibleFor_GrupoB (Active)/BR_IneligibleFor_GrupoB.json](grupoB/BR_IneligibleFor_GrupoB%20(Active)/BR_IneligibleFor_GrupoB.json).

## Pendencias

- confirmar se existem outros itens em `ProductConfiguration` alem do item documentado
- confirmar se `BaseAction`, `SetAttribute`, `SetParameter` e `REAAction` estao vazios ou se possuem valores
- complementar a descricao funcional da regra conforme forem chegando novos prints