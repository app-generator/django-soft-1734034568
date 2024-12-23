# [Generated](https://app-generator.dev/) Django Project

Starter built with [App Generator](https://app-generator.dev/), an open-source service.

In order to use the sources, follow the build instructions as presented in `Start with Docker` and `Manual Build` sections. 

<br />

## Features: 

- `Up-to-date Dependencies`, Django `4.2.8`
- Modern UI
- Extended User Profile 
- API Generator (optional)

<br />

## Deploy on `Render` (free plan)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

<br /> 

## Start with `Docker`

> In case the starter was built with Docker support, here is the start up CMD:

```bash
$ docker-compose up --build
```

Once the above command is finished, the new app is started on `http://localhost:5085`

<br />

## Manual Build 

> Download/Clone the sources  

```bash
$ git clone https://github.com/<THIS_REPO>.git
$ cd <LOCAL_Directory>
```

<br />

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> `Set Up Database`

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> `Start the App`

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />



__OAUTH_GITHUB__

---
Starter built with [App Generator](https://app-generator.dev/), a free service provided by **AppSeed**.
