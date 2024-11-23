# PHP + NGINX + MYSQL
Infraestrutura Docker-compose para criação de ambiente local de desenvolvimento em ecossistema PHP.

> PHP 8.3
> MySQL 8.4.3

# Instruções de uso
Fazer o download do repositório para Windows WSL / Linux / MacOS (garantir que o Docker está disponível no sistema)
Dentro da pasta do repositório executar o comando
  docker-compose up -d
Vão ser criados 3 containers: nginx, php e mysql
Utilizar o VSCode para acessar remotamente ao container de php e usar como pasta de trabalho /var/www/html

NOTA: É necessário criar uma pasta public dentro da pasta de trabalho
