# Status Build

## Travis
[![Build Status](https://travis-ci.org/thiagonf/GCS01.svg?branch=master)](https://travis-ci.org/thiagonf/GCS01)
## CircleCI
[![CircleCI](https://circleci.com/gh/thiagonf/GCS01/tree/master.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/thiagonf/GCS01/tree/master)

# Django Basico

## Ambiente de Dev

O ambiente de dev utiliza o sistema operacional Ubuntu Trusty 64.

```
sudo apt-get install python-pip
sudo pip install django flake8
```

Após ter tudo instalado, prepare o ambiente rodando:

```
python manage.py migrate
```

Para rodar os testes:

```
python manage.py test
flake8 --exclude polls/migrations/,manage.py  .
```

### Acesso

Para rodar o projeto:

```
python manage.py runserver 0:8000
```

O acesso deve ser feito através do `localhost:8000`.


