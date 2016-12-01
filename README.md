# Project Name

Docker Wordpress Container

This is a Custom version of a docker Wordpress Container and MariaDB.

## Installation

Git clone:

```
git clone https://github.com/Esteban-Rocha/docker_wordpress.git
```

Docker

```
docker-compose up -d
```

## Usage
Goto:

 + http://localhost

## Folder Structure

 + database
```
Volume standing at MariaDB container on /home
For dumps and data export / import.
```

 + www
```
Volume standing at Wordpress container on /var/www/html
Your wordpress code base goes here.
```

## Credentials

### MariaDB

	MYSQL USER: wp_db_admin
	MYSQL DATABASE: wp_docker_db
	MYSQL PASSWORD: 123123

	root PASSWORD: 7SgkH6292yqzfXjQSY3B

Enjoy!

## History

 + m@Ver_1.0.0

## Credits

Esteban Rocha

## License

Project under the [BSD LICENSE](LICENSE)
