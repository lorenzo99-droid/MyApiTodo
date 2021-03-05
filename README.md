# MyApiTodo

**O projeto My_API foi inicialmente inspirado em ferramentas de organização de usuários e tarefas como o Trello. Nesse projeto incorporamos todos as quatro operações básicas do CRUD em funções, dinamizamos o funcionamento do nosso código com funções assíncronas e organizado no modelo MVC para facilitar o entendimento e o debugamento do código**

## Installation

Essa API exige que a ferramenta para rodar os arquivos no back seja o  [Node.js](https://nodejs.org/).

Para ter uma cópia desse projeto basta baixar a pasta src, arquivos package-json e lock-json, depois de instalados, rodar o comando no terminal para instalar a lista de dependências e outro comando para rodar a API.

```sh
cd MYAPI_TODO
npm install
npm start
```
*Número da porta usada port:**3030***

Para verificar a funcionalidade dos verbos da API restfull recomenda-se que use o app  **[insomnia](https://insomnia.rest/download/).**
## **Rotas**

### GET
    https://localhost:3030/tarefas  &  https://localhost:3030/tarefas/id = ?
    https://localhost:3030/usuarios  &  https://localhost:3030/usuarios/id= ?
### POST
    https://localhost:3030/tarefas
    https://localhost:3030/usuarios 
    
### PUT
    https://localhost:3030/tarefas/id = ?
     https://localhost:3030/usuarios/id= ?
### DELETE
     https://localhost:3030/tarefas/id = ?
     https://localhost:3030/usuarios/id= ?

### Quais as tecnologias envolvidas?
 
 ● Express
 ● Nodemon
 ● Body Parser
 ● Cors
 ● SQLite 3
 ● Insomnia
