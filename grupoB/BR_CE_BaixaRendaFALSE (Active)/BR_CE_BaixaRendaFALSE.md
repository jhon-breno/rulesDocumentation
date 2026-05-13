# BR_CE_BaixaRendaFALSE

## Objetivo

Documentar a regra atual do B2Win para servir de insumo na migracao para um componente LWC no Salesforce.

## Status da documentacao

Documentacao parcial. Ate o momento foram registrados:

- nome e status da regra
- expressao de REACondition na aba Conditions
- 1 item de ProductConfiguration na aba Actions

## Leitura funcional atual

A regra valida o parametro lowIcome em SessionParameters e segue quando o valor e false.

Na aba Actions, o item documentado em ProductConfiguration registra inelegibilidade para:

- Classe BR: 11 - Residencial Baixa Renda
- SubClasse BR: REBRBPC, REBRIND, REBRQUI, REBXR, RBXRDS, REBXDS

## Arquivo estruturado

Os dados extraidos foram organizados em [grupoB/BR_CE_BaixaRendaFALSE (Active)/BR_CE_BaixaRendaFALSE.json](grupoB/BR_CE_BaixaRendaFALSE%20(Active)/BR_CE_BaixaRendaFALSE.json).

## Pendencias

- confirmar se existem outros itens em ProductConfiguration alem do item documentado
- confirmar se BaseAction, SetAttribute, SetParameter e REAAction estao vazios ou se possuem valores
- validar se o parametro e lowIcome ou lowIncome no sistema origem
- complementar a descricao funcional da regra conforme forem chegando novos prints
