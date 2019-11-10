1- Qual o objetivo do comando cache em Spark?

O comando cache é utilizado para evitar o acesso ao disco repedidamente. Através dele é armazenado o resultado da consulta na memória, 
facilitando e deixando com que as consultas futuras sejam mais rápidos.


2- O mesmo código implementado em Spark é normalmente mais rápido que a implementação equivalente em
MapReduce. Por quê?

Com MapReduce o resultado de cada job é armazenado em disco. Com Apache Spark o acesso é feito em memória RAM,
temos acesso a dados da memória mais rápido que o acesso em disco, fazendo com o que a solução Apache Skark tenha uma velocidade superior que a MapReduce.

3 - Qual é a função do SparkContext?

Através da função SparkContext é útilizada para criar RDDs, colocar jobs em execução, criar variáveis de broadcast e acumuladores.
