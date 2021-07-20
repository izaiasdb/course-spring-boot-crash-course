Curso: Introduction to Spring Boot for beginners
https://www.youtube.com/playlist?list=PLiPfbGXxKXnc-CXnrZUFVJjPLFAnd_sww
Aulas: 17
https://github.com/Awdesh/spring-boot-crash-course

********************************************* docker (subir para onedrive)
instalar docker
https://hub.docker.com/_/postgres

caso não tenha o docker
https://phoenixnap.com/kb/install-docker-on-ubuntu-20-04

comandos docker
https://woliveiras.com.br/posts/comandos-mais-utilizados-no-docker/

ver imagens local do docker
sudo docker images 

baixar uma imagem do postgres
sudo docker pull postgres

instanciar/criar um container postgres
docker run --name [nome imagme] -e POSTGRES_PASSWORD=210184 -d [nome banco]
sudo docker run --name curso-spring-postgres -e POSTGRES_PASSWORD=[senha basica] -p 5432:5432 -d postgres

ver os containers que estão ativos rodando
sudo docker ps

ver os containers que foram criados independente se estão ativos
sudo docker ps -a

iniciar container (pega iniciais da id do container, não dá imagem)
sudo docker start 783

parar container (pega iniciais da id do container, não dá imagem)
sudo docker stop 783

remover container
sudo docker rm 783

remover a imagem
sudo docker rmi 783
********************************************* swagger / springfox (Muito show)
Documentação e tem também como se fosse um client, do tipo postman
http://localhost:8080/swagger-ui/

