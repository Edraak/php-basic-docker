# Basic php dev setup (Php-fpm + nginx + mysql)



## Installation

Download and install [docker desktop](https://www.docker.com/products/docker-desktop).

Verify by running: 
```bash
docker -v
```


## Usage

Just run 
```bash
docker compose up
```

Verify by testing: [localhost/index.php](http://localhost/index.php)

Now you can edit your code in /code folder, and observe the results right away in the browser.

## mysql

To run mysql shell run:
```bash
docker compose exec mysql mysql
```

You can access mysql from php:
```yml
host: mysql
port: 3306
user: root
pass:
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[Apache License](https://en.wikipedia.org/wiki/Apache_License)# php-basic-docker
