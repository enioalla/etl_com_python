# ETL com Python
Esse repositório contém arquivos de data frame base para desenvolver aplicação de ETL em python. 
Essa aplicação faz parte do desafio ETL em Python do bootcamp Santander 2023 da [DIO](https://www.dio.me) 


## Files
O repositório possui:
1 arquivo .csv do dataframe original
1 arquivo . ipynp contendo o código da ETL
1 arquivo .csv gerado através da ETL



## Passos executados na ETL

### Importação de arquivo
O arquivo vgsales.csv é importado, através da biblioteca pandas
### Transformação do arquivo
O arquivo é, então filtrado, contendo apenas os jogos para a plataforma Wii com venda global superior ou igual a 1.0 milhões.

### Novo Arquivo
O novo arquivo é criado (vendas_wii.csv) contendo apenas os jogos filtrados na etapa anterior.
