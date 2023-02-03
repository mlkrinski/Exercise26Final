# Exercise26Final

# Exercício Final - Consumindo uma API

### Finanças Pessoais

Desenvolva uma aplicação web de página única utilizando html, css e javascript para controle de finanças pessoais que atenda aos seguintes requisitos:

- sua aplicação deverá utilizar a biblioteca json-server para simular um backend que armazena transações financeiras.
- transações devem possuir, pelo menos, as propriedades id (gerenciado pelo json-server), nome e valor.
- a aplicação deverá mostrar na página todas as transações salvas no backend.
- a aplicação deverá ter um formulário para criar uma nova transação no backend (sem atualizar a página) através de uma requisição POST.
- novas transações criadas devem aparecer na lista de todas as transações assim que são criadas, tudo isso sem atualizar a página.
- a aplicação deverá permitir editar os dados de uma transação através de uma requisição PUT (o PUT funciona da mesma forma que o POST, enviando dados a serem atualizados no body e com o id do recurso a ser editado na url).
- a aplicação deverá permitir excluir uma transação através de uma requisição DELETE (as requisições DELETE não precisam de um body, apenas do id do recurso a ser excluído na url).
- a aplicação também deverá mostrar na página o saldo total, que é calculado somando todos os valores das transações (que podem ser positivos ou negativos).
- o valor do saldo total deve estar sempre atualizado na tela, ou seja, ao criar, editar ou excluir uma transação o saldo deverá refletir o novo valor.
