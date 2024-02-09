# Usage (Local Development Only!)
This repo will start a laravel 10 TALL stack in Docker

To start the containers
```
docker compose up --build
```

Once started connect to the shell of the laravel container and copy ./laravel/.env.example to ./laravel/.env and then run
```
composer i
npm i
php artisan key:generate
php artisan migrate
npm run build
```

To access the site open http://localhost:8000
