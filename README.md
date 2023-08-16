
# Setup Docker Laravel 10 com PHP 8.1

### Passo a passo
Clone Repositório
```sh
git clone 
```
```sh
cd app-laravel
```


Crie o Arquivo .env
```sh
cp .env.example .env
```


Atualize as variáveis de ambiente do arquivo .env
```dosini
APP_NAME= NOME_DA_APLICAÇÂO
APP_URL=http://localhost:8989 

DB_CONNECTION= NOME_DA_CONEXÂO
DB_HOST= IP_DO_BANCO
DB_PORT= 5432
DB_DATABASE= NOME_DO_BASE_DE_DADOS
DB_USERNAME= NOME_DO_USUARIO
DB_PASSWORD= SENHA_DE_ACESSO

CACHE_DRIVER=redis
QUEUE_CONNECTION=redis
SESSION_DRIVER=redis

REDIS_HOST=redis
REDIS_PASSWORD=null
REDIS_PORT=6379
```


Suba os containers do projeto
```sh
docker-compose up -d
```


Acesse o container app
```sh
docker-compose exec app bash
```


Instale as dependências do projeto
```sh
composer install
```


Gere a key do projeto Laravel
```sh
php artisan key:generate
```


Acesse o projeto
http://localhost:8989
