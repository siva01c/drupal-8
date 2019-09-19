# drupal-8

How start project

 * git clone https://github.com/siva01c/drupal-8.git myproject
 * cd myproject
 * cp .env.example .env
 * docker-compose up -d
 * docker-compose exec drupal bash
 * composer install

You will find your website on DAO_PORT_NGINX port, which is defined at .env file. Default location is http://localhost:1577.
