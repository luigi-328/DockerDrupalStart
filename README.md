cd drupal/
composer install --ignore-platform-reqs
cd ..
docker compose up -d

conf db durante install:
db: drupa
user: drupal
pass: drupal
host: drupal-db


localhost:8080 -> drupal
localhost:8080 -> adminer
