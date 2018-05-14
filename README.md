# React_Django_Boilerplate Code

Boiler plate code to use React and Django together without much configuration.

# Installing

After cloning the repo.

```bash
$ cd react_django_boilerplate
$ docker-compose build
```


# Running the App
```bash
$ docker-compose up
```

Or if you've yet to build the docker images:

```bash
$ docker-compose up --build
```

# Running in production

First build the static files.

```bash
$ yarn build
```

Run the server with production settings.

```bash
$ python manage.py runserver --settings=production_settings
```

# Note

You may need to install babel-loader

```bash
$ yarn add babel-loader --dev
```

You might also need to run collect static for you server to see you static files

```bash
$ python manage.py collectstatic
```



