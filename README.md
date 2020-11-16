# cognitivo_ai
Teste para Engenharia de Dados da Cognitivo AI

Esse teste teve por objetivo:
- converter o arquivo CSV para um formato colunar de alta performance de leitura;
- deduplicação dos dados convertidos, mantendo apenas o registro da entrada mais recente da variável 'update_date';
- conversão das variáveis para formatos específicos, fornecidos pelo arquivo types_mapping.json.

Todas as operações deveriam utilizar o Spark e cada opeação deveria ser realizada no data frame do passo anterior.

O formato colunar de alta perfomance de leitura escolhido foi o Parquet.
