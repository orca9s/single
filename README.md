# EB DOCKER Deploy

## Requiremets
- python (3.6)
- pipenv
- Django (2.x)

### Secrets

#### `.secrets/base.json`

```json
{
  "SECRET_KEY": "<Django secret key>"
}
```

## Installation

```
pipenv install
```


## Runnning

```
# Move project's directory
- pipenv install
- pipenv shell
- cd app
- export DJANGO_SETTINS_MODULE=config.settings.local
./manage.py runserver
```