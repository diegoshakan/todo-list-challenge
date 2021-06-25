# todo-list-rails
This challenge is to my students in the course of Ruby on Rails

## Utilizando a tecnologia Ruby on Rails iremos criar um To Do List (Lista de Tarefas)
Você quer aprender muitas tecnologias para se tornar um desenvolvedor top, porém, sem gestão de tempo e prioridades você pode ficar perdido no meio do caminho. Anotando o que quer aprender, datando início e fim, você se aprimorará e o que era difícil antes, ficará fácil para você, pois você está evoluindo.
Por isso você irá criar uma aplicação web para poder gerenciar essas informações.

## Habilidades que serão trabalhadas e desenvolvidas
1. Gestão organizacional;
2. Autodidatismo;
3. Implementação de bibliotecas no projeto;
4. Relacionamento entre entidades;
5. Compreensão de regras negociais;
6. Versionamento de código.

## Como proceder
1. Faça o fork deste projeto;
2. Aponte seu projeto local para o repositório "forkado";
3. Crie suas branches, após a funcionalidade faça o PR para a branch release/v0.1;
4. Após terminada a aplicação, faça o merge com sua branch Main;
5. Solicite o PR para este repositório (original) na branch com o seu nome.

### Requisitos
1. Criar Tarefa
  - Título -> Com no mínimo 6 caracteres e no máximo 30 caracteres;
  - Descrição -> **Obrigatório**;
  - Data de Início -> **Obrigatório**;
  - Data de Conclusão -> **Obrigatório**;
  - Concluído -> Campo booleano, inicia como false.

2. Criar Usuário
  - Implementar um sistema de login;
  - Nome e Sobrenome;
  - Email -> **Para autenticação**;
  - Password -> **Para autenticação**;
  Obs: *Usar a gem Devise*.
  
### Negocial
1. Um usuário poderá ter várias tarefas;
2. Um usuário só poderá visualizar as suas próprias tarefas;
3. O usuário poderá criar, atualizar, apagar suas tarefas;
4. A tela principal de entrada do usuário será uma listagem com suas tarefas;
5. A tarefa quando marcada como concluída, deverá apresentar alguma informação de que ela foi concluída.

### Plus
1. Teste Unitário;
2. Configurar o banco de dados Postgresql no projeto;
3. Fazer deploy no heroku - [Deploy no Heroku](https://medium.com/campuscode/deploy-de-uma-aplica%C3%A7%C3%A3o-ruby-on-rails-5-2-no-heroku-9e4352a973f9).

### Considerações
- O back-end deve ser feito utilizando Ruby on Rails;
- O front-end você pode fazer como desejar, usando algum framework javascript, ou o simples html, css e js;
- O projeto deve usar o git para controle de versão e deve estar hospedado no github;
- Será bom se os commits estiverem organizados pra facilitar a visualização da evolução do projeto.

### Evolução Futura (Faça se tiver tempo)
1. Adicionar comentários para as tarefas;
2. Na listagem das tarefas, informar quantos comentários existem em cada tarefa;
Obs: *Pesquisar sobre nested routes (rotas aninhadas)*.
