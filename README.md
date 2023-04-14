# Bootcamp TQI Kotlin - Backend Developer - DIO
 
 Nesse diretório irei hospedar os arquivos do bootcamp

- [x] Configuração do VirtualBox
- [x] Instalação do Ubuntu Server
- [x] Configuração do SSH
- [x] Instalação Docker
- [x] Instalação Conteiner



Comandos docker:

- docker ps  !lista os containeres ativos
- docker ps -a !lista o historico dos containeres
- docker exec -it "ID" /bin/bash
- docker rm "ID" !remove o container - iniciais
- docker images !lista as imgs
- docker rmi img !remove a imagem
- docker run -dti "nome da imagem"
- docker run -dti --name Ubuntu-A ubuntu
- docker exec Ubuntu-A mkdir /destino (não preciso acessar a imagem pra fazer uma operação nela)
- docker cp MeuArquivo.txt Ubuntu-A:/destino (colo o arquivo no destino sem precisar acessar ele de fato)
- docker cp Ubuntu-A:/destino/Meuzip.zip ZipCopia.zip (faço uma copia c outro nome)

Iniciando um container MySQL via docker docker run -e MYSQL_ROOT_PASSWORD=senha123 --name mysql-A -d -p 3306:3306 mysql



 
