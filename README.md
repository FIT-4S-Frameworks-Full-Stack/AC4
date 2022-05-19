# AC4

Este projeto usa sqlalchemy com postgresql
https://github.com/antoniodiasabc/docker_postgres

Execute ele com docker e tire um print da tabela posts com dados
(o proprio projeto tem um passo a passo para execucao)

Este projeto usa sqlalchemy com mysql
https://github.com/antoniodiasabc/sqlalchemy
Execute ele com docker (na parte de banco de dados mysql) tire um print das tabelas project e project_manager  com os dados armazenados
(o proprio projeto tem um passo a passo para execucao)

<hr/>

git clone https://github.com/antoniodiasabc/sqlalchemy

cd sqlalchemy/

ls -lrt

docker pull mysql:5.7

docker run --name mysql5 -e MYSQL_ROOT_PASSWORD=mudar123 -p 3306:3306 -d mysql:5.7

docker ps

docker exec -it 257d598cec09 /bin/bash

mysql -uroot -p

create schema teste;

pip install sqlAlchemy

pip install PyMySQL

python3 -m examples.basic

python3 -m examples.onetoone

python3 -m examples.onetomany
