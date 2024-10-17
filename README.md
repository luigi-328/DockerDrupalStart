cd drupal/ <br>
composer install --ignore-platform-reqs <br>
cd .. <br>
docker compose up -d <br>
<br>
conf db durante install: <br>
db: drupal <br>
user: drupal <br>
pass: drupal <br>
host: drupal-db <br>
<br>
<br>
localhost:8080 -> drupal <br>
localhost:8081 -> adminer
