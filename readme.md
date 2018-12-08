## Base 0.1

Como baixar?

git clone https://bitbucket.org/gutierre69/base.git

Como instalar?

Após baixar, importe para o MySQL ou MariaDB a base.sql que se encontra na raiz, também outros arquivos .sql na sequencia, ex: update-01.sql, update-02.sql, update-03.sql, etc...
Renomeie o arquivo database.sample.php para database.php e edite-o, colocando os seus dados de banco. Este arquivo encontra-se em /app/Config/.

Leitura e Escrita

Este projeto precisa permissão de leitura e escrita em dois diretórios: /app/tmp e /app/webroot/uploads

sudo chmod -R 777 /app/tmp

sudo chmod -R 777 /app/webroot/uploads

## Email

Como configurar?

Todos os envios são configurados em um único arquivo, em: /app/Config/email.php

Configure $smtp.

## Template

Estamos usando BOOTSTRAP 4 para o front, o Admin continua BOOTSTRAP 3.