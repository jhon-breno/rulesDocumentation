# BR_CE_CambioTitularidade_GrupoB

## Objetivo

Documentar a regra atual do B2Win para servir de insumo na migracao para um componente LWC no Salesforce.

## Status da documentacao

Documentacao parcial. Ate o momento foram registrados:

- nome e status da regra
- 1 REACondition
- 8 blocos de ProductConfiguration

## Leitura funcional atual

A regra segue quando o campo adjustment em SessionParameters termina com Owner.

Os 8 blocos de ProductConfiguration descrevem diferentes comportamentos por Classe BR, incluindo atribuicao padrao de Categoria de Tarifa BR, SubClasse BR, regras de atributos obrigatorios e ocultos.

## Arquivo estruturado

Os dados extraidos foram organizados em [grupoB/BR_CE_CambioTitularidade_GrupoB (Active)/BR_CE_CambioTitularidade_GrupoB.json](grupoB/BR_CE_CambioTitularidade_GrupoB%20(Active)/BR_CE_CambioTitularidade_GrupoB.json).

## Pendencias

- confirmar se existe algum outro bloco de ProductConfiguration alem dos 8 informados
- confirmar se BaseAction, SetAttribute, SetParameter e REAAction possuem valores
- validar se os nomes dos campos devem permanecer com acentos e espacos exatamente como no sistema origem
