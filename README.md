# About

Make a recipe and add ingredients, image, and tags.

Filter recipes by tags and ingredients.

Automated testing of API endpoints.

# Prerequisites

Install [Docker](https://docs.docker.com/get-docker/) and [Docker Compose]().

# Usage

### Clone

```bash
git clone https://github.com/Tantan1939/recipe-app-api.git
```

### Build

```bash
docker-compose build
```

### Migrate

```bash
docker-compose run --rm app sh -c "python manage.py migrate"
```

### Run

```bash
docker-compose up
```

# Test

### Run the unit tests

```bash
docker-compose run --rm app sh -c "python manage.py test"
```

# API Documentations

Open this [Link](http://localhost:8000/api/docs/) in your browser.

## Create user

![create-user](./docx-imgs/create-user.png)

## Login

![authenticate-user](./docx-imgs/authenticate.png)

![authorize-btn](./docx-imgs/authorize-btn.png)

![login-user](./docx-imgs/login.png)

## Recipe APIs

![manage-recipes](./docx-imgs/recipe-APIs.png)
