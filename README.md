# Laravel Docker Setup
## Instructions
- Spin up the containers using: `docker-compose up -d --build site`
- Feel free remove and re-install laravel inside `/src` folder
- Running composer, eg: `docker-compose run --rm composer update`
- Running npm, eg: `docker-compose run --rm npm run dev`
- Running artisan commands, eg: `docker-compose run --rm artisan migrate`

## Available services
- nginx - `:80`
- mysql - `:3306`
- php - `:9000`
- redis - `:6379`
- mailhog - `:8025`