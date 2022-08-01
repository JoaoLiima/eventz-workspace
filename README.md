Para realização do desafio optei por usar Node, Typescript, NestJS, MariaDB e TypeORM

## Requisitos para executar a aplicação
* Node
* NPM ou yarn
* Docker e docker-compose
* GIT

## Execução da aplicação

Para executar a aplicação: 
1. Clone o repositório e os submódulos;
2. Entre na pasta eventz-api e instale as dependências com `yarn install` ou `npm install`;
3. Na pasta eventz-workspace, execute `docker-compose up` ou `sudo docker-compose up` para inicializar o projeto;
4. Abra o terminal, navegue até a pasta eventz-api e execute `yarn migrate` ou `npm run migrate`, para executar as migrations no banco de dados
5. É possível baixar um arquivo para importar as requisições no Insomnia [aqui](https://drive.google.com/file/d/1rqiyyF5rDdEeHEI5tpoveDQZfxk1zsHS/view?usp=sharing)


## Funcionalidades

* Criação de usuários de tipos tipos diferentes (admin ou costumer)
* Permissionamento baseado no tipo de usuário
* CRUD de admins, costumers e eventos
* Compra de ingressos para os eventos


## Melhorias futuras

* Integrar cartões de crédito para adicionar fundos a carteira
* Incluir o swagger para facilitar a realização de requisições
* Adicionar tabela de transações para registrar os eventos comprados pelos consumidores
