# estudo-docker-compose
Projeto do Curso Docker Ferramenta essencial para Desenvolvedores - Cod3r 

# comandos docker compose

`docker-compose up -d` = iniciar os processos (-d modo detach)

`docker-compose ps` = verificar processos que estão rodando

`docker-compose exec db psql -U postgres -f /scripts/check.sql` = executar scritp que verifica criação do banco e da tabela

`docker-compose down` = parar os processos

`docker-compose logs -f -t` = exibir logs dos processos

`docker-compose exec db psql -U postgres -d email_sender -c ‘select * from emails’` = listar as mensagens

`docker-compose up -d --scale worker=3` = iniciar processo com scale para levantar n instâncias de um serviço

`docker-compose scale worker=3` = scale para levantar n instâncias de um serviço

`docker-compose logs -f -t worker` = acompanhar apenas o log do serviço worker

