# docker-octobercms2

starting point for october cms 2 plugin development

License key needed to install ...

## usage

````
docker-compose up -d --build

# inside php docker container
composer create-project october/october .
php artisan october:install
php artisan october:migrate
````
