# Recipe App API
Recipe API project develop using Django Rest Framework and Docker

## Installing

This project uses Docker, and all commands to use and install are run with Docker.

> build project
```
docker compose build
```

> run project
```
docker compose up
```
```
docker compose up -d
```

> stop project
```
docker compose down
```

ps.: To verify your application open 127.0.0.1:8000

## Verifying the code patterns 

> to run flake8

```
docker compose run --rm app sh -c "flake8"
```

## Run unit tests 

> to run tests

```
docker compose run --rm app sh -c "python manage.py test"
```

## Django commands

> to create a new Django project

```
docker compose run --rm app sh -c "django-admin startproject app ."
```

> to create migrations

```
docker compose run --rm app sh -c "python manage.py makemigrations"
```

> to run migrations

```
docker compose run --rm app sh -c "python manage.py migrate"
```

## Contributing

Contributions are what make the open source community an incredible place to learn, inspire and create. Any contribution you make will be **much appreciated**.
1. Make a project Fork
2. Create a Branch for your feature (`git checkout -b feature/amazing-feature`)
3. Insert your changes (`git add .`)
4. Make a commit with your changes (`git commit -m 'feat(<scope>): Inserting a Amazing Feature !`)
5. Push the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## License

Distributed under the MIT license. See `LICENSE` for more information.

## Contact

Yury Alencar - [Github](https://github.com/yuryalencar) - **yuryalencar19@gmail.com**
