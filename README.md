# Migrations

A micro-service for data migration.

## Configuration for development

N.B. Make sure you are setting correcly your docker environment.

- Run composer install: `docker exec -t directus-press.sindria.org-migrations su sindria -c "composer install -d /var/www/app/"`

- Setup config env: `cp .env.local .env`
