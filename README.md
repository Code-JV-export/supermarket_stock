<h2>Desenvolvimento de testes unitários em uma API REST de gerenciamento de estoque de um supermercado </h2>

Este projeto tem com o intuito de praticar o desenvolvimento de testes unitários emm uma API REST. 

Tal projeto teve como inspiração as aulas da Digital Innovation One (DIO).

Para executar o projeto no terminal, basta digitar o seguinte comando na raiz do projeto:

```shell script
mvn spring-boot:run
```

Para executar os testes do projeto, basta executar os eguinte comando:

```shell script
mvn clean test
```

Após a execução do comando acima, basta apenas entrar neste endereço:

```
http://localhost:8080/api/v1/beers
```

É necessario os seguintes requisitos para a execução do projeto:

* Java 14 ou versões superiores. Pode ser encontrado [aqui](https://www.oracle.com/br/java/technologies/javase/jdk14-archive-downloads.html)