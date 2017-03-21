Symfony Docker
==================

### Installation
* create *.env* file from *.env.dist* and configure values
* run 'symfony new symfony 2.8'
* configure *app/config/parameters.yml*
* run 'docker-compose build'
* run 'docker-compose up -d'

### Run Commands
Use 'docker-compose exec php' to run commands in container.

**Example:**

`docker-compose exec php php /var/www/symfony/app/console c:c`