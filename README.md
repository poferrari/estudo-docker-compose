# estudo-docker-compose
Projeto do Curso Docker Ferramenta essencial para Desenvolvedores - Cod3r 

# comandos

`docker-compose up -d` = iniciar os processos (-d modo detach)

`docker-compose ps` = verificar processos que estão rodando

`docker-compose exec db psql -U postgres -f /scripts/check.sql` = executar scritp que verifica criação do banco e da tabela

`docker-compose down` = parar os processos

`docker-compose logs -f -t` = exibir logs dos processos

`docker-compose exec db psql -U postgres -d email_sender -c ‘select * from emails’` = listar as mensagens

