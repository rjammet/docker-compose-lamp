# Serveurs LAMP avec Docker & Docker composer

Voici les différents modules qui seront installés:

* PHP
* Apache
* MySQL
* phpMyAdmin
* Redis

Différentes versions de PHP:
* [5.4.x](/5.4.x)
* [5.6.x](/5.6.x)
* [7.1.x](/7.1.x)
* [7.2.x](/7.2.x)
* [7.3.x](/7.3.x)
* [7.4.x](/7.4.x)

## Installation

Cloner ce repository dans un dossier (Recommendation dans un répertoire portant le nom de la version de PHP) 
Exécutez la commande: `docker-compose up -d`.
Lancer composer une nouvelle fois: `docker-compose build`

```shell
git clone https://github.com/rjammet/docker-compose-lamp.git
cd docker-compose-lamp/
git fetch --all
cp sample.env .env
docker-compose up -d
```

Le containter va s'installer puis s'initialiser. Une fois fini, vos serveurs LAMP sont lancés et accessible.
