# BR_CE_RuralIrrigatingTRUE

## Objetivo

Documentar a regra atual do B2Win para servir de insumo na migracao para um componente LWC no Salesforce.

## Status da documentacao

Documentacao parcial. Ate o momento foram registrados:

- nome e status da regra
- 1 REACondition
- 1 item em ProductConfiguration

## Leitura funcional atual

A regra segue quando o parametro rural em SessionParameters e igual a true.

Na aba Actions, o item documentado em ProductConfiguration registra inelegibilidade para as classes BR:

- 10 - Residencial
- 11 - Residencial Baixa Renda
- 20 - Industrial
- 30 - Comercial
- 50 - Poder Publico
- 60 - Iluminacao Publica
- 70 - Servico Publico
- 80 - Consumo Proprio
- 9 - REVENDA

## Arquivo estruturado

Os dados extraidos foram organizados em [grupoB/BR_CE_RuralIrrigatingTRUE (Active)/BR_CE_RuralIrrigatingTRUE.json](grupoB/BR_CE_RuralIrrigatingTRUE%20(Active)/BR_CE_RuralIrrigatingTRUE.json).

## Pendencias

- confirmar se existem outros itens em ProductConfiguration alem do item documentado
- confirmar se BaseAction, SetAttribute, SetParameter e REAAction estao vazios ou se possuem valores
- complementar a descricao funcional da regra conforme forem chegando novos prints
