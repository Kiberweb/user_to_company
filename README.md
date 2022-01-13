# Instruction how to use
1) docker-compose up -d host start in localhost:7000

2)docker ps name: **php_fpm**

3)docker exec -it php_fpm bash

4)php artisan migrate

**Seed demo data**

5)php artisan db:seed --class=UserSeeder

6)php artisan db:seed --class=CompanySeeder