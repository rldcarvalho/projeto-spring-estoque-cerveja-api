# Implementação de testes unitários em uma API REST

Projeto de elaboração de testes unitários para validar uma API REST que faz o gerenciamento de estoques de cerveja.

O objetivo foi evidenciar a importância da pirâmide de testes e do teste unitário utilizando o JUnit e Mockito, que nesse exemplo cobriu os processos de criação, listagem, consulta por nome e exclusão de cervejas. 
Além disso, foi possível aplicar o TDD (Test Driven Development) na implementação de duas novas funcionalidades: incremento e decremento do estoque.

Projeto criado com a mentoria do [Rodrigo Peleias](https://github.com/rpeleias-v1).

---
### Ferramentas utilizadas:
- [Spring](https://spring.io/)
- [JUnit](https://junit.org/junit5/docs/current/user-guide/)
- [Mockito](https://site.mockito.org/)
- [Hamcrest](http://hamcrest.org/JavaHamcrest/)

---
## Inicialização o projeto:

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```
