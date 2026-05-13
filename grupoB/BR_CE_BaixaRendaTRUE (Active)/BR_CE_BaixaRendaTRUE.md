# BR_CE_BaixaRendaTRUE

## Objetivo

Documentar a regra atual do B2Win para servir de insumo na migracao para um componente LWC no Salesforce.

## Status da documentacao

Documentacao parcial. Ate o momento foram registrados:

- nome e status da regra
- expressao de REACondition
- 2 Default Actions

## Leitura funcional atual

A regra segue quando:

- lowIcome em SessionParameters e igual a true
- TypeBx em SessionParameters e diferente de true

Foram identificadas duas acoes padrao:

- Categoria de Tarifa BR: B1_RESID - Categoria de tarifa B1 residencial
- Classe BR: 11 - Residencial Baixa Renda

## Arquivo estruturado

Os dados extraidos foram organizados em [grupoB/BR_CE_BaixaRendaTRUE (Active)/BR_CE_BaixaRendaTRUE.json](grupoB/BR_CE_BaixaRendaTRUE%20(Active)/BR_CE_BaixaRendaTRUE.json).

## Pendencias

- confirmar se existem valores em SetAttribute, SetParameter, ProductConfiguration e REAAction
- validar se o parametro e lowIcome ou lowIncome no sistema origem
- complementar a descricao funcional da regra conforme forem chegando novos prints
