# Definição de Banco de Dados

Os bancos de dados são conjuntos de arquivos relacionados entre si, com registros sobre pessoas, lugares ou informações em geral. São portanto uma coleção de dados para coletar, formatar, armazenar e usar informações com uma determinada funcionalidade. Os bancos de dados são operados pelos Sistemas Gerenciadores de Bancos de Dados (SGBD).

# Sistema de gerenciamento de um banco de dados ou SGBD

É o sistema de software responsável pelo gerenciamento de um ou mais bancos de dados. Seu principal objetivo é retirar da aplicação cliente a responsabilidade de gerenciar o acesso, a persistência, a manipulação e a organização dos dados. O SGBD disponibiliza uma interface para que seus clientes possam incluir, alterar ou consultar dados previamente armazenados.

# Sql

SQL é a sigla para “Structured Query Language”, que significa, traduzindo para o português, “Linguagem de Consulta Estruturada”. Trata-se de uma linguagem de consulta a banco de dados relacionais.
O SQL é utilizado para executar vários comandos como criar, alterar, gerenciar, consultar, etc no seu banco de dados.
Os bancos SQL seguem uma modelagem relacional, pois estes se baseiam no fato de que todos seus dados sejam guardados em tabelas. É uma linguagem declarativa dividida em conjuntos de comandos Data Definition Language (DDL), Data Manipulation Language (DML), Data Control Language (DCL), Transactional Control Language (TCL) e Data Query Language (DQL).

# NosSql

NoSQL (Not Only SQL) é o termo utilizado para banco de dados não relacionais de alto desempenho onde, geralmente, o SQL não é utilizado como linguagem de consulta.
O NoSQL foi criado para ter uma performance melhor e uma escalabilidade mais horizontal para suprir necessidades onde os bancos relacionais não são eficazes. 

### Documento
Os dados são armazenados como documentos. Os documentos podem ser descritos como dados no formato de chave-valor, como por exemplo, o padrão JSON.
Um exemplo de banco de dados neste formato é o MongoDB.

### Colunas
Os dados são armazenados em linhas particulares de tabela no disco, podendo suportar várias linhas e colunas, além de permitir sub-colunas.
Um banco de dados dessa família, por exemplo, é o Cassandra.

### Grafos
Os dados são armazenados na forma de grafos (vértices e arestas).
O Neo4j é um banco que utiliza grafos.

### Chave-valor
Essa família de bancos NoSQL é a que aguenta a maior carga de dados, pois o conceito dela é que um determinado valor seja acessado através de uma chave identificadora única.
Um exemplo é o banco de dados Riak. 

# Diferenças Sql x NoSql e em que contexto utilizar cada
A utilização de cada um deles depende da demanda.

Caso saiba listar exatamente o que deve ser armazenado em seu banco de dados e estes dados exigem grande consistência, preza por um banco com suporte da comunidade para tirar dúvidas e prefere aprender uma linguagem padronizada e bastante regularizada, SQL é a melhor escolha. Ainda vale ressaltar que, essencialmente, SQL não é uma linguagem de programação, sendo assim, pode ser a melhor escolha para iniciantes.

Entretanto, se seus dados são dinâmicos e mudam constantemente, você não tem uma estrutura bem definida do que armazenar ali, exige uma maior performance ou prevê que irá escalar rapidamente, talvez um banco NoSQL seja o melhor pra você.


