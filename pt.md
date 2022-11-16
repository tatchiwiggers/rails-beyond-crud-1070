# BEYOND CRUD
ontem vcs viram então o CRUD em rails, hoje nos vamos falar de como ir alem de CRUD, como por exemplo vou mostrar pra vcs que nos nao estamos limitaos aos 7 CRUD actions, podemos criar rotas customizadas, vou mostrar pra vcs como criar rotar aninhadas e vamos falar tb de uma ferramenta de rails chamada scaffold.

# SETUP

# CREATE A NEW RAILS APP

# ADD BOOTSTRAP STYLESHEET

# ADD SIMPLE FORM 1/2
O Simple Form pode ser facilmente integrado ao Bootstrap 5. Bastando utilizar a opção bootstrap no gerador de instalação do simple form lançando esse codigo aqui no nosso terminal:

# ADD SIMPLE FORM 2/2
Agora podemos usar simple_form_for ao inves vez de form_with

vamos entao fazer uma rapida revisão do que vimos ontem:
esse é o codigo que precisamos escrever no nosso formulario, ou seja no nosso new da nossa aplicação rails que vai gerar o seguinte formulario HTML:
forms em rails são bastante complexos principalmente porque geramos nossos forms atraves de rails helpers como simple form que vão fazer todo o trabalho arduo de gerar todo o HTML pra gente, então para que não precisemos dedicar um dia inteiro a forms e eu matar vcs de tedio, recomendo que deem uma olhadinha da documentação de forms em rails ok?

# FIRST COMMIT

# CRUD
Aula passada

# 7 ACTIONS
na aula passada nos vimos que se fizermos resouces restaurants, nos conseguimos gerar as 7 rotas de CRUD em rails. 

# 7 ACTIONS - part 2

# SCAFFOLD
Only for demos not for projects
You never need all of the 7 CRUD actions in real projects

# vamos dar uma olhada no que o scaffold gerou pra gente:
- modelo restaurant
- nosso controller com todos os 7 metodos CRUD prontos
- nossos views icluindo nossos formularios.

Falei e repito, se vcs criarem o app de vcs hj utilizando o scaffold, nos vamos saber e vamos pedir pra vcs apagarem e começarem do zero ta?

# LAUNCH RAILS S

- USE RAILS ROUTES
- ActiveRecord::PendingMigrationError: EXPLAIN -> A MIGRAÇÃO CREATE TABLE FOI GERADA MAS NAO FOI FEITA!
rails db:migrate