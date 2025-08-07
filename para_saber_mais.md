## Para saber mais: A classe SparkSession

A classe SparkSession é o ponto de entrada para a programação do Spark com a API Dataset e DataFrame.

Uma SparkSession pode ser usada para criar DataFrames, registrar DataFrames como tabelas, executar comandos SQL sobre tabelas, armazenar tabelas em cache e ler arquivos em parquet.

Esta classe possui alguns métodos e atributos que utilizaremos ao longo das aulas e outros que seria interessante você conhecer. A documentação da classe pode ser acessada nesse [site do spark](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.SparkSession.html).

Para responder boa parte dos exercícios deste curso vamos sempre supor que a SparkSession spark está criada.

## Para saber mais: Data Types

Identificar os tipos de dados que possuímos em nossos datasets é um trabalho bastante importante no procedimento inicial de análise.

Nesta etapa nós podemos identificar erros de definição de tipo que podem nos atrapalhar no uso de ferramentas específicas para tratamento e análise, por exemplo, quando temos um dado numérico que esteja representado como uma string ou quando temos uma informação de data representada como uma string ou como um número.

Neste dois casos de exemplo teríamos problemas para extrair e realizar operações específicas dos reais tipos, como realizar uma simples operação aritmética.

Nesse [link](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/data_types.html) está a documentação e temos acesso aos tipos de dados que podemos utilizar com Spark. Nos próximos vídeos vamos ver como trabalhar com alguns destes tipos e como resolver problemas como estes que são apresentados nos parágrafos acima.
