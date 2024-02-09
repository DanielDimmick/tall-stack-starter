# Usage

To start the containers
```
docker compose up --build
```

Once started connect to the shell of the laravel container and run
```
composer i
npm i
php artisan migrate
```

To access the site open http://localhost:8000