# Organizador de pastas e arquivos

Este projeto é um organizador de pastas e arquivos que permite organizar seus arquivos por mês ou por tipo de arquivo.

## Como usar

Para usar o organizador, siga estas etapas:

1. Selecione a pasta origem que contém os arquivos que você deseja organizar.
2. Selecione a pasta destino onde deseja que os arquivos organizados sejam colocados.
3. Clique no botão "Organizar".

O organizador irá organizar os arquivos da pasta origem de acordo com as regras definidas no dicionário `regras_arquivos`.

## Regras de organização

As regras de organização são definidas no dicionário `regras_arquivos`. Cada chave do dicionário representa uma regra de organização. O valor da chave representa o novo nome da pasta que o arquivo será movido.

Por exemplo, a regra `jan: Janeiro` significa que todos os arquivos que começam com a string "jan" serão movidos para uma pasta chamada "Janeiro".
