# C3 Data Converter
Tools to fast and easy read data from database

## Specification
Eu como desenvolvedor quero obter de forma rápida os dados de uma banco de dados em um formato especifico.

Dado os dados de acesso a banco de dados em uma arquivo datasource.json o comando a seguir deve retornar uma imagem png:

    easyreaddb  -f postgre  -q query.sql -d file.png

Sintaxe geral:

easyreaddb -f [postgre | oracle | sqlite3]  -q [""| query] -d file.[jpg, png, tiff, txt, csv]
