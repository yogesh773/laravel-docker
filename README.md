# Laravel Docker Project

## Steps Followed

1. Created project Directory `laravel-docker`.
2. Added `docker-compose.yml` with two services: PHP-FPM and Nginx.
3. Created directory `nginx` Added `default.conf` for Nginx configuration.
4. Created `src` directory to hold Laravel project.
5. Installed Laravel using Composer containe
   command = `docker run --rm -v $(pwd)/src:/app composer create-project laravel/laravel .`
6. Set permissions for SQLite database
   command = chmod -R 777 src/src/database 
7. Started Docker containers:
   command =  `docker ps`
   command = `docker-compose up -d`
8. Application runs on: http://localhost:8000



