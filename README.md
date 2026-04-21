# Referências Frontend

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

# Referências Negócio

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuário só pode visualizar transações o qual ele criou;

# Referências Ambiente

- [x] npm run knex -- migrate:latest | ler e criar as migration IMPORTANTE
- [x] criar .env e .env.test para banco de dados
- [x] npm run knex -- migrate:rollback | desfaz a migration criada, caso tenha errado algo
- [x] npm run knex -- migrate:make add-session-id-to-transactions | criar sessão dentro da tabela transaction
- [x] npm run dev | executar servidor
- [x] http localhost:3333/hello | executar aplicação (trazendo as tabelas)
- [x] usar validação de dotenv e routes com zod
- [x] @types knex para tipar as tabelas
- [x] npm i @fastify/cookie para salvar dados em cookie
- [x] middlewares fastify verifica se o cookie existe
- [x] instalar vitest para criar testes unitários
- [x] instalar tsup e rodar npm run build para criar build deploy
- [x] criar deploy com render.com
