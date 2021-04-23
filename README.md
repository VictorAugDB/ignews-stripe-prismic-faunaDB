# ignews-stripe-prismic-faunaDB
Projeto com integração com stripe, prismic e FaunaDB

Para rodar o projeto

crie conta no stripe, prismic e faunaDB

Para cada um dos serviços será necessário uma key que normalmente se encontrar nas settings da sua conta
eu deixei um arquivo .env.example para você poder verificar quais keys deve colocar para rodar o projeto.
crie um arquivo .env e coloque as keys nele

para que você consiga rodar é imprescindivel olhar a documentação das apis, pois existem coisa específicas a serem feitas pra tudo funcionar corretamente.

para testar o stripe é necessário rodar ele para ele interceptar as chamadas
stripe listen --forward-to 'endereço que a aplicação está rodando'
sem aspas.

Se quiser só rodar o projeto.

>yarn
>yarn dev
