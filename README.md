# Trabalhando com middlewares

Esse desáfio consistia em fazer os middlewares necessários para passar nos testes automatizados.

- ## [x] checksExistsUserAccount

  - Consiste em verificar a autencidade do usuário através de seu username que foi enviado pelo header.
- ## [x] checksCreateTodosUserAvailability

  - Verifica qual dos planos o usuário tem e se pode ou não fazer mais `ToDos`: Usuários tem a opção de criar um dos 2 planos, caso o usuário esteja usando o plano `pro` ele pode criar `ToDos` ilimitados, do contrário, com o plano gratuito só é possível criar um máximo de 10. 
- ## [x] checksTodoExists

  - faz 3 verificações, primeiro a autencidade do usuário, segundo verifica se o id enviado pelos parâmetros de rota é um UUID válido e por último confere se o id enviado equivale ao id de um dos `ToDos` desse usuário.
- ## [x] findUserById

  - Como o `checksExistsUserAccount`, esse middleware também confirma a autenticidade do usuário, porém, com o diferencial de ser pelo `ID`.