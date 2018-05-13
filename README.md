# React_Django_Boilerplate Code

Boiler plate code to use React and Django together without much configuration.

# Installing

After cloning the repo.

```bash
$ cd react_django_boilerplate
```

##### For the backend

```bash
$ cd backend
$ pip install -r requirements.txt
```

##### For the frontend

```bash
$ cd frontend
$ yarn install
$ yarn add webpack-bundle-tracker --dev
```

# Running the App

```bash
$ yarn start
```

```bash
$ python manage.py runserver
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



