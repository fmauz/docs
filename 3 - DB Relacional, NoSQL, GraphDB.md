## ACID

`Em ciência da computação, ACID é um conjunto de propriedades de transação em banco de dados. No contexto de banco de dados, transação é uma sequência de operações de banco de dados que satisfaz as propriedades ACID e, portanto, pode ser percebida como uma operação lógica única sobre os dados.` - Wikipédia

- **A**tomicidade

Em uma transação envolvendo duas ou mais tabelas, ou a transação será executada totalmente ou não será executada. garantido que a transação seja atômica.

- **C**onsitencia

A transação cria um novo estado dos dados ou em caso de falha retorna todos os dados ao seu estado antes que a transação foi iniciada.

- **I**solamento

Um transação em andamento mas ainda não validada deve permanecer isolada de qualquer outra operação.

- **D**urabilidade

Dados válidados pelo sistema precisa ser registrados de tal forma que mesma no caso de uma falha e/ou reinicio do sistema, os dados estarão disponíveis.

 

## Banco de Dados Relacional

#### MySQL, PostgreSQL, MSSQL, Oracle, Sqlite



## Banco de Dados NoSQL

#### MongoDB, Redis



## Banco de Dados Graph

#### RedisGraph, Neo4j, GraphDB





## Problemas

* Transactions
* N+1