# RF

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

# RN

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
- [ ] Deve ser possível identificarmos o usuário entre as requisições;
- [ ] O usuário só pode visualizar transações o qual ele criou;


npm run knex -- migrate:latest | ler e criar as migration IMPORTANTE
criar .env e .env.test para banco de dados
npm run knex -- migrate:rollback | desfaz a migration criada, caso tenha errado algo
npm run knex -- migrate:make add-session-id-to-transactions | criar sessão dentro da tabela transaction (alterar)
npm run dev | executar servidor
http localhost:3333/hello | executar aplicação (trazendo as tabelas)
usar validação de dotenv e routes com zod
@types knex para tipar as tabelas
npm i @fastify/cookie para salvar dados em cookie
middlewares fastify verifica se o cookie existe
instalar vitest para criar testes unitários
instalar tsup e rodar npm run build para criar build deploy
